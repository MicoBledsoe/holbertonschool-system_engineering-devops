# 0x04 MySQL Configuration and Scripts

Welcome to the MySQL section of the `holbertonschool-system_engineering-devops` repository. This directory contains various scripts and configuration files aimed at setting up MySQL replication and backups for a web server infrastructure.

### Files and Descriptions

#### 4-mysql_configuration_primary

**Purpose:** This script configures the primary MySQL server for replication.

**Contents:**
#```bash
[mysqld]
server-id = 1
log_bin = /var/log/mysql/mysql-bin.log
binlog_do_db = include_database_name


#### 4-mysql_configuration_replica

**Purpose:** Sets up the replica MySQL server configuration.

**Contents:**
#```bash
[mysqld]
server-id = 2
relay-log = /var/log/mysql/mysql-relay-bin.log
log_bin = /var/log/mysql/mysql-bin.log
binlog_do_db = include_database_name


#### 5-mysql_backup

**Purpose:** Script to create backups of the MySQL databases.

**Contents:**
#```bash
#!/usr/bin/env bash
mysqldump --all-databases -u root -p > alldb_backup.sql
tar -czvf alldb_backup.$(date +%F).tar.gz alldb_backup.sql


#### sql_install

**Purpose:** Script to install MySQL and setup the initial environment.

**Contents:**
#```bash
#!/usr/bin/env bash
apt update
apt install -y mysql-server
mysql_secure_installation

## Collaborators
Mico Bledsoe - LinkedIn(www.linkedin.com/in/micobledsoe)

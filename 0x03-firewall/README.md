# Project: 0x03-firewall

## Project Description
This project involves setting up firewall rules using UFW (Uncomplicated Firewall) on a server. The objective is to secure the server by configuring rules that control incoming and outgoing network traffic.

## Files Description

- **0-block_all_incoming_traffic_but**: Script to block all incoming traffic except for SSH, HTTP, and HTTPS ports.
- **README.md**: Documentation of the firewall project.

## Configuration Details

The firewall is configured to allow connections only on the following ports:
- SSH (port 22)
- HTTP (port 80)
- HTTPS (port 443)

All other incoming connections are blocked by default. This configuration ensures basic security measures are in place to protect the server from unauthorized access.

## Usage

To activate the firewall rules, run the following command:

#```bash
sudo ufw enable
sudo ufw allow 22/tcp
sudo ufw allow 80/tcp
sudo ufw allow 443/tcp

Verify the status and rules of UFW with:
'sudo ufw status verbose'

## Collaborators
Mico Bledsoe - LinkedIn(www.linkedin.com/in/micobledsoe)

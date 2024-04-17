# Project: Shell Basics

This project is an introduction to the basic commands within the Unix shell. It covers navigation, file handling, and other fundamental shell operations.

#### Table of Contents

- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Files in this Project](#files-in-this-project)
- [Usage](#usage)
- [Contributions](#contributions)

#### Overview

Understanding the basics of the Unix shell is crucial for software development, especially in environments where Linux is used. This project contains scripts that demonstrate fundamental shell commands and operations.

#### Technologies Used

- Bash 4.3.48
- Tested on Ubuntu 20.04 LTS

#### Files in this Project

- `0-current_working_directory` - Script that prints the absolute path name of the current working directory.
- `1-listit` - Displays the contents of your current directory.
- `2-bring_me_home` - Changes the working directory to the user’s home directory.
- `3-listfiles` - Displays current directory contents in a long format.
- `4-listmorefiles` - Lists all files (including hidden) in the current directory in long format.
- `5-listfilesdigitonly` - Displays current directory contents with user and group IDs displayed numerically.
- `6-firstdirectory` - Creates a directory named `my_first_directory` in the `/tmp/` directory.
- `7-movethatfile` - Moves the file `betty` from `/tmp/` to `/tmp/my_first_directory`.
- `8-firstdelete` - Deletes the file `betty`.
- `9-firstdirdeletion` - Deletes the directory `my_first_directory` that is in the `/tmp` directory.
- `10-back` - Changes the working directory to the previous one.
- `11-lists` - Lists all files (even ones that begin with a period character, which are normally hidden) in the current directory and the parent of the working directory and the `/boot` directory (in this order), in long format.
- `12-file_type` - Prints the type of the file named `iamafile`.
- `13-symbolic_link` - Creates a symbolic link to `/bin/ls`, named `__ls__`.
- `14-copy_html` - Copies all the HTML files from the current working directory to the parent of the working directory, but only copies files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

#### Usage

Each script can be executed by running a command in the terminal. For example:

#```bash
./0-current_working_directory

## Collaborators
Mico Bledsoe - LinkedIn(www.linkedin.com/in/micobledsoe)

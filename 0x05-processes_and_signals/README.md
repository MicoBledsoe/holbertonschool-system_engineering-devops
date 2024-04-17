### Project: Processes and Signals in Bash

This project is designed to introduce the basics of process management and signal handling in Unix-like operating systems using Bash scripts.

#### Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [File Descriptions](#file-descriptions)
- [Usage Examples](#usage-examples)
- [Further Reading](#further-reading)

#### Introduction

Understanding processes and how to manipulate them is fundamental in systems engineering. This project covers how to manage processes and handle signals using shell commands and scripts.

#### Requirements

- A Linux shell environment
- Basic knowledge of shell scripting
- Permissions to execute Bash scripts

#### File Descriptions

- `0-what-is-my-pid` - Script that displays its own process ID.
- `1-list_your_processes` - Script to list all current processes in a hierarchical format.
- `2-show_your_bash_pid` - Script that displays the PID of all instances of bash that are running.
- `3-show_your_bash_pid_made_easy` - Simplified script using `pgrep` to show Bash process IDs.
- `4-to_infinity_and_beyond` - Script demonstrating an infinite loop outputting a message every 2 seconds.
- `5-dont_stop_me_now` - Demonstrates a script that ignores `SIGTERM` and continues running.
- `6-stop_me_if_you_can` - Script that can be stopped with a `SIGTERM` signal.
- `7-highlander` - Script that continuously outputs a message and handles `SIGTERM` with a custom message without stopping.
- `8-beheaded_process` - Script that stops itself when receiving a `SIGINT` signal.


### Further Reading

#```markdown
#### Further Reading

- [Linux Process Management](https://www.tldp.org/LDP/Linux-Filesystem-Hierarchy/html/Linux-Filesystem-Hierarchy.html)
- [Understanding Linux Signals](https://man7.org/linux/man-pages/man7/signal.7.html)

## Collaborators
Mico Bledsoe - LinkedIn(www.linkedin.com/in/micobledsoe)

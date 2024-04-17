### Shell Permissions

This section of the repository focuses on managing file and directory permissions in Unix/Linux. Learn how to handle different types of permissions and modify them using shell scripts.

#### Table of Contents

- [Overview of Shell Permissions](#overview-of-shell-permissions)
- [Scripts Included](#scripts-included)
- [Usage Examples](#usage-examples)
- [Contributions](#contributions)

#### Overview of Shell Permissions

In Unix-like operating systems, file permissions control the actions that can be performed on files and directories. Each file is associated with a user and a group, along with three types of permissions:
- **Read (r)**: Permission to read the file.
- **Write (w)**: Permission to modify the file.
- **Execute (x)**: Permission to run the file as a program.

#### Scripts Included

- **0-iam_betty:** Switches the current user to the user `betty`.
- **1-who_am_i:** Displays the effective username of the current user.
- **2-groups:** Prints all the groups the current user is part of.
- **3-new_owner:** Changes the owner of a file to the user `betty`.
- **4-empty:** Creates an empty file named `hello`.
- **5-execute:** Adds execute permission to the owner of the file `hello`.
- **6-multiple_permissions:** Adds execute permission to the owner and the group owner, and read permission to other users, for the file `hello`.
- **7-everybody:** Adds execution permission to the owner, the group owner, and other users, for the file `hello`.
- **8-James_Bond:** Sets the permissions to 007 for the file `hello`.
- **9-John_Doe:** Sets the permissions to 753 for the file `hello`.
- **10-mirror_permissions:** Mirrors the permissions of one file to another.
- **11-directories_permissions:** Adds execute permission to all subdirectories of the current directory for the owner, the group owner, and all other users.
- **12-directory_permissions:** Creates a directory with permissions 751 in the working directory.
- **13-change_group:** Changes the group owner to `holberton` for the file `hello`.

#### Usage Examples

To change the file owner to `betty` for a file named `hello`:
#```bash
./3-new_owner hello

To display the effective username of the current user:
./1-who_am_i

To set all permissions to rwx for everyone on a file named hello:
chmod 777 hello


### Section 5: Contributions
#```markdown
#### Contributions

Contributions to this project are welcome! To contribute, please follow these steps:
- Fork the repository.
- Create a new branch with your feature: `git checkout -b my-new-feature`.
- Commit your changes: `git commit -am 'Add some feature'`.
- Push to the branch: `git push origin my-new-feature`.
- Submit a pull request.

Mico Bledsoe - LinkedIn(www.linkedin.com/in/micobledsoe)

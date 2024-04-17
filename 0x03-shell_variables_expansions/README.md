### Project: Shell Variables and Expansions

This project explores the fundamentals of shell initialization files, variables, expansions, and shell arithmetic. The focus is on understanding and manipulating environment variables and shell expansions in Bash.

#### Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [File Descriptions](#file-descriptions)
- [Usage Examples](#usage-examples)
- [Contributing](#contributing)

#### Introduction

Shell variables are essential for managing user environments and script behavior. This project covers creating, listing, and using local and global variables along with introducing special parameters and shell expansions.

#### Requirements

- Access to a Bash shell
- Basic knowledge of shell scripting
- Permissions to execute scripts

#### File Descriptions

- `0-alias` - Script that creates an alias.
- `1-hello_you` - Script that prints `hello user`, where user is the current Linux user.
- `2-path` - Adds `/action` to the `PATH`. `/action` should be the last directory the shell looks into when looking for a program.
- `3-paths` - Script that counts the number of directories in the `PATH`.
- `4-global_variables` - Lists environment variables.
- `5-local_variables` - Lists all local variables and environment variables, and functions.
- `6-create_local_variable` - Creates a new local variable.
- `7-create_global_variable` - Creates a new global variable.
- `8-true_knowledge` - Prints the result of the addition of 128 with the value stored in the environment variable `TRUEKNOWLEDGE`.
- `9-divide_and_rule` - Prints the result of `POWER` divided by `DIVIDE`.
- `10-love_exponent_breath` - Displays the result of `BREATH` to the power of `LOVE`.
- `11-binary_to_decimal` - Converts a number from base 2 to base 10.
- `12-combinations` - Prints all possible combinations of two letters, except `oo`.
- `13-print_float` - Prints a number with two decimal places.

#### Usage Examples

#```bash
# To create an alias named `ls`:
./0-alias

# To print the current user in a custom greeting:
./1-hello_you

# To add a custom directory to your PATH:
./2-path

# To display the current number of directories in the PATH:
./3-paths

## Collaborators
Mico Bledsoe - LinkedIn(www.linkedin.com/in/micobledsoe)

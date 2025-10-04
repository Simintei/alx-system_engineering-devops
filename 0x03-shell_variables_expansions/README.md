# 0x03. Shell, init files, variables and expansions

## Learning Objectives
By the end of this project, you should be able to explain to anyone, without the help of Google:

- What happens when you type `$ ls -l *.txt` in the shell
- What are shell initialization files, and how to set, unset, and use variables
- The difference between local and global variables
- What a reserved variable is
- How to create, update, and delete shell variables
- What command substitution is, and how to use it
- How to perform arithmetic operations in the shell
- How to create an alias

## Project Structure
This project contains shell scripts that demonstrate usage of:
- Aliases
- Shell variables
- Expansions
- Shell arithmetic

Each file is a script that can be executed in a shell environment.  
All scripts start with `#!/bin/bash`.

## Example
Script `0-alias` creates an alias named `ls` with the value `rm *`.

```bash
$ ls
0-alias  file1  file2
$ source ./0-alias
$ ls
# (this removes all files in the current directory)

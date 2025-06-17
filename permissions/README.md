shell permissions

This directory contains bash scripts to maipulate shell permissions


### `0-iam_betty`
Switches the current user to the user `betty`.

### `1-who_am_i`
Prints the username of the current user using the `whoami` command.

### `2-groups`
Prints all the groups the current user belongs to using the `groups` command.

### `3-new_owner`
Changes the owner of the file `hello` to the user `betty` using the `chown` command.

### `4-empty`
Creates an empty file called `hello` using `touch`.

### `5-execute`
Adds execute permission to the owner of the file `hello` using `chmod u+x`.


## Requirements

- All scripts are written in Bash
- First line of each script: `#!/bin/bash`
- Each script is exactly 2 lines
- Files end with a new line
- No use of backticks, `&&`, `||`, or `;`
- All scripts are executable
- Scripts from task 3 and above must be created in the sandbox for grading

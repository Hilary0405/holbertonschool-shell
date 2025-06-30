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

### `6-multiple_permission`
Adds execute permission to the owner and the group owner and read permission to other users, to the file 'hello' using chmod command.

### `7-everybody`
adds execution permission to the owner, the group owner and the other users to the file 'hello' using command chmod.

### `8-James_Bond`
set the permissions to the file hello as user and group no permissions and other all the permissions using command chmod 007

### `9-John_Doe`
Write a script that sets the mode of the file hello to this: -rwxr-x-wx using command chmod 753 

### '10-Look in the mirror'
This sets the mode of the file hello the same as olleh's mode.

### '11-Directories'
This adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. without changin the files.

### '12-More dircetories'
This programm create a script that creates a directory called my_dir with permissions 751 in the working directory.

### '13-Change group'
This script change the group owner to school for file hello. started by creating a group named school using sudo goupadd command.'

### '14-Owner and group'
This script change the owner and group owner of all the files from 'root root' to 'vincent staff'

### '15-Symbolic link'
This script change the user and grp user of a symbolic link 

### '16-If only'
This script change the owner of a file only if the file user name iis guillaume.


## Requirements

- All scripts are written in Bash
- First line of each script: `#!/bin/bash`
- Each script is exactly 2 lines
- Files end with a new line
- No use of backticks, `&&`, `||`, or `;`
- All scripts are executable
- Scripts from task 3 and above must be created in the sandbox for grading

# Shell, permissions

This directory contains shell scripts for the Holberton School Shell permissions project.

| Script | Description |
|---|---|
| `0-iam_betty` | Switches the current user to `betty` |
| `1-who_am_i` | Prints the effective username of the current user |
| `2-groups` | Prints all the groups the current user is part of |
| `3-new_owner` | Changes the owner of the file `hello` to `betty` |
| `4-empty` | Creates an empty file called `hello` |
| `5-execute` | Adds execute permission for the owner of `hello` |
| `6-multiple_permissions` | Adds execute permission for owner and group, and read permission for others, on `hello` |
| `7-everybody` | Adds execute permission for everyone on `hello` |
| `8-James_Bond` | Sets the mode of `hello` to `007` |
| `9-John_Doe` | Sets the mode of `hello` to `-rwxr-x-wx` (`753`) |
| `10-mirror_permissions` | Sets the mode of `hello` to match the mode of `olleh` |
| `11-directories_permissions` | Adds execute permission for everyone on all subdirectories of the current directory |
| `12-directory_permissions` | Creates the directory `my_dir` with permissions `751` |
| `13-change_group` | Changes the group of `hello` to `school` |
| `14-change_owner_and_group` | Changes the owner to `vincent` and the group to `staff` for all files and directories in the current directory |
| `15-symbolic_link_permissions` | Changes the owner and group of the symbolic link `_hello` to `vincent` and `staff` |
| `16-if_only` | Changes the owner of `hello` to `vincent` only if it is owned by `guillaume` |

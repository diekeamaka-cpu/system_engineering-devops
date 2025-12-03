#This repository contains Bash scripts designed to practice Linux file and directory permissions.

## Scripts

### 0. My Name Is Betty (0-iam_betty)
Switches the current user to "betty".

### 1. Who Am I (1-who_am_i)
Prints the effective username of the current user.

### 2. Groups (2-groups)
Displays all groups to which the current user belongs.

### 3. New Owner (3-new_owner)
Changes the owner of the file `hello` to "betty".

### 4. Empty! (4-empty)
Creates an empty file named `hello`.

### 5. Execute (5-execute)
Grants execute permission to the owner of the file `hello`.

### 6. James Bond (6-James_Bond)
Sets the permissions of `hello` so that the owner and group have no permissions, and others have all permissions.

### 7. John Doe (7-John_Doe)
Sets the permissions of `hello` to `rwx r-x -wx` (owner, group, others).

### 8. Directories (8-James_Bond)
Adds execute permission to all subdirectories.

### 9. More Directories (9-directory_permissions)
Creates a directory named `my_dir` with permissions set to `751`.

### 10. Change Group (13-change_group)
Changes the group of the file `hello` to "school".

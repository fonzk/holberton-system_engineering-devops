# shell permissions

This project have a lot of script i am explain what each script is doing


### scripts explain

every scripts is explain here:

- [**0-iam_betty script** ](./0-iam_betty) :This script that changes your user ID to ```betty```.

- [**1-who_am_i script** ](./1-who_am_i) :This script prints the effective userid of the current user.

- [**2-groups script** ](./2-groups) :This script prints all the groups the current user is part of.


- [**3-new_owner script** ](./3-new_owner) :This script changes the owner of the file ```hello``` to the user ```betty```.

- [**4-empty script** ](./4-empty) :This script creates an empty file called ```hello```.

- [**5-execute script** ](./5-execute) :This script  adds execute permission to the owner of the file ```hello```.

- [**6-multiple_permissions script** ](./6-multiple_permissions) :This script  adds execute permission to the owner and the group owner, and read permission to other users, to the file ```hello```.

- [**7-everybody script** ](./7-everybody) :This script  adds execution permission to the owner, the group owner and the other users, to the file ```hello```.

- [**8-James_Bond script** ](./8-James_Bond) :This script sets the permission to the file ```hello``` as follows:

    - **Owner**: no permission at all
    - **Group**: no permission at all
    - **Other users**: all the permissions
    
    9-John_Doe
 - [**9-John_Doe script** ](./9-John_Doe) :This script sets the mode of the file ```hello``` to this:
        - ```-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello```

- [**10-mirror_permissions script** ](./10-mirror_permissions) :This script sets the mode of the file ```hello``` the same as ```olleh```’s mode.

- [**11-directories_permissions script** ](./11-directories_permissions) :This script adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

12-directory_permissions
- [**12-directory_permissions script** ](./12-directory_permissions) :This script creates a directory called ```dir_holberton``` with permissions 751 in the working directory.

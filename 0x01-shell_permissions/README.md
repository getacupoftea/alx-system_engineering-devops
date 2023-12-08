This is my readme file for the shell permissions task. Below are the scripts and description.

0. A script that switches the current user to the user betty

"#!/bin/bash"
"su betty"

1. A script that prints the effective username of the current user

"#!/bin/bash"
"whoami"

2. A script that prints all the groups the current user is part of

"#!/bin/bash"
"groups"

3. A script that changes ownership of the file "hello" to the current user "betty"

"#!/bin/bash"
"chown betty hello"

4. A script that creates an empty file called hello

"#!/bin/bash"
"touch hello"

5. A script that adds execute permission to the owner of the file hello

"#!/bin/bash"
"chmod u+x hello"

6. A script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello

"#!/bin/bash"
"chmod ug+x,o+r hello"

7. A script that that adds execution permission to the owner, the group owner and the other users, to the file hello

"#!/bin/bash"
"chmod ugo+x hello"

8. A script that sets the permission to the file "hello" as follows:
Owner: no permission at all
Group: no permission at all
Other users: all the permissions

"#!/bin/bash"
"chmod 007 hello"

9. A script that  that sets the mode of the file hello to -rwxr-x-wx

"#!/bin/bash"
"chmod 753 hello"

10. A script that sets the mode of the file hello the same as olleh’s mode
"#!/bin/bash"
"chmod --reference=olleh hello"

11. A script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.

"#!/bin/bash
"chmod -R +X. 

12. A script that creates a directory called (my_dir) with permissions 751 in the working directory

"#!/bin/bash"
"mkdir -m 751 my_dir"

13. A script that changes the group owner to school for the file hello

"#!/bin/bash"
"

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

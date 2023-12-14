0. A script that prints “Hello, World”, followed by a new line to the standard output:

#!/bin/bash
echo Hello, World

1. A script that displays a confused smiley "(Ôo)':

#!/bin/bash
echo \"\(\Ôo\)\'

2. A script that displays the content of the /etc/passwd file:

#!/bin/bash
cat /etc/passwd

3. A script that displays the contents of /etc/passwd and /etc/hosts:

#!/bin/bash
cat /etc/passwd /etc/hosts

4. A script that displays the  last 10 lines of /etc/passwd:

#!/bin/bash
tail /etc/passwd

5. A script that display the first 10 lines of /etc/passwd:

#!/bin/bash
head /etc/passwd

6. A script that displays the third line of the file iacta with the file in the working directory:

#!/bin/bash
head -3 iacta | tail -1

8. A script a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it:

#!/bin/bash
ls -la > ls_cwd_content

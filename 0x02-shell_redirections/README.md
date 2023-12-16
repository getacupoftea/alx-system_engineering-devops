0. A script that prints “Hello, World”, followed by a new line to the standard output:

"#!/bin/bash"
"echo Hello, World"

1. A script that displays a confused smiley "(Ôo)':

"#!/bin/bash"
"echo \"\(\Ôo\)\'"

2. A script that displays the content of the /etc/passwd file:

"#!/bin/bash"
"cat /etc/passwd"

3. A script that displays the contents of /etc/passwd and /etc/hosts:

"#!/bin/bash"
"cat /etc/passwd /etc/hosts"

4. A script that displays the  last 10 lines of /etc/passwd:

"#!/bin/bash"
"tail /etc/passwd"

5. A script that display the first 10 lines of /etc/passwd:

"#!/bin/bash"
"head /etc/passwd"

6. A script that displays the third line of the file iacta with the file in the working directory:

"#!/bin/bash"
"head -3 iacta | tail -1"

7. A shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line:

"#!/bin/bash"
"echo "Best School" > "\*\\\'\"Best School\"\'\\\*$\?\*\*\*\*\*:)"

8. A script a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it:

"#!/bin/bash"
"ls -la > ls_cwd_content"

9. A script that duplicates the last line of the file iacta:

"#!/bin/bash"
"tail -1 < iacta >> iacta"

10. A script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders:

"#!/bin/bash"
"find . -name '*.js' -type f -delete"

11. A script that counts the number of directories and sub-directories in the current directory:

The current and parent directories should not be taken into account
Hidden directories should be counted

"#!/bin/bash"
"find ./* -type d -print | wc -l"

12. A script that displays the 10 newest files in the current directory:

One file per line
Sorted from the newest to the oldest

"#!/bin/bash"
"ls -t | head"

13. A script that takes a list of words as input and prints only words that appear exactly once:

Input format: One line, one word
Output format: One line, one word
Words should be sorted

"#!/bin/bash"
"sort | uniq -u"

14. A script that display lines containing the pattern “root” from the file /etc/passwd:

"#!/bin/bash"
"grep "root" /etc/passwd"

15. A script that display the number of lines that contain the pattern “bin” in the file /etc/passwd:

"#!/bin/bash"
"grep bin /etc/passwd | wc -l"

16. A script that display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd:

"#!/bin/bash"
"grep -A 3 root /etc/passwd"

17. A script that display all the lines in the file /etc/passwd that do not contain the pattern “bin”:

"#!/bin/bash"
"

18. A script that display all lines of the file /etc/ssh/sshd_config starting with a letter, including capital letters:

"#!/bin/bash"
"grep -i ^[a-z] /etc/ssh/sshd_config"

19. A script that replace all characters A and c from input to Z and e respectively:

"#!/bin/bash"
"

20. A script that removes all letters c and C from input:

"#!/bin/bash"
"

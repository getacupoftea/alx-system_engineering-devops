Shell basics involve interacting with a command-line interface, typically using a shell program like Bash. Here's a brief explanation:

Shell: A shell is a command-line interpreter that allows users to interact with the operating system by typing commands. Bash (Bourne Again SHell) is a popular shell used on Unix-based systems.

Command Prompt: When you open a terminal or command prompt, you're presented with a prompt where you can type commands. The shell reads these commands and executes them.

Commands: Commands are instructions given to the shell to perform specific tasks. They can be simple, like listing files (ls), or more complex, involving pipes, redirects, and other features.

Scripts: Shell scripts are files containing a sequence of shell commands. They allow you to automate tasks by executing a series of commands in a specific order. The #!/bin/bash at the beginning of a script is called a shebang or hashbang. It indicates the path to the shell interpreter (in this case, Bash) that should be used to execute the script.

0. To write a script that prints the absolute path name of the current working directory, the first line of the script should include the "#!/bin/bash", followed  by the command which is : "pwd". Leave a new line after this script.

1. To display the contents list of your current directory: ls, but the first line should be the "#!/bin/bash"; like this:

"#!/bin/bash"
"ls"

2. A script that changes the working directory to the user’s home directory:

"#!/bin/bash"
 "cd ~"

3. A script that print contents in current directory in a long format : 

"#!/bin/bash"
"ls -l"

4. A script that prints contents in current directory including hidden files and in long format : 

"#!/bin/bash"
"ls -la"

5. A script that displays the contents of the current directory in; long format, with user and group IDs displayed numerically, and hidden files starting with (.)

"#!/bin/bash
ls -la --numeric-uid-gid

6. A script that creates a directory named (my_first_directory) in the /tmp/ directory:

"#!/bin/bash"
"mkdir /tmp/my_first_directory"

7. A script that moves the file betty from /tmp/ to /tmp/my_first_directory
"#!/bin/bash"
"mv /tmp/betty /tmp/my_first_directory/

8. A script that deletes the file "betty" in the /tmp/my_first_directory"

"#!/bin/bash"
"rm /tmp/my_first_directory/betty"

9. A script that deletes the directory my_first_directory that is in the /tmp directory
"#!/bin/bash"
rm -r /tmp/my_first_directory

10. A script that changes the working directory to the previous one: 
"#!/bin/bash"
"cd -"

11. A scrript thatthat lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format:

"#!/bin/bash"
"ls -la . .. /boot"

12. A script that prints the type of the file named iamafile in the /tmp directory
"#!/bin/bash"
"file /tmp/iamafile"

13. A script that creates a symbolic link to /bin/ls, named __ls__ in the current working directory

"#!/bin/bash"
"ln -s /bin/ls __ls__(to achieve this symbol,hold the shift key,and the minus sign twice)

14. A script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory

"#!/bin/bash"
"cp -un *.html ../"

15. A script that moves all files beginning with an uppercase letter to the directory /tmp/u

"#!/bin/bash"
"mv [[:upper:]]* /tmp/u"

16. A script that deletes all files that end with character (~) in the current working directory
"#!/bin/bash"
"rm *~"

17. A script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory

"#!/bin/bash
"mkdir -p welcome/to/school"

18. A script that that lists all the files and directories of the current directory, separated by commas (,);
Directory names should end with a slash (/)
Files and directories starting with a dot (.) should be listed
The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
Only digits and letters are used to sort; Digits should come first
You can assume that all the files we will test with will have at least one letter or one digit
The listing should end with a new line

"#!/bin/bash"
"ls -la -m -p"

19. Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.

"#!/bin/bash"
"

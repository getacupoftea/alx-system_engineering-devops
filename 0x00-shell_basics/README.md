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

10. A script that changes the working directory to the previous one: 
"#!/bin/bash"
"cd -"



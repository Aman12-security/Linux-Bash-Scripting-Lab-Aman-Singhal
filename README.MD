# Experiment-11

Title: Study of Linux Shells and Implementation of a Basic Bash Script Using Variables  
Aim:To study different types of shells available in Linux, understand their features and characteristics, and to write and execute a simple Bash shell script using variables.

Objective:
- To understand the concept of different shells in Linux.
- To explore the features of Bash and its scripting capabilities.
- To write and execute a basic Bash script using variables.

Theory:

Shell in Linux:
A shell is a command-line interpreter that processes user commands and communicates with the kernel. It allows users to execute commands, manage files, and write scripts for automation.

Types of Shells:
Common shells available in Linux include:
- sh– Original Bourne Shell
- bash– Bourne Again Shell
- ksh– Korn Shell
- csh– C Shell
- zsh– Z Shell

Bash Shell:
Bash is an enhanced version of sh that supports:
- Command history
- Job control
- Scripting with variables and control structures

Shell Scripts:
A shell script is a file containing a sequence of commands that can be executed as a program.

Step-by-step Procedure:

A. Identifying Different Shells:
1. Log in to the Linux virtual machine and open the Terminal.
2. List available shells using:
     cat /etc/shells
3. Check the current shell using:
       echo $SHELL

B. Switching Between Shells:
4. Switch to Bourne Shell using:
      sh
5. Return to Bash using:
      exit

C. Writing a Simple Bash Script:
6. Create a new script file using:
       nano simple.sh
   write a simple script like:
      • #!/bin/bash 
      • echo "Welcome to Linux Shell Scripting" 
      • name="Student"  
      • echo "Hello $name" 
7. Make the script executable using:
      chmod +x simple.sh
8. Execute the script using:
      ./simple.sh

Configuration Commands:
- cat /etc/shells - Lists all available shells on the system.
- echo $SHELL - Displays the current shell in use.
- sh - Starts the Bourne shell.
- exit - Exits the current shell and returns to the previous one.
- nano simple.sh - Opens the Nano text editor to create a new script.
- chmod +x simple.sh - Makes the script file executable.
- ./simple.sh - Executes the script.

Observations / Results:
Each file in Linux has a unique inode containing metadata such as file type, permissions, owner, size, and timestamps.
I/O redirection stores or reads data from files effectively.
Pipes allow chaining commands for efficient data processing.
Process control commands help monitor, suspend, resume, and terminate processes.


Conclusion:
This experiment provided an understanding of different types of shells in Linux, including how to switch between shells, and how to write, execute, and manage a basic Bash shell script.

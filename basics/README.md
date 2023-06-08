SHELL, BASICS


In this module we learnt about shell, basic concepts. 
The learning objetives are:

- GENERAL

What does RTFM mean?
What is a Shebang

- WHAT IS THE SHELL?

What is the shell
What is the difference between a terminal and a shell
What is the shell prompt
How to use the history (the basics)

- NAVIGATION

What do the commands or built-ins cd, pwd, ls do
How to navigate the filesystem
What are the . and .. directories
What is the working directory, how to print it and how to change it
What is the root directory
What is the home directory, and how to go there
What is the difference between the root directory and the home directory of the user root
What are the characteristics of hidden files and how to list them
What does the command cd - do

- LOOKING AROUND

What do the commands ls, less, file do
How do you use options and arguments with commands
Understand the ls long format and how to display it
A Guided Tour
What does the ln command do
What do you find in the most common/important directories
What is a symbolic link
What is a hard link
What is the difference between a hard link and a symbolic link

- MANIPULATING FILES

What do the commands cp, mv, rm, mkdir do
What are wildcards and how do they work
How to use wildcards

- WORKING WITH COMMANDS

What do type, which, help, man commands do
What are the different kinds of commands
What is an alias
When do you use the command help instead of man

- READING MAN PAGES

How to read a man page
What are man page sections
What are the section numbers for User commands, System calls and Library functions

- KEYBOARD SHORTCUTS FOR BASH

Common shortcuts for Bash

- LTS

What does LTS mean? 

RESOURCES:

http://linuxcommand.org/lc3_lts0010.php
http://linuxcommand.org/lc3_lts0020.php
http://linuxcommand.org/lc3_lts0030.php
http://linuxcommand.org/lc3_lts0040.php
http://linuxcommand.org/lc3_lts0050.php
http://linuxcommand.org/lc3_lts0060.php
http://linuxcommand.org/lc3_man_pages/man1.html
https://www.howtogeek.com/181/keyboard-shortcuts-for-bash-command-shell-for-ubuntu-debian-suse-redhat-linux-etc/
https://wiki.ubuntu.com/LTS
https://en.wikipedia.org/wiki/Shebang_%28Unix%29

TASKS:

0. Where am I?
- create a script that displays the working directory
1. What’s in there?
- create a script that displays the contents of the directory
2. There is no place like home
- create a script that returns you to the root directory
3. The long format
- create a script that displays a list in long format
4. Hidden files
- create a script that displays the hidden files in long format
5. I love numbers
- Display current directory contents.
 	Long format
	with user and group IDs displayed numerically
	And hidden files (starting with .)
6. Welcome
- Create a script that creates a directory named my_first_directory in the /tmp/ directory
7. Betty in my first directory
- Move the file betty from /tmp/ to /tmp/my_first_directory
8. Bye bye Betty
- Delete the file betty.
9. Bye bye My first directory
- Delete the directory my_first_directory that is in the /tmp directory.
10. Back to the future
- Write a script that changes the working directory to the previous one.
11. Lists
- Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
12. File type
- Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
13. We are symbols, and inhabit symbols
- Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
14. Copy HTML files
- Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

You can consider that all HTML files have the extension .html
15. Let’s move
- Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.

You can assume that the directory /tmp/u will exist when we will run your script
16. Clean Emacs
- Create a script that deletes all files in the current working directory that end with the character ~.
17. Tree
- Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.

You are only allowed to use two spaces (and lines) in your script, not more.

# BASIC LINUX COMMANDS 

#### Why Do We Need Linux Commands?
When using Linux, you can perform tasks in two ways:
1. Graphical User Interface (GUI) – Clicking buttons, similar to Windows or macOS.
2. Command Line Interface (CLI) – Typing commands to get things done faster.
Using commands in the Terminal, can be much quicker and more powerful than clicking around with a mouse.



* "echo" is a command that displays the text or message in the terminal. 
* "pwd" - print working directory ---> tells the path of the folder(tells if the terminal is a folder or directory). 
> Folder and directory are the same things
* "cd <folder_name>" - used to get into a folder. 
* "cd .." - will take back to folder level. The 2 dots here will take us back to one level 
* "more <filename>" -- tells us what is in the file 
* "clear" -- command used to clear the terminal 
* "ls <flag>" - used to add a flag to a command to use it in different ways. (<flag> (name of the folder you are ciurrently in ))
* "ls -l <flag>" - list the contents of (<flag> (name of the folder you are ciurrently in )) in long list format. 
* "cd ../.." - go back two folders. Each set of dots represents another folder level.
* "mkdir <folder_name>" -- to make a new folder where mkdr stands for make directory 
* "touch <filename> " -- to create a new file(empty file)
* "ls --help" -- Display the "help" menu for the ls command.
* "ls --all or ls --a" -- to list all the contents of the folder 
> For the image files that we created in the folder will show up in pink color
* "cp <file> <destination>" -- for copying one file to the destination folder or file. 
* "rm <filename>" remove the filename, where rm stands for remove
* "mv <filename> <new_filename>" -- used to rename or move the file. where mv stands for move
* "find" -- to find things or view a file tree in a folder
* "find <folder_name>" to display the tree of that folder 
* "find -name <filename>" -- Use find with the -name flag to search for the file name. Can follow the same to find the name of the folder as well.
* "find ." -- use this to first view the file structure of your current directory
* "find . -type d -name "directory_name" " --- If you want to restrict the search to only directories, you can use the -type d
* "mkdir <folder_name>/<new_folder_name>" --- used a new director from the existing directory. 
* "rmdir" stands for "remove directory" --- rmdir directory_name
* "uname -a" tells about the version of the system
* "cat" this shows the content of a file
* "less <file_name.extension>" to reada big file page by page
* "ps" this is used to see a list of running programs
* "wget <file_name.extension>" this downloads a file from a website
* "whoami" is used to check the username
* "sort <file_name.extension>" sorts the contents of a file in order
* "cal" displays a simple calendar
* "df" used to check the disk space
* "df -h" shows the disk usage in human-readable format
* "man command-name" shows a detailed manual of any command. 

# The Command Line

### The Command Line
- A command line, or terminal, is a text based interface to the system. Users are able to enter commands by typing them on the keyboard and feedback will be given to the users similarly as text.
It usually presents the user with a prompt. As one type, it will be displayed after the prompt. Most of the time the user will be issuing commands.

### Basic Navigation
- Moving around in the system, important concepts are Relative vs Absolute Paths. Relative Path is relative to where we currently are in the system and Absolute Path is relation to the root of the file system.
- Couple of key command lines are: 
- `pwd` - Print Working Directory - ie. Where are we currently.
- `ls` - List the contents of a directory.
- `cd` - Change Directories - ie. move to another directory.

### More About Files 
- Interesting characteristics of files and directories in a Linux enviorment are:
- 1. Everything including directories are files under Linux. 
- 2. Linux is extensionless.
- 3. Linux is case sensitive. 

### Manual Pages 
- Manual pages allows the users to look things up instead of having to memorize it. 
- Couple of key terms include:
- `man` <command> - Look up the manual page for a particular command.
- `man -k` -  <search term> - Do a keyword search for all manual pages containing the given search term.
`/<term>`- Within a manual page, perform a search for 'term'.
- `n` - After performing a search within a manual page, select the next found item.

### File Manipulation 
  How to make, remove, rename, copy and move files and directories.
-  File manipulation has consequences and there is no undoing your actions.
- The Linux command line does not have an undo feature. Perform destructive actions carefully.
- Most commands have many useful command line options. Make sure you skim the man page for new commands so you are familiar with what they can do and what is available.
  
 ### Cheat Sheet 
- A quick reference for the main points covered in this tutorial.
- Couple of important notes in the cheat sheet include:
`du -sh ./*` - Find the size of every directory in your current directory.
`df -h` - Display how much disk space is used and also free.
`basename -s .jpg -a *.jpg | xargs -n1 -i cp {}.jpg {}_original.jpg` - Make a copy of every jpg image file in the current directory and rename adding _original.
`find /home -mtime -1` - Find all files in the given directory (and subdirectories) which have been modified in the last 24 hours.
`shutdown -h now` - Shutdown the system. (Replace -h with -r for reboot.)

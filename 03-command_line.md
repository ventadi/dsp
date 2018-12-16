# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path : 
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

* show current working directory path : pwd
* creating a directory : mkdir temp
* deleting a directory : rmdir temp
* creating a file using `touch` command: touch test.file
* deleting a file: rm test.file
* renaming a file: mv test.file test.bak
* listing hidden files: ls -al
* copying a file from one directory to another: mv ./dir1/filename ./dir2
* List of commands from history : history
* List of the name of the person who is logged in: whoami
---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  : list of files in the directory
`ls -a`  : list all files, included hidden
`ls -l`  : list of files in long form
`ls -lh`  : displays files in Kilobytes and Gigabytes
`ls -lah`  : combination of all of the above three
`ls -t`  :  Sort by time modified (most recently modified first)
`ls -Glp`: Enable colorized output. long output and Write a slash (`/') after each filename if that file is a directory.
  

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> >
-R	Displays subdirectories as well.
-t	Displays newest files first. (based on timestamp)
-l	Displays the long format listing.
-a	Displays all files.
-f Output is not sorted. This option turns on the -a option.


---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

xargs is a command on Unix and most Unix-like operating systems used to build and execute commands from standard input. It converts input from standard input into arguments to a command.

echo 'dir1 dir2 dir3' | xargs mkdir

The above command creates three directories.


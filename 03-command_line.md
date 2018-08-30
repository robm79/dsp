# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> > - show current working directory path = pwd
> > - creating a directory = mkdir
> > - deleting a directory = rm -r OR rmdir
> > - creating a file using `touch` command = touch abc.txt
> > - deleting a file = rm abc.txt
> > - renaming a file = rename a.txt b.txt
> > - listing hidden files = ls -a
> > - copying a file from one directory to another cp a.txt location/
> > - list files and details = ls -l
> > - chmod = change access permissions

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> > List files
> >
> > List all files, including hidden
> >
> > List files in long format
> >
> > list files in long format with sizes in human readable format
> >
> > list all files, including hidden, in long format with sizes in human readable format
> >
> > list files in order of most recently modified
> >
> > list files with file type added, color coded, and nature of file appended

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > | Option | Description                                                  |
> > | ------ | ------------------------------------------------------------ |
> > | -g     | Displays the long format listing, but exclude the owner name. |
> > | -o     | Displays the long format listing, but excludes group name.   |
> > | -p     | Displays directories with **/**                              |
> > | -R     | Displays subdirectories as well.                             |
> > | -t     | Displays newest files first. (based on timestamp)            |

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > Xargs is a command line utility for building an execution pipeline from standard input.
> >
> > In other words, it allows functions that cannot normally use standard input to do so.
> >
> > useful examples: using rm on all files that contain a specific string in the filename, or within a specific timeframe
> >
> > find . -mtime +14  | xargs rm (deletes all files older than 2 weeks in current folder)

 


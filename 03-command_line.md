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

> > REPLACE THIS TEXT WITH YOUR RESPONSE

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

> - `ls` lists the contents of the present working directory.
> -  The option `-a` ensures that all contents are revealed when executing `ls`, including hidden files that begin with `.` 
> - The option `-l` creates a long-form version of `ls`
> - `-lh`: Options can be grouped. The option `-lh` calls the long-form option, as well as the option `-h`, which means human-readable. Human readable here means that numbers are printed with not too many digits, replaced instead by k, M, G, etc. 
> - `-lah`: Same as above, but includes hidden files as well.
> - `-t`: sorted by modification time.
> - `-Glp`: `p` adds file type incidator, i.e. it adds `/` to end of folder names. `G` enables colorized output (making the folder names a different color). 

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> - `-S` sorts by size
> - `-R` recursively goes through the directory structure, revealing all the folders' and subfolders' contents,
> - `-1` prints directory contents with one entry per line,  
> - `-r` reverses order
> - `-x` inverts sorting order for tabular display (multicolumn output is sorted across, rather than down the columns).
---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > REPLACE THIS TEXT WITH YOUR RESPONSE

 


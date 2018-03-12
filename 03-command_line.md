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

> > - `pwd`: shows current directory path
> > - `mkdir` [dirname]: creates directory. Add option `-p` to make multiple, nested directories.
> > - `cd` and `cd -`: change directory. `cd -` allows you to toggle between the last two current directories.
> > - `rmdir` or `rm -d|-r` `dirname`: Delete directories. `rmdir` is the safe choice to stay out of the trouble `rm` can cause. However, `rmdir` is less powerful (it will get stuck if a directory folder contains files). `rm` on the other hand, especially if deployed recursively (`-r`), will remove folders as well as files. 
> > - `touch [filename]`: creates an empty file. 
> > - `rm [filename]`: removes file.
> > - `mv [file] [newfilename]`: renames file. 
> > - `ls -a`: lists hidden files 
> > - `cp [file][copydirectory]`: copies file to copydirectory.
> > - `echo`: the print statement 
> > - `man [utility]`: the help menu for utility.
> > - `apropos`: find what `man` page is appropriate.
> > - `find`: find files
> > - `pushd [dir]` and `popd`: push and pop directories to be able to switch back and forth between different directory locations. `pushd` must be used with a directory as argument. To push the current directory, simply reference like so: `pushd .`
> > - `dirs`: shows the directory stack built by pushd and popd.
> > - `grep`: find things inside files.
> > - `env`: look at your environment.
> > - `export`: export/set a new environment variable.
> > - `exit`: exit the shell
> > - `sudo`: 'super user do'--become super user root **danger**.
> > - `xargs`: execute arguments.
> > - `cat`: print the whole file.
> > - `less`: page through a file.
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

 


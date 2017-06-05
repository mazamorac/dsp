# Learn command line

Please follow and complete the free online [Command Line Crash Course
tutorial](https://web.archive.org/web/20160708171659/http://cli.learncodethehardway.org/book/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. Each "chapter" focuses on a command. Type the commands you see in the _Do This_ section, and read the _You Learned This_ section. Move on to the next chapter. You should be able to go through these in a couple of hours.

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

> > 
pwd
mkdir <dir>
rm -rf <dir>
touch <file>
rm <file>
mv <oldname> <newname>
ls -a
cp -p <source> <destination>

usual commands:
alias lr="ls -lrt"


---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  list files, simple
`ls -a`  list all files, simple
`ls -l`  list files, with permissions, dates and sizes
`ls -lh`  list files -l, in human-readable metrics
`ls -lah` list all as -lh
`ls -t`  list all, sorting by modtime
`ls -Glp`  no group names, long, trailing slash on dirs

> > (SIL)

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > ls -lrt (I always alias it to lr)
-F classify
-L deref symlinks
-R recursive
-S sort by size
-X sort by extension

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > takes STDIN words and forks another program repeatedly, passing input as command line parms.
find -type f -name '*.py' | xargs head -10


 


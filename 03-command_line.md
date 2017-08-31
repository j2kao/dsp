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

* pwd
* mkdir
* rmdir
* touch readme.txt
* rm readme.txt
* mv readme.txt readme2.txt
* ls a
* cp ./a/readme.txt ./b/readme.txt

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

* list files
* list files including hidden files
* list files with long format (permissions)
* list files with long format, file size formatted
* list files including hidden files with long format, file size formatted
* list files by time
* list files with long format, colorized output, slash for directory

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

-L	Displays the file or directory referenced by a symbolic link.
-r	Displays files in reverse order.
-R	Displays subdirectories as well.
-t	Displays newest files first. (based on timestamp)
-u	Displays files by the file access time.

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

xargs lets you take inputs and applies them to commands

e.g.,

```console
find . -maxdepth 1 -name "*.txt" | xargs grep "text_to_search"
```

 


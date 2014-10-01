bash-intro
==========

Introduction to Bash in 60 seconds or less

```
/* 
So sixty second crash course in the command line, some very basic commands with a basic example right after (the dollar sign represent your prompt, and everything after it on that line is the command typed it [i.e. don't copy the dollar sign if you're copying and pasting]):
*/  
```
```
pwd     <-- Print Working Directory (the "you are here" of unix land)
mkdir    <--make director/folder
cd   <-- change directory (this is how you 'move' around the file system
ls   <-- list the current directory i.e. show me what is in the current folder
man  <-- “manual” gives the manual page for any command i.e. `man ls` will give the manual page for ls
```
```
# This is a comment, lines that start with a hash are comments and
# and are ways for me to explain what is going on for your benefit only 
# comments are  very important in programming languages

# ok from here $ means the prompt
```
```
$ pwd
/home/bob
```
```
$ mkdir git
# there is no output for this command
```
```
$ cd git
# again no output on this command so long as there are no errors
# but let's prove to ourselves that we changed directories with `pwd`
$ pwd
/home/bob/git
```


```
# ok now let's clone that repo!
$ git clone https://github.com/WebHostingCoopTeam/WebHostingCoopTeam.github.io.git
Cloning into 'WebHostingCoopTeam.github.io'...
remote: Counting objects: 331, done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 331 (delta 0), reused 0 (delta 0)
Receiving objects: 100% (331/331), 3.65 MiB | 483.00 KiB/s, done.
Resolving deltas: 100% (43/43), done.
Checking connectivity... done.
```


```
# yay!  we're done, now send me the changes, and when I send them back I'll have more CLI (command line interpreter) fun for you!

// some languages a double slash is the single comment

/*
 this is how you do a multiline
 comment in some languages
 with the slash star - comments - star slash 
*/
```

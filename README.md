# Cli-Intro-to-Git
==========

### Introduction to git on the command line in 60 seconds or less


/* 
Type these commands directly into bash (your terminal, shell, command line interpreter, whatever you want to call it [tested in bash, sh, and zsh *ymmv])
*/  
```
pwd
cd /tmp
pwd
mkdir git
cd git
pwd
git init
echo 'my test' >test1
ls
git status
git add test1
git status
git commit -am 'initial add of test1'
git log
echo 'second test' >>test1
git status
echo 'second test file'>test2
git status
git commit -am 'second test'
git log
```
/*
 Ok so that was git in 60 seconds.  What just went on?  Let me be abit more verbose with an intro of some very basic commands with a basic explanation after the `<--` :
*/
```
pwd      <-- Print Working Directory (the "you are here" of unix land)
mkdir    <-- make directory/folder
cd       <-- change directory (this is how you 'move' around the file system
ls       <-- list the current directory i.e. show me what is in the current folder
man      <-- “manual” gives the manual page for any command i.e. `man ls` will give the manual page for ls
man git  <-- At some point you'll feel confident enough to just pull this page up for reference, not just yet
```
```
# This is a comment, lines that start with a hash are comments and
# and are ways for me to explain what is going on for your benefit only 
# comments are  very important in programming languages

# ok from here $ means the prompt
# and you should type what directly follows that $ into your command prompt
# like learning a new language it's best for you to actually speak (type) the words
# and see the resulting output, it's very satisfying to see your creation take life
# let's see those first commands again with some # comments to explain what's going on

pwd
cd /tmp
pwd
mkdir git
cd git
pwd
git init
echo 'my test' >test1
ls
git status
git add test1
git status
git commit -am 'initial add of test1'
git log
echo 'second test' >>test1
git status
echo 'second test file'>test2
git status
git commit -am 'second test'
git log
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
Appendix A more comment styles:

// some languages a double slash is the single comment

/*
 this is how you do a multiline
 comment in some languages
 with the slash star - comments - star slash 
*/
```

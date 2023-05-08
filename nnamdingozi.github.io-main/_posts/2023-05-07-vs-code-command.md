--
layout: post
title: VS code commands
subtitle: tech academy
categories: Terminal basics
tags: [serverVS code, commands, ]

---

## Open a terminal in VS code

press (ctrl+shift+~)

## Navigation commands

 On the terminals the first symbol that shows the terminal is ready to receive input is the dollar sign

 ## ls
  
  Stands for List, this command lists all the files and directories on the current directory you are in. 
 directory is another name for folders

 ## pwd
 Means print working directory. It outputs the name of the directory you are currently on. ls and pwd shows where you are in the file system
 
 ## cd |

stands for change directory and it takes an arguement.The arguement specifies the directory you want to change into.Eg cd 2015.

## cd..

used to move one directory up. ie the directory above the current working directory.

## cd ||
Used to move across multiple directories with one command. EG cd 2015/jan/memory/blog

## cd../..

Use to move up multiple directories
It means the directory above the directory above that

eg
pwd 
/home/cuser/workspace/blog/2015/jan/memory
cd../..
pwd
/home/cuser/workspace/blog/2015

## ..directory name

Used to move to an adjacent directory
EG
ls
2014 2015 hardware.txt
cd 2015
pwd
 /home/cuser/workspace/blog/2015
 cd ../2014
 pwd
 /home/cuser/workspace/blog/2014

 ## mkdir

Stands for make directory. It takes a directory name as an arguement and creates a new directory in the current working directory. to create a new directory, cd into the directory you want to work it before using the mkdir command

## touch
 
 This command creates a new file inside your working directory. it takes a file name as an arguement and creates an empty file.

 ## Helpful commands

these are key board keys that makes navigation of file system easy
tab  used to autocomplete your command like when typing an existing file or directory

up and down arrows  used to cycle through your previous commands. up arrows take you up through your most recent commands and down arrow will take you back.Helps to review your command history

clear is a command typed to clear your terminal. it doesnt change or undo your previous commands, it just clears them from view.

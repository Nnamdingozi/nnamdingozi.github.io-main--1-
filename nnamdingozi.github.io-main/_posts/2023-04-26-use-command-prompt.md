---
layout: post
title: Assessing server
subtitle: tech academy
categories: Javascript
tags: [server, access, ]
---

## Moving files
To move a file, type in the following command
*mv target destination
where mv is move
destination is where you want to move it to.

## copying files/folders
If you’re trying to copy files around, the easiest way to do this is using the cp command. Use the following script to copy around files.

## copy file command
*cp -r target destination*

In this script, cp represents copying and -r represents doing it recursively. The target is the target folder/file you’re trying to copy, and destination is the target folder you’re trying to copy to

## important notes on copying files
-Let’s say you type in “cp -r home/target/ home/destination/”. If “home” is a folder and “target” is a folder, but “destination” is not a folder in home, then “target” will be copied into home but will be named “destination”.

-Let’s say you type in “cp -r home/target/ home/destination/”. If all of these are valid folder, “target” will be copied as a folder inside of “destination” inside of “home” — you’ll end up with a folder that’s “home/destination/target/”.

-Let’s say you type in “cp -r home/target/ users/”. This will just copy the “target” folder into the “users” folder under the same name (target).

-Use the * character to represent all. For example, to copy all files in a folder that start with the letter a, your target should be “/folder/a*”. To copy all files of a certain extension (say something like .png), your target should be “/folder/*.png”.

-Use the . character to represent the current folder.

-If the file/folder already exists in destination, it WILL BE OVERRIDDEN. So make sure you don’t make this rookie mistake.

## deleting files command
rm -r target

## important notes on deleting files

-will not work if file does not exixst

-Use* to represent all
-use . for current folder
-this cmd deletes files very quickly and when file is deleted, you cant get it back. There is no control z on this one

## Listing files

This cmd is used to view files or folders that are within your a folder. if you are 
trying to list the contents of the folder you’re currently in, leave target blank

*ls target(options)*

where target is the folder whose content you are trying to list

use the following options
-“-F”: adds a character for the type of file (e.g. a “*” for an exectuable script or a “/” for a directory).

-“-f”: stops the computer from sorting the contents. Useful when there are huge numbers of files and it’s not useful to sort the files.

-“-a”: lists all files, including hidden files that would normally be hidden.

“-h”: will let you also get the sizes of the files.

-“-t”: sorts the files by when it was last modified.

## changing directory you are in

use this cmd
*cd target*
-Use the . character to represent the current folder. Doing “cd .” will refresh what the command line says your current directory is (useful if you’ve changed a folder name in the path to your folder).

-Use “../” to represent the enclosing folder. For example, if you’re currently in “home/target/”, then you can do “cd ../” to get to the “home” folder. The “../” is also stackable, so two of them would get you 2 folders back.

## making a new folder

use this cmnd
*mkdir target*

## clearing out cluster

*clear*

## Running scripts

You can use command line to run your script based on codeing language

 ### for java

 *java target*
 *javac target*

 ### for javascript
 visit link [run javascript through terminal](https://stackoverflow.com/questions/8532960/how-do-you-run-javascript-script-through-the-terminal)



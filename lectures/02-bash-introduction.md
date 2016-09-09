---
layout: lecture
title: "Unix and Bash"
---

### Week 2 - Unix and Bash

We are going to work on the [The Unix Shell](http://swcarpentry.github.io/shell-novice/) workshop (by Software Carpentry)

Download the `shell-novice-data.zip` file from [http://swcarpentry.github.io/shell-novice/setup/](http://swcarpentry.github.io/shell-novice/setup/)

1. [Introducing the Shell](http://swcarpentry.github.io/shell-novice/01-intro/)
2. [Navigating Files and Directories](http://swcarpentry.github.io/shell-novice/02-filedir/)
3. [Working with Files and Directories](http://swcarpentry.github.io/shell-novice/03-create/)

-----

- Introduction to Unix
	+ Graphical User Interface (GUI) vs Command-Line Interface (CLI)
	+ Command Line Terminal
	+ Commands structure
	+ Understanding the command-line prompt
	+ Unix `man` command: manual pages

- Filesystem basics
	+ The working directory and the command `pwd`
	+ Listing files and directories with `ls`
	+ Moving around the filesystem with `cd`
	+ Filesystem organization


#### Working with Files and Directories

- Naming files
	+ avoid spaces
- Creating files
	+ using a text editor (vim, nano, emacs, _etc_)
	+ using the `touch` command
	+ through redirection (we'll see this later)
- Unix text editors
	+ Learn how to work with a unix text editor
- Viewing file contents
	+ Before inspecting the contents of a file, check its type with `file`
	+ viewing the whole file with `cat`
	+ viewing the whole file using a paginator with `less`
	+ viewing parts of a file with `head` and `tail`
- Creating directories with `mkdir`
- Moving and renaming files with `mv`
- Copying files and directories with `cp`
- Deleting files `rm`
	+ `rm -r`
	+ `rm -f`
	+ `rm -i`
- Searching for files and directories

- Compressing data
- Compression utilities:
	+ `bzip2` (file extension `.bz2`)
	+ `gzip` (file extension `.gz`) is the GNU Project's compression utility
	+ `zip` (file extension `.zip`) is the Unix version of the PKZIP program for Windows
- Package `gzip`:
	+ `gzip` for compressing files
	+ `gzcat` for displaying the contents of compressed text files
	+ `gunzip` for uncompressing files
- `zip` utility:
	+ `zip` for compressing files
	+ `unzip` for uncompressing files


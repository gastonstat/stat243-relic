---
layout: lecture
title: "Shell basics"
---

<p class="message">
  The typical way of (not) doing things: issues and problems
</p>


### Recap

In any Data Analysis Project (DAP), you'll be working with files:

- data, code, images, docs, etc
- some files are inputs, some files are outputs
- a project is a NETWORK of relationships between files
- although you don't see it, there is a network (connections among files)
- FUNDAMENTAL to know where files are, and manage their pathnames


### Handling files and directories

- How do you handle files and directories?
- Using a GUI (Graphical User Interface)
- Using a CLI (Command Line Interface)
- Advantages and disadvantages of GUIs
- Advantages and disadvantages of CLIs


### Some Shell-related Terminology

Many people use the terms _command line_, _bash_, and _shell_ interchangeably. 
Although they are related terms, they are not synonyms. 

- __Unix-like__ refers to a family of operating systems that 
includes Linux, Android, iOS (iPhone/iPad), and Mac OS X.
- The way that you interact with a Unix-like system is by using the command line.
- __Terminal__ (or terminal emulator) refers to the program that gives us a 
command line (i.e. provides a command line access to Unix). 
The terminal is where you type the commands. 
- The __kernel__ is the core of the operating system in Unix. 
It's what takes care of allocating time and memory to program.
- __Shell__ is the outside of the kernell. The shell is the outer layer of the 
operating system. That's what you see when you open up a Terminal window.
- The shell interacts with the user (think of it as your working environment). 
Every time you execute a command, the shell will send requests to the kernel. 
The kernel will then do its thing and results will then be returned back to the 
shell so that you can interact with them again.
- There are several types of shells. Perhaps the most common one is the __bash__ 
(Bourne Again Shell) shell.

__In summary:__
Bash is a type of shell. All shells require a command line interpreter or 
terminal emulator. That's where the user type commands, which are handled 
by the shell and send to the operating system (based on Unix).


### Some basic bash commands

- `ls`
- `pwd`
- `cd`
- `mkdir`
- `touch`
- `rm`
- `rmdir`
- `cp`
- `mv`


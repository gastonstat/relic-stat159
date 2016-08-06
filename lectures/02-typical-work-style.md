---
layout: lecture
title: "Typical Work Style"
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


### Activity 1

- Form groups of 2 or 3 people, make sure at least one person knows R
- We are going to create a minimal report
- Go to google drive
- Open a google sheet
- Create two variables X and Y (e.g. 10 values)
- Make a summary table of each variable (e.g. min, max, mean, median)
- Make a scatterplot
- Add axis labels
- Add a title
- Color points with your favorite color
- Open a google doc
- Write some content
- Include the summary table
- Include the scatterplot
- Generate a pdf of the document

__Questions__

- How many steps to create the table?
- How many steps to create the chart?
- How many steps to create document in pdf?
- What is going on with this typical way of doing things?


### Activity 2

- Let's add one more row to the data set
- Now redo the analysis (time it!, how much time it took you?)
- How many steps would you require to do the analysis again?
- What if you had to handle this project to someone else? 
Is it clear where to begin, what to do?
- If someone else wanted to redo the report, what would that person need to know?


### Considerations and Inconvenient Issues

- 3 or 6 months from now ...  Would you be able to recreate the report? Yes/No and Why?
- Identify at least 5 factors that can affect recreating the report
- Problems around reproducing your own work:
	- Ignorance
	- You don't document what you do
	- You may or may not track changes
	- You may never stop thinking about organization
	- Nobody teaches you these things
	- No one else cares enough about it
	- You may feel copy-paste is tedious and cumbersome (but that's ok, right?)
	- Almost never think about sharing your stuff
	- Things that never crossed your mind
	- ...
	- As you're working on a project, your memory is fresh
	- But then (6 months later) you try to redo your analysis
	- Will you be able to do it reliably?
	- Will you be able to do it in a short period of time?


### Activity 3

- Let's consider an alternative way of doing things
- We'll use R and an `.Rmd` file
- Create the data set
- Open an `.Rmd` file
- Write some content
- Add a chunk to compute the summary stats
- Add a chunk to plot the scatter diagram
- Knit the document
- ...
- Now add one more row to the data
- Redo the analysis and time it.
- What do you think of this approach?

What happens with this alternative way of doing things?


### Summary

- Understand limitations of WYSIWYG tools
- Advantages of using WYSIWYM tools
- Learn how to use a text editor (vim, emacs, nano, etc)
- Let the computer do the tedious, laborious, repetitive work
- Write documentation for all your projects
- Recognize the advantage of dynamic documents
- Collaboration: you are your main collaborator!

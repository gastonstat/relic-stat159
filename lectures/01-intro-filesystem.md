---
layout: lecture
title: "Introduction"
---

<p class="message">
  Introduction: The Data Analysis Cycle and the Filesystem
</p>


<h3>
	<span class="fa fa-picture-o fa-lg main-list-item-icon"></span> 
	<a href="" target="_blank">Introduction</a>
</h3>


<a href="http://www.phdcomics.com/comics/archive/phd053104s.gif" target="_blank"><img src="http://www.phdcomics.com/comics/archive/phd053104s.gif"></a>


### The Data Analysis Cycle

- Starting point: some raw data set(s)
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Hypothesis testing
- Simlation(s)
- Modeling
- Visualization(s)
- Reporting and communicating


### Toy Example

Let's consider the cyclone data set, described in 
[http://www.stat.ufl.edu/~winner/data/cyclone.txt](http://www.stat.ufl.edu/~winner/data/cyclone.txt), and available here:
[http://www.stat.ufl.edu/~winner/data/cyclone.dat](http://www.stat.ufl.edu/~winner/data/cyclone.dat)


### Activities

- Form groups of 2-3 people
- Do not code, just focus on writing brief descriptions
- Identify the main steps
	+ Write down a list of maximum 5 main steps (like a cooking recipe)
- Identify inputs and outputs
	+ For each main step, what are the input(s) and output(s)?
- Draw a diagram with the workflow
- Work with handout to write path names


### Network of relationships among files

- Classification of files (inputs, instructions, outputs)
- How does a data analysis project looks like from the files standpoint?
- Understanding the structure of directories and files
- Understanding the network of relationships between files
- It is FUNDAMENTAL to know where files are, and manage their pathnames
- How to start organizing things?
- How to NOT organize things
- What kinds of things can change in a project?


### Some Shell-related Terminology

- __Unix-like__ refers to a family of operating systems that 
includes Linux, Android, iOS (iPhone/iPad), and Mac OS X.
- The way that you interact with a Unix-like system is by using the command line.
- __Terminal__ (or terminal emulator) refers to the program that gives us a command line (i.e. provides a command line access to Unix). The terminal is where you type the commands. 
- The __kernel__ is the core of the operating system in Unix.  It's what takes care of allocating time and memory to program.
- __Shell__ is the outside of the kernell. The shell is the outer layer of the operating system. That's what you see when you open up a Terminal window.
- The shell interacts with the user (think of it as your working environment). Every time you execute a command, the shell will send requests to the kernel. The kernel will then do its thing and results will then be returned back to the shell so that you can interact with them again.
- There are several types of shells. Perhaps the most common one is the __bash__ (Bourne Again Shell) shell.

Many people use the terms "command line", "bash", and "shell" interchangeably. Although they are related terms, they are not synonyms. Bash is a type of shell. All shells require a command line interpreter or terminal emulator. That's where the user type commands, which are handled by the shell and send to the operating system (based on Unix).


### Summary

- A data analysis project can be viewed as an iterative pipeline
- A data analysis project involves working with files
- There is a implicit network of relationships among files
- It's fundamental to set up a good file structure
- You should know how to navigate such file structure (i.e. path names)
- A data analysis project may experience a variety of changes
- Ultimate goal: being prepared to recreate the analysis when anything changes


> Last but not least: Define teams for class presentations!

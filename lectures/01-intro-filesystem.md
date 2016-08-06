---
layout: lecture
title: "Introduction"
---

<p class="message">
  The Data Analysis Cycle and the Filesystem
</p>


## The Data Analysis Cycle

Every Data Analysis Project goes through a cycle

<a href="http://www.phdcomics.com/comics/archive/phd053104s.gif" target="_blank"><img src="http://www.phdcomics.com/comics/archive/phd053104s.gif"></a>

- Starting point: some raw data set(s)
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Hypothesis testing
- Simulation(s)
- Modeling
- Visualization(s)
- Report and communication


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


### Network of relationships among files

- Classification of files (inputs, instructions, outputs)
- How does a data analysis project looks like from the files standpoint?
- Understanding the structure of directories and files
- Understanding the network of relationships between files
- It is FUNDAMENTAL to know where files are, and manage their pathnames
- How to start organizing things?
- How to NOT organize things
- What kinds of things can change in a project?


### File-system and path names

Since all Data Analysis Projects involve working with files, we need to 
discuss/recap the concept of filesystem and path names.

- Navigating the file system
	- Understand the tree structure
	- Pathnames: absolute and relative
- The Root directory `/`
- The working directory
- The home directory
- Special directories: home `/~`, current `.`, parent `..`
- Absolute names
- Relative names
- Descending the tree
- Ascending the tree

Work on handout for path names


### Summary

- A data analysis project can be viewed as an iterative pipeline
- A data analysis project involves working with files
- There is a implicit network of relationships among files
- It's fundamental to set up a good file structure
- You should know how to navigate such file structure (i.e. path names)
- A data analysis project may experience a variety of changes
- Ultimate goal: being prepared to recreate the analysis when anything changes


> Last but not least: Define teams for class presentations!

---
layout: lecture
title: "Typical Work Style"
---

<p class="message">
  Typical way of working
</p>


<h3>
	<a href="" target="_blank">
		<span class="fa fa-picture-o fa-lg main-list-item-icon"></span> 
		How not to do a data analysis project
	</a>
</h3>

In this lecture we'll talk about the typical way of (not) doing things


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
- What if you had to handle this project to someone else? Is it clear where to begin, what to do?
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
- Open an Rmd file
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

- Limitations of WYSIWYG tools
- Advantages of using WYSIWYM tools
- Learn how to use a text editor (vim, emacs, nano, etc)
- Let the computer do the tedious, laborious, repetitive work
- Write documentation for all your projects
- Recognize the advantage of dynamic documents
- Collaboration: you are your main collaborator!

---
layout: lecture
title: "Introduction"
---

<p class="message">
  Introduction: The Data Analysis Cycle
</p>


<h4>
	<span class="fa fa-picture-o fa-lg main-list-item-icon"></span>
	Slides
</h4>

<a href="" target="_blank">Introduction</a>


<h4>
	<span class="fa fa-bars fa-lg main-list-item-icon"></span>
	Agenda
</h4>


### Understanding the Data Analysis Cycle

![by-the-numbers](http://www.phdcomics.com/comics/archive/phd053104s.gif)

- Start point: some raw data set(s)
- Cleaning and preprocessing
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

`cyclone.dat` is a fixed-width delimited file, which represents a tabular data 
with 3 columns and 12 rows:

|   |   |      |
|---|---|------|
| 1 | 1 |  370 |
| 1 | 2 |  452 |
| 1 | 3 |  273 |
| 1 | 4 |  422 |
| 2 | 1 |  526 |
| 2 | 2 |  624 |
| 2 | 3 |  513 |
| 2 | 4 | 1059 |
| 3 | 1 |  980 |
| 3 | 2 | 1200 |
| 3 | 3 |  995 |
| 3 | 4 | 1751 |


### Activities

- Form groups of 2-3 people
- Do not code, just focus on writing brief descriptions
- Identify the main steps (5 mins):
	+ Write down a list of maximum 5 main steps (like a cooking recipe)
- Identify inputs and outputs (5 mins)
	+ For each main step, what are the input(s) and output(s)?
- Draw a diagram with the workflow (5 mins)


### Summary

- A data analysis project can be viewed as a pipeline
- A data analysis project involves working with files


### Network of relationships among files

- Files can be inputs, instructions, or outputs
- Although we don't see it, there is an implicit network of 
relationships among files


### Changes in a project

Understanding that a data analysis project is subject to changes:

- data
- settings and parameters
- developer(s), maintainer(s)
- scope
- tools


> __Reproducibility__
>
> By changing any of the considered factors, we need to be able to
> recreate one or more parts of a project ...
> in a timely and efficient way.



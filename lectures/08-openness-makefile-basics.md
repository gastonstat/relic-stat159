---
layout: lecture
title: "Open Science and Make Basics"
---

<p class="message">
  Open Science
</p>


### Assigned Readings

<a href="https://en.wikipedia.org/wiki/Open_science" target="_blank"><i class="fa fa-newspaper-o" aria-hidden="true"></i> Open Science</a> (Wikipedia entry)

<a href="http://www.openscience.org/blog/?p=269" target="_blank"><i class="fa fa-newspaper-o" aria-hidden="true"></i> What Exactly is Open Science?</a> (by Dan Gezelter)

<a href="https://wiki.surfnet.nl/display/OSCFA/Amsterdam+Call+for+Action+on+Open+Science" target="_blank"><i class="fa fa-newspaper-o" aria-hidden="true"></i> Amsterdam Call for Action on Open Science</a> (by John Dove)

<a href="https://opensource.org/osd-annotated" target="_blank"><i class="fa fa-newspaper-o" aria-hidden="true"></i> The Open Source Definition</a> (by Open Source Initiative)

<a href="http://opendefinition.org/" target="_blank"><i class="fa fa-newspaper-o" aria-hidden="true"></i> The Open Definition</a> (by Open Knowledge)


### Discussion

Let's go back to the [Introduction](http://ropensci.github.io/reproducibility-guide/sections/introduction/) of the Reproducibility Guide by rOpenSci:

> __Why do reproducible research?__
>
> - Show evidence of the correctness of your results
> - Enable others to make use of our methods and results

> __What are the principles of Reproducible Research?__
>
> The aim of practising Reproducible Computational Research is to 
> expose our research workflow to our audience.
> This makes it easier to make a more informed assessment of our methods and results.
> It also makes it easier to adapt our methods to their own research.


We'll keep talking about open science in the next lectures. Right now I just want
you to realize the importance of the _Openness_ movement.

- What are the components of Open Science?
- How can we design or modify the scientific reward systems to embrace open science?
- What are the 12 actions described in the Amsterdam Call for Action on Open Science?


-----

<p class="message">
  Basics of Makefiles
</p>


- __Automation:__ The ability to rapidly re-create an analysis when data
and/or input changes (as it always does).
- Scripts to automate things
- What is GNU Make?
- We won't really use Make for compiling, but for automating tasks
- The main advantage is its capability to track timestamps
- It only executes things that have changed
- I've found that the learning curve is a bit steep
- We'll keep working with Make throughout the course,
so we will start with very simple makefiles

-----

<h3>
	<span class="fa fa-info-circle fa-lg main-list-item-icon"></span>
	More Info
</h3>

- [Tutorial about basics of GNU Make](https://github.com/unix-tools/tutorial-makefiles)
- <a href="https://www.youtube.com/watch?v=Lyp36ku7D0A" target="_blank">GNU Make and Makefiles</a> by <a href="https://www.andysayler.com/" target="_blank">Andy Sayler</a>
- [GNU Make Manual](http://www.gnu.org/software/make/manual/make.html)
- [Introduction to making Makefiles](http://www.jfranken.de/homepages/johannes/vortraege/make_inhalt.en.html) by Johannes Franken

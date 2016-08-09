---
layout: lecture
title: "Dynamic Documents part 1"
---

<p class="message">
  Dynamic Documents with R
</p>


### Assigned Reading

<a href="http://biostats.bepress.com/bioconductor/paper2/" target="_blank"><i class="fa fa-newspaper-o" aria-hidden="true"></i> Statistical Analyses and Reproducible Research</a> (by Robert Gentleman and Duncan Temple Lang)

Read the paper by Gentleman and Temple Lang, and focus mainly on the first
three sections:

- Who are the authors?
- What is their concept of a "compendium"?
- What do the authors mean by "Reproducible Research"?
- What do the authors mean by "dynamic document"?
- List three or more advantages of using dynamic documents
- What is the idea of Literate Programming?
- Review of some terminology: 
	+ code chunks
	+ weaving
	+ tangling 
- Complementary paper to the assigned reading (optional):
Literate Statistical Practice by Rossini and Leisch

-----


### Dynamic Documents with R

- What is a dynamic document?
- Dynamic documents and markup languages
- Dynamic documents require a parser and renderer
- In R, we have the packages "knitr", "rmarkdown", and "shiny"
- Before knitr we had "Sweave" (with LaTeX)
- LaTeX is still the _de rigueur_ scientific typesetting system


-----

<h3>
	<span class="fa fa-info-circle fa-lg main-list-item-icon"></span>
	More Info
</h3>

- [Literate Statistical Practice](http://biostats.bepress.com/uwbiostat/paper194/) by Anthony Rossini and Friedrich Leisch.
- [knitr website](http://yihui.name/knitr/) by Yihui Xie.
- [R Markdown website](http://rmarkdown.rstudio.com/) by RStudio.
	+ [Introduction to R Markdown](http://rmarkdown.rstudio.com/articles_intro.html)
	
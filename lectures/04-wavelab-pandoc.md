---
layout: lecture
title: "Reproducibility Notions"
---

<p class="message">
  Basics of Reproducibility
</p>


<h3>
	<a href="" target="_blank">
		<span class="fa fa-picture-o fa-lg main-list-item-icon"></span> 
	Reproducibility</a>
</h3>


### Assigned Reading

<a href="http://statweb.stanford.edu/~wavelab/Wavelab_850/wavelab.pdf" target="_blank"><i class="fa fa-newspaper-o" aria-hidden="true"></i> WaveLab and Reproducible Research</a> (by Jonathan Buckheit and David Donoho)

- Skip sections 4 and 5
- Who are the authors? Find out a little bit about the authors
- What is the thesis (i.e. the main point or argument)?
- What is the biased (if any) of the article?
- What are the conclusions?
- What is the part or section that interested you the most?


### Claerbout's famous statement

> An article about computational science in a scientific publication 
> is not the scholarship itself, it is merely advertising of the scholarship. 
> The actual scholarship is the complete software development and 
> the complete set of instructions which generated the figures.


### Donald Knuth's Literate Programming

<a href="http://www.literateprogramming.com/knuthweb.pdf" target="_blank">
Literate Programming</a> (by Donald Knuth)

> I believe that the time is ripe for significantly better documentation 
> of programs, and that we can best achieve this by considering programs
> to be works of literature.

> Let us change the traditional attitude to the construction of programs: 
> Instead of imagining that our main task is to instruct a computer what to do, 
> let us concentrate rather on explaining to human beings what we want a computer to do.


### Pandoc

- Recap: Reproducibility requires special "authoring" tools and markup syntaxes
- Markdown and pandoc are good starting points
- Philosophy of Pandoc
- Small demos:
	+ from markdown to html
	+ from markdown to latex
	+ from markdown to pdf
	+ from markdown to docx
	+ etc

Pandoc is a command-line tool. There is no graphic user interface. 
So, to use it, you’ll need to open a terminal window.

To verify that pandoc is installed, type:

```bash
pandoc --version
```

By default, input is interpreted as pandoc markdown, and output is HTML 4.
Assuming that you have a text file `doc.md` written in markdown,
the default command to generate the html file would be:
```bash
pandoc doc.md
``` 

The previous command can be equivalently executed with the options
`-f` _from_ markdown, and `-t` _to_ html: 
```bash
pandoc -f html -t markdown doc.md
```

Converting _from_ HTML _to_ markdown: 
```bash
pandoc -f html -t markdown
```


### Resources

- [About pandoc](http://pandoc.org/index.html)
- [Getting started with pandoc](http://pandoc.org/getting-started.html)
- [User's guide](http://pandoc.org/MANUAL.html)


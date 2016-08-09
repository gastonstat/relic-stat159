---
layout: lecture
title: "Dynamic Documents part 2"
---

<p class="message">
  Dynamic Documents and Regression Analysis
</p>


### Assigned Reading

<a href="http://www-bcf.usc.edu/~gareth/ISL/data.html" target="_blank"><i class="fa fa-newspaper-o" aria-hidden="true"></i> Chapter 3 of "An Introduction to Statistical Learning": Linear Regression</a> (by James et al)

The third chapter of _An Introduction to Statistical Learning_ covers 
linear regression---a technique for predicting a quantitative response.
Section 3.1 describes simple linear regression (i.e. one predictor variable).
In turn, section 3.2 describes multiple linear regression (i.e. multiple predictor 
variables). Most of the discussion and examples use the dataset `Advertising`.

We will use the material of the chapter to work on the Lab and HW associated
to the introduction of dynamic documents.


__Provide a description for the following points:__

- Dataset `Advertising` (see chapter 2 of the book).
- Overall problem: "suggesting a marketing plan for next
year that will result in high product sales".
- Notation (symbols) and terminology.
- Simple linear regression model:
	+ equation
	+ assumptions
- Estimation of regression coefficients:
	+ residual sum of squares
	+ least squares criterion
- Estimation of the residual standard error (RSE)
- Confidence Intervals for the regression coefficients
- Hypothesis tests for the regression coefficients
	+ global F-test
	+ t-test for each individual coefficient
- Assessing the accuracy of the model:
	+ RSE
	+ R-squared statistic
- Generalization to multiple regression model
- Using the regression equation for prediction purposes


__Answer the questions addressed in pages 59-60:__

- Is there a relationship between advertising budget and sales?
- How strong is the relationship between advertising budget and sales?
- Which media contribute to sales?
- How accurately can we estimate the effect of each medium on sales?
- How accurately can we predict future sales?
- Is the relationship linear?

-----


### Regression Analysis with R

- Recap of (simple) linear regeression analysis
- Regression Analysis in R
- Function `lm()`
	+ input
	+ output
- Summary method `summary()` for an object `"lm"`
- Plots
- Prediction method `predict()` for an object `"lm"`
- Confidence intervals with function `confint()` 


-----

<h3>
	<span class="fa fa-info-circle fa-lg main-list-item-icon"></span>
	More Info
</h3>

- [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/data.html) by James et al.
- [Practical Regression and Anova using R](https://cran.r-project.org/doc/contrib/Faraway-PRA.pdf) by Julian Faraway.

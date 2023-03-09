# Gender Bias in Graduate Admissions

Objective: To determine whether there is a gender bias in admissions for graduate school

Skills: Logistic/logit Regression, Hypothesis Testing, Data Visualization, Data Manipulation

Tools: R, dplyr, ggplot, tidyverse

## Section 1
- load the data and the libraries required
- use `tidy()` function to tidy up the messy data

## Section2 
- we are interested in the proportion of gender in the data
- manipulating the data to obtain the proportion

## Section 3
- plot out the data to get a better sense of the distribution

## Section 4
- the unequal frequency might due to departments
- group the data by departement and plot it out
- this can be used to identify the Simpson's Paradox

## Section 5
- identify the department that may have gender bias, those will be our interests
- make a hypothesis such that H~0~: there is no gender bias
- manipulate the data again so that we can proceed with a correct dataset

## Section 6
- since there are categorical variable, we need to classify which will be the reference level to prevent perfect multicollinearity
- use the `glm()` function to run logistic regression

## Section 7
- the model we ran in Section 6 might have a problem of Omitted Variable Bias, causing our estimation be biased
- here, we control for `Gender` variable by including it into our model
- note that now the effect of `GenderMale` on `Admit` is not statistically significant

## Section 8
- we have now seen the Simpson's Paradox
- if we run a logistic regression for Department A only, we can see that there are no gender bias in it
- that said, there might be gender bias in one department, but not neccessarily the others

## Section 9
- completed








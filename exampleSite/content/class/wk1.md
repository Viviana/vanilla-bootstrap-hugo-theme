---
title: "SPP608lab1"
author: "Viviana Wu"
date: "2/3/2021"
output:
  word_document: default
  html_document: default
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## R Studio 

R Studio is an Integrated Development Environment (IDE). This program serves as a text editor, data manager, and package library to help you read and write R code. You can create R script, R Markdown, Shiny App, run Python script and many more in R Studio. 

## Running R codes  

Use  `COMMAND`+`ENTER` key on Mac, and `CONTROL`+ `ENTER` key on PC to run a R script one line at a time. 
(Put your cursor to the line of code you want to run!) To run multiple lines, just select them and run.

## Variable Assignment  

`<-` is a left assignment operator in R (i.e., to command R to assign values to vectors, which are the codes after the arrow)

These operators are used to assign values to variables.

```{r}
a <- "this is my first line of R code"

# a is the object you want to specify and want R to remember! 

```

### Q1: Can you repeat the following example and introduce yourself to R?

```{r}
Viviana <- "Viviana is the instructor of SPP608. She does research on philanthropy and nonprofits and their policy roles online and offline."  

Viviana       # check if R stores the answer for you.


# Your turn:




```

## R Markdown

This is an R Markdown document. We will be using R Markdown for **all your assignments and quizzes**. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

For more examples on R code chunk, see learnr lesson 3: <https://rmarkdown.rstudio.com/lesson-3.html>

```{r cars}
print(cars)  # cars is an existing data set stored in R

```
## What is a data frame?

A data frame is a rectangular collection of values, usually organized so that **observations** appear in rows (unique entities, such as student id) and variables appear in the **columns** (such as height, GPA). 

### Q2: How many variables can you find from `car` dataset? (Tips: How many columns are there? Numbers don't need to use `""` for numerical value)
```{r}
# Let's write your answer in R's way! (Tips: column <- ?)



# check if R stores the answer for you. 

```

### Q3: Repeat the code for row: How many observations can you find from `car` dataset? (Tips: How many rows are there?)

```{r}



# check if R stores the answer for you. 

```

# Submit your Assignment 

## Step 1: Double check if you answered all questions and check for accuracy ALWAYS!

## Step 2: `Knit` your R Markdown document--move your cursor to the face-down triangle next to `Knit`, and choose for **a word or pdf document** (name your file as "Last name_HW1", e.g., Wu_HW1)  

## Step 3: Submit two copies of R Markdown documents to Gradescope <https://www.gradescope.com/>

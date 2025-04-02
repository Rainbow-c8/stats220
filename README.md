# stats220

This is my repo for STATS 220. 

A little about me:

- I am undertaking a degree in Computer Science.
- I am taking STATS 220 because it is a compulsory subject for me.
- I am interested in learning about how to program the code in java.

**Introduction to Computer Science**

Various _Algorithms_
Different programming formats(based on _Languages_)

The level of **Computer Science** is constantly expanding
_Algorithms_ are essential for efficient computation.

- The _Languages_ in **Computer Science**:
  - Python
  - Java
  - C++

1. The step on Programming code:
   1. According to the demand of the request
   2. Programming framework
   3. Improve the program based on bugs

For more details, please visit [https://www.springer.com/cn/computer-science]

A meme that captures how I currently feel about my university studies is ![https://i0.hdslb.com/bfs/article/85921d280d927a4e940f58ae192290ffab70bc9d.gif]

An existing meme online that contains both an image and text which I found is [https://www.engagebay.com/blog/wp-content/uploads/2022/10/inspirationmeme5.png]
**inspo_meme** is saved and with the _.png_ format.
![inspo_meme](https://github.com/user-attachments/assets/52d70056-4dad-4d90-b1c6-e60a350c974e)

We could analyze the meme design in many way.
1. The meme type is a photo.
2. Text located on the bottom of the meme.
   1. It is all _uppercase_.
3. The font style is simple.
   1. White text with black outlines.
4. This meme in sunshine and grass, both bright colors.
5. The theme is a joke with a skull(bro) on it, full of humor.

Below is my Appendix from Project 2:
[Uploading project2_report.Rmd…]()
---
title: "Project2"
author: "Rui Cheng"
date: "`r Sys.Date()`"
subtitle: "STATS 220 Semester One 2025"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```
## Introduction
For this project, I focused on recording books over the course of a week. Every time I open a book, I record the relevant information. The purpose is to analyze the influence of various data on the choice of reading.

To keep the form simple, I use a format like an exeal form so that the data is clear at a glance, and location and entry are faster. This helps save time in troubleshooting errors.

Analyzing this data helps determine which book categories appear most frequently, which days of the week you have more time to read, and whether the cover matter. It can provide some information for judging a person's character. In addition, it is possible to draw up a schedule to some extent
## Dynamic report
https://github.com/Rainbow-c8/stats220.git
## Creativity
This project demonstrates creativity in a number of ways:

** Data Collection methods ** : One of the things I focus on is the cover color - which can also be interpreted as the first impression. Structured forms make data entry seamless.

** Dynamic Reports ** : Use RMarkdown to automatically update reports when new data is added.

Take a unique approach to data tracking and focus on relevant topics.
## Learning reflection
One of the things I learned from Module 2 is the web-based dynamic reporting for real-time data updates. So when I connected my Google Sheets CSV to Rstudio I could immediately see the change and reflect it in my analysis.

For more advanced dynamic reporting, I think I still need to learn more about this project.

Overall, this project deepened my understanding of data visualization and report automation.
## Appendix
Below is the code from my `exploration.R` and `dynamic_report.Rmd` files:
### **exploration.R**
```{r}
knitr::include_graphics("exploration.R")
knitr::include_graphics("dynamic_report.Rmd")
```

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

```{r cars}
summary(cars)
```

## Including Plots

You can also embed plots, for example:

```{r pressure, echo=FALSE}
plot(pressure)
```

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.

# STAT 220 labs

At the University of St Thomas (St. Paul, MN), introductory statistics courses are taught in large lectures (~60-90 students), with accompanying smaller lab sections (~20-30 students). In lab sections, students learn to use statistical software to analyze data. Software varies by lab, with labs taught in JMP, SPSS, Minitab, Excel, and R. In lab, students experience a "pre-lab," which exposes them to the statistical concepts and software skills necessary to complete the lab assignment they will turn in for credit. These pre-labs are customized by instructors to the software used in the lab. However, no matter which lab section students are enrolled in, the questions asked on their graded lab assignments are the same. Lab exercises were developed by the faculty in order to be tool-agnostic. 

In Spring 2020, I had the first opportunity to teach R labs at St Thomas, and was assigned two sections (both associated with the same lecture section). As someone interested in statistics education, particularly with regard to computing, I wanted to do the best job possible. At my previous institution, I had taught similar labs, both in formula syntax (mosaic, lattice graphics) and in tidyverse syntax (dplyr, ggplot2, etc). However, I had never had the opportunity to compare the syntaxes head-to-head. Instead, I had tried one syntax one semester, and another a different semester, giving rise to many other varying circumstances. In particular, my materials and assignments would change, to be easier to complete in a given syntax. In Spring 2020, I was able to control more of the variability. Both sections were taught by me, in the same semester, with the same lab assignments. So, I decided to teach one section in formula syntax and the other in tidyverse syntax. (I have a [cheatsheet](https://github.com/rstudio/cheatsheets/raw/master/syntax.pdf) I developed while teaching a particular syntax to show students parallel tasks in other R syntaxes. The cheatsheet also includes the base R syntax, which I chose not to teach.)

Of course, the teaching materials I used in the pre-labs could not be completely standardized. However, I made every effort to make them similar. For the first lab, I wrote the tidyverse version first, and then modified the document to create a corresponding formula version. The next week, I switched the order, writing the formula version first and modifying for tidyverse. 

There are 12 labs included here:
- lab 1: Introduction to R and RStudio, describing data
- lab 2: EDA for categorical variables: bar charts, tables, two-way tables
- lab 3: EDA for one numeric variable: histograms, boxplots, measures of central tendancy and spread
- lab 4: EDA for two numeric variables: scatterplots, correlation and regression 
- lab 5: bootstrap for confidence intervals
- lab 6: randomization for hypothesis tests
- lab 7: inference for a single proportion using distributional approximation (z-tests)
- lab 8: inference for a single mean using distributional approximation (t-tests)
- lab 9: inference for two variables using distributional approximations (t- and z-tests, difference of proportions, difference of means, paired data)
- lab 10: ANOVA
- lab 11: Chi-square for goodness of fit and independence
- lab 12: inference for regression

There are YouTube videos that accompany each of the pre-labs. YouTube videos for the formula labs are [here](https://www.youtube.com/playlist?list=PLik6fAQnSI90bHK9fapPS-eZCUhgROh6S) and for the tidyverse labs are [here](https://www.youtube.com/playlist?list=PLik6fAQnSI93eBVuAONFBCVdOd7VFhKQX). 

Each pre-lab uses the same example dataset, `GSS-clean.csv`, included in the directory `data`. There are also two "all the R you need" sheets, one for formula and one for tidyverse. 

The primarily content of this repo are the pre-lab exercises, which often contain blanks that need to be filled in by students. I have many other materials associated with this course, including completed pre-labs, blank lab assignments, and completed lab assignment keys. If you are an instructor or researcher who is interested in these materials, please contact me. 

UPDATE June 2024: I have changed the magrittr pipe, `%>%` to the base R pipe, `|>` in this code. When students saw the documents they used the magrittr pipe, but `|>` has become standard. If you want to see the original version with `%>%`, see [version 1.0.0](releases/tag/v1.0.0). 


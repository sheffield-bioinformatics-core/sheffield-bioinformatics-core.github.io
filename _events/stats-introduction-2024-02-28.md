---
layout: page
organizer: Sheffield Bioinformatics Core
category: workshop
permalink: /training/stats-introduction-2024-02-28
title: Statistical Analysis of Biological Data in R
excerpt: "Stats Intro"
date: 2024-02-28
end-date: 2024-02-28
startDate: 2024-02-28
endDate: 2024-02-28
startTime: 13.00
endTime: 17.00
from: "13:00"
to: "17:00"
location: "Bartolome House - Seminar Room EG03, or ONLINE"
speaker: "Dr. Aya Elwazir, Dr. Mark Dunning"
postcode: S3 7ND
city: Sheffield, or online
country: United Kingdom
city: Sheffield, or ONLINE
venue: Bartolome House, Seminar Room EG03, University of Sheffield, or ONLINE
description: "This course provides a refresher on the foundations of statistical analysis. "
keywords: statistics, R, biostatistics, online
scientific_keywords: statistics, biostatistics
difficulty: beginner
contact: bioinformatics-core@sheffield.ac.uk
---

#

- Wednesday 28th February, 13:00 - 17:00
- Bartolome House, Seminar Room EG03, or ONLINE
- [Registration Link](https://onlineshop.shef.ac.uk/conferences-and-events/faculty-of-medicine-dentistry-and-health/medical-school)

## Overview
This course provides a refresher on the foundations of statistical analysis. The course is aimed at scientists at all levels – especially those whose formal education likely included statistics, but who have not perhaps put this into practice since. The focus of the course is on understanding the principles behind statistical testing, how to choose and execute the most appropriate test for your data, and how to interpret the result.

**Note that you will need to be familiar with R to access this course. Please see our latest introductory course on using R to check if you have sufficient background
[https://sbc.shef.ac.uk/training/r-introduction-2024-01-29/](https://sbc.shef.ac.uk/training/r-introduction-2024-01-29/)**


## Who should attend this course?

The course is aimed primarily at scientists at all levels – especially those whose formal education likely included statistics, but who have not perhaps put this into practice since. 

## Objectives:- After this course you should be able to:

- State the assumptions required for a one-sample and two-sample t-test and be able to interpret the results of such a test
- Know when to apply a paired or independent two-sample t-test
- To perform simple statistical calculations using R
- Understand the limitations of the tests taught within the course
- Know when more complex statistical methods are required


## Aims:- During this course you will learn about:

- Different types of data, distributions and structure within data
- Summary statistics for continuous and discrete data
- Formulating a null hypothesis
- Assumptions of one-sample and two-sample t-tests
- Interpreting the result of a statistical test
- Statistical tests of categorical variables (Chi-squared and Fisher’s exact tests)
- Non-parametric versions of one- and two-sample tests (Wilcoxon tests)


## Prerequisites

- Introductory-level R; for example attending our [Data Manipulation and Visualisation](http://sbc.shef.ac.uk/training/r-introduction-2024-02-29/) course


## Provisional Timetable and Materials



# Setup

1) First, install both R **and** RStudio for your operating system. 

### Windows

Install R by downloading and running [this .exe file](http://cran.r-project.org/bin/windows/base/release.htm) from CRAN. Also, please install the [RStudio IDE](http://www.rstudio.com/ide/download/desktop). Note that if you have separate user and admin accounts, you should run the installers as administrator (right-click on .exe file and select "Run as administrator" instead of double-clicking). Otherwise problems may occur later, for example when installing R packages.

### Mac

Install R by downloading and running [this .pkg file](https://cran.r-project.org/bin/macosx/base/R-4.2.1.pkg) from CRAN. Also, please install the free [RStudio IDE](https://www.rstudio.com/products/rstudio/download/#download) 

### Linux

You can download the binary files for your distribution from CRAN. Or you can use your package manager (e.g. for Debian/Ubuntu run `sudo apt-get install r-base` and for Fedora run `sudo yum install R`). Also, please install free [the RStudio IDE](https://www.rstudio.com/products/rstudio/download/#download). 



2) Type the following into the R console to install some extra R packages required for the workshop

```
install.packages("dplyr")
install.packages("ggplot2")
install.packages("readr")
install.packages("rmarkdown")
install.packages("tidyr")
```



**Mac Users may get the following error message when trying to install these packages**

```
xcrun error: inactive developer path (/Library/Developer/CommandLineTools), missing xcrun at:.....

```

If this is the case, you will need to follow the instructions from this link to install "Xcode"

[https://apple.stackexchange.com/questions/254380/why-am-i-getting-an-invalid-active-developer-path-when-attempting-to-use-git-a](https://apple.stackexchange.com/questions/254380/why-am-i-getting-an-invalid-active-developer-path-when-attempting-to-use-git-a)

**Window users might get a message that Rtools is required. This shouldn't be necessary, but you might need it for other packages. It can be installed here:-**

[https://cran.r-project.org/bin/windows/Rtools/](https://cran.r-project.org/bin/windows/Rtools/)




## Instructors

- Mark Dunning, Bioinformatics Core Director
- Emily Chambers, Bioinformatics Core Scientist
- Aya Elwazir, PhD Student


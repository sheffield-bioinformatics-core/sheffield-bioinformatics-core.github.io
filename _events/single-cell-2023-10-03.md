---
layout: page
category: workshop
permalink: /training/single-cell-2023-10-03
organizer: Sheffield Bioinformatics Core
title: Introduction to Single-cell RNA-seq in R
excerpt: "Single-cell RNA-seq in R"
startDate: 2023-10-03
date: 2023-10-03
endDate: 2023-10-03
end-date: 2023-10-03
startTime: 09.30
from: "09:30"
endTime: 16.30
to: "16:30"
city: Sheffield
postcode: S10 2HQ
country: United Kingdom
venue: Barber House Boardroom (PROVISIONAL) or ONLINE
description: "Recent advances in gene expression technologies have made it possible to measure transcription for individual cells - enabling researchers to understand cellular heterogeneity and understand complex tissue types.  In this course we describe the analysis of data derived from such experiments using the R language"
keywords: bioinformatics, NGS, RNA-seq, R, single-cell, 10X, online
scientific_keywords: bioinformatics, transcriptomics, functional genomics, single-cell, clustering, cell-types
difficulty: beginner
contact: bioinformatics-core@sheffield.ac.uk
location: Barber House Boardroom, University of Sheffield, or Online
speaker: Dr. Mark Dunning, Dr. Emily Chambers
---

## Workshop Information

Tuesday 3rd October 09:30 - 16:30

Barber House Boardroom, The University of Sheffield (PROVISONAL), or online, [Book here](https://onlineshop.shef.ac.uk/conferences-and-events/faculty-of-medicine-dentistry-and-health/medical-school) 



***Some basic R knowledge is assumed (and is essential). Without it, you will struggle on this course. If you are not familiar with the R statistical programming language we strongly encourage you to work through an introductory R course before attempting these materials. We recommend reviewing Parts 1 and 2 of our R introductory course before deciding if you can attend***

- [R crash course Part 1](https://sbc.shef.ac.uk/r-online/part1.nb.html)
- [R crash course Part 2](https://sbc.shef.ac.uk/r-online/part2.nb.html) 

## Registration Link

You can sign-up to attend either in-person or online using this link

- [https://onlineshop.shef.ac.uk/conferences-and-events/faculty-of-medicine-dentistry-and-health/medical-school](https://onlineshop.shef.ac.uk/conferences-and-events/faculty-of-medicine-dentistry-and-health/medical-school)

## Overview

Recent advances in gene expression technologies have made it possible to measure transcription for individual cells - enabling researchers to understand cellular heterogeneity and understand complex tissue types.  In this course we describe the analysis of data derived from such experiments using the R language. 

We will focus specifically on data generated using the 10X protocol, although the methods will relevant to other technologies


## Who should attend this course?

Researchers in life sciences who want to get an appreciation for the computational steps involved in Single-cell RNA-seq analysis, and how to execute best-practice RNA-seq workflows in R.

## Objectives:- After this course you should be able to:

- Read data from a 10X experiment into R
- Perform quality assessment on single-cell RNA-seq data
- Execute different clustering methods
- Identify a set of markers to distinguish unique cell clusters


## Aims:- During this course you will learn about:

- The Seurat R package
- What QC metrics are commonly-used for single-cell RNA-seq
- Normalization and integration of single-cell datasets
- The theory behind popular clustering methods for single-cell data


## Setup 

1) First, install both R **and** RStudio for your operating system. 

### Windows

Install R by downloading and running [this .exe file](http://cran.r-project.org/bin/windows/base/release.htm) from CRAN. Also, please install the [RStudio IDE](http://www.rstudio.com/ide/download/desktop). Note that if you have separate user and admin accounts, you should run the installers as administrator (right-click on .exe file and select "Run as administrator" instead of double-clicking). Otherwise problems may occur later, for example when installing R packages.

### Mac

Install R by downloading and running [this .pkg file](https://cran.r-project.org/bin/macosx/base/R-4.2.2.pkg) from CRAN. Also, please install the free [RStudio IDE](https://www.rstudio.com/products/rstudio/download/#download) 

### Linux

You can download the binary files for your distribution from CRAN. Or you can use your package manager (e.g. for Debian/Ubuntu run `sudo apt-get install r-base` and for Fedora run `sudo yum install R`). Also, please install free [the RStudio IDE](https://www.rstudio.com/products/rstudio/download/#download). 


  
2) Please download and extract (un-zip) this zip file into the directory on the computer that you wish to work in

- [Course Data](https://drive.google.com/file/d/1Em7pGgweMOCLxZWNgEle5L2p5ynZsdyt/view?usp=sharing)

3) Type the following into the R console to install some extra R packages required for the workshop

```
source("https://raw.githubusercontent.com/sheffield-bioinformatics-core/scrnaseq_course/main/install_packages.R")
```



**Mac Users may get the following error message when trying to install these packages**

```
xcrun error: inactive developer path (/Library/Developer/CommandLineTools), missing xcrun at:.....

```

If this is the case, you will need to follow the instructions from this link to install "Xcode"

[https://apple.stackexchange.com/questions/254380/why-am-i-getting-an-invalid-active-developer-path-when-attempting-to-use-git-a](https://apple.stackexchange.com/questions/254380/why-am-i-getting-an-invalid-active-developer-path-when-attempting-to-use-git-a)

**Window users might get a message that Rtools is required. This shouldn't be necessary, but you might need it for other packages. It can be installed here:-**

[https://cran.r-project.org/bin/windows/Rtools/](https://cran.r-project.org/bin/windows/Rtools/)


## Materials

- [Part 1 - Markdown](https://sbc.shef.ac.uk/scrnaseq_course/session1.Rmd)
<!--- [Part 1 - HTML](session1.nb.html)-->
- [Part 2 - Markdown](https://sbc.shef.ac.uk/scrnaseq_course/session2.Rmd)
<!--- [Part 2 - HTML](session2.nb.html)-->
- [Part 3 - Markdown](https://sbc.shef.ac.uk/scrnaseq_course/session3.Rmd)
<!--- [Part 3 - HTML](session3.nb.html)-->


## Instructors

- Dr. Emily Chambers, Bioinformatics Core Scientist
- Dr. Mark Dunning, Bioinformatics Core Director
- Martina Morchio, PhD Student, Faculty of Health



## Timetable (provisional)





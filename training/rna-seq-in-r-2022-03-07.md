---
layout: page
organizer: Sheffield Bioinformatics Core
title: Introduction to RNA-seq analysis in R
excerpt: "RNA-seq in R"
startDate: 2020-07-13
endDate: 2020-07-14
startTime: 9.30
endTime: 17.00
city: sheffield
postcode: S3 7RD
country: United Kingdom
venue: The Diamond, Workroom 1
description: "In this workshop, you will be learning how to analyse RNA-seq count data, using R. This will include reading the data into R, quality control and performing differential expression analysis and gene set testing, with a focus on the edgeR analysis workflow. You will learn how to generate common plots for analysis and visualisation of gene expression data, such as boxplots and heatmaps. You will also be learning how alignment and counting of raw RNA-seq data can be performed in R. This workshop is aimed at biologists interested in learning how to perform differential expression analysis of RNA-seq data when reference genomes are available.."
keywords: bioinformatics, NGS, RNA-seq, R
difficulty: beginner
contact: bioinformatics-core@sheffield.ac.uk
---

- Sheffield - 13th /14th July 2020
- 09:30am - 5pm
- The Diamond, Workroom 1

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3365.6502641679717!2d-1.4835925589425!3d53.381301664196606!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x48797881e28b3e81%3A0x611c9522ca2169ed!2sThe+Diamond!5e0!3m2!1sen!2suk!4v1533302104527" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>

## Overview

In this workshop, you will be learning how to analyse RNA-seq count data, using R. This will include reading the data into R, quality control and performing differential expression analysis and gene set testing, with a focus on the DESEq2 analysis workflow. You will learn how to generate common plots for analysis and visualisation of gene expression data, such as boxplots and heatmaps. You will also be learning how alignment and counting of raw RNA-seq data can be performed in R. This workshop is aimed at biologists interested in learning how to perform differential expression analysis of RNA-seq data when reference genomes are available.

***Some basic R knowledge is assumed (and is essential). Without it, you will struggle on this course. If you are not familiar with the R statistical programming language we strongly encourage you to work through an introductory R course before attempting these materials. We recommend reading our [R crash course](https://bioinformatics-core-shared-training.github.io/r-crash-course/) before attending, which should take around 1 hour***

***Please also make sure you have experience of using the Unix command line. For example by following a Software Carpentry lesson on the [Unix shell](http://swcarpentry.github.io/shell-novice/), or following the online [command-line bootcamp](http://rik.smith-unna.com/command_line_bootcamp/?id=ghu7d9fl7cn)***

## Acknowledgements

This course is based on the course [RNAseq analysis in R](http://combine-australia.github.io/2016-05-11-RNAseq/) originally prepared by [Combine Australia](https://combine.org.au/) and delivered on May 11/12th 2016 in Carlton. The course was then modified by Cancer Research Uk Cambridge Institute and delivered as part of the [CRUK Functional Genomics Autumn School](https://bioinformatics-core-shared-training.github.io/cruk-autumn-school-2017/)

![](https://raw.githubusercontent.com/sheffield-bioinformatics-core/RNAseq-R/gh-pages/images/combine_banner.png)

![](https://raw.githubusercontent.com/sheffield-bioinformatics-core/RNAseq-R/gh-pages/images/CRUK_Cambridge_Major%20Centre%20logo.jpg)

## Who should attend this course?

Researchers in life sciences who want to get an appreciation for the computational steps involved in RNA-seq analysis, and how to execute best-practice RNA-seq workflows in R.

## Objectives:- After this course you should be able to:

- Design properly your RNA-Seq experiments considering advantages and limitations of RNA-seq assays
- Assess the quality of your datasets
- Know what tools are available in Bioconductor for RNA-seq data analysis and understand the basic object-types that are utilised
- Produce a list of differentially expressed genes from an RNA-seq experiment 

## Aims:- During this course you will learn about:

- RNA sequencing technology and considerations on experiment design
- Sources of variation in RNA-seq data
- Differential expression analysis using edgeR and DEseq2
- Annotation resources in Bioconductor
- Identifying over-represented gene sets among a list of differentially expressed genes 
    
## Software installation
You will need to bring an internet-enabled laptop to the course and install the latest versions of both R ***and*** RStudio before coming to the course

### Windows

Install R by downloading and running [this .exe](http://cran.r-project.org/bin/windows/base/release.htm) file from CRAN. Also, please download and run the [RStudio installer for Windows](https://www.rstudio.com/products/rstudio/download/#download). Note that if you have separate user and admin accounts, you should run the installers as administrator (right-click on .exe file and select “Run as administrator” instead of double-clicking). Otherwise problems may occur later, for example when installing R packages.

### Mac

Install R by downloading and running [this .pkg](http://cran.r-project.org/bin/macosx/R-latest.pkg) file from CRAN. Also, please download and run [the RStudio installer for Mac](https://www.rstudio.com/products/rstudio/download/#download)

### Linux

You can download the binary files for your distribution from CRAN. Or you can use your package manager (e.g. for Debian/Ubuntu run `sudo apt-get install r-base` and for Fedora run `sudo yum install R`). Also, please download and run the [RStudio installer](https://www.rstudio.com/products/rstudio/download/#download).


## Instructors

- Dr. Mark Dunning, Bioinformatics Core Director
- to be confirmed

## Docker

We also have a *docker* container that has all the software packages and data pre-installed. First [install docker](https://www.docker.com/community-edition#/download) and then launch the container with:-

```
docker run -p 8787:8787 markdunning/rna-seq-r
```
In your web browser ```http://localhost:8787``` should show an RStudio session. The username and password are both ```rstduio```.

## Timetable (provisional)

Day 1
- [Preamble](https://docs.google.com/presentation/d/15OLjTTRniIYADnSU6KS1vfmIa6gVFNWGWory8FUR_8k/edit?usp=sharing)
- 09:30 - 10:30 [Introduction to RNA-seq data]()
- 10:30 - 12:30 [Dealing with raw RNA-seq reads]()
- 12:30 - 13:30 LUNCH
- 13:30 - 15:00 [Quantifying transcripts with salmon]()
- 15:00 - 17:00 [Quality assessment and pre-processing]()

Day 2

- 09:30 - 11:00 Quality assessment and pre-processing for RNA-seq - continued
- 11:00 - 12:30 [Differential Expression]()
- 12:30 - 13:30 LUNCH
- 13:30 - 15:30 [Annotation and Visualisation of RNA-seq results]()
- 15:30 - 17:00 [Gene set testing]()


## Feedback



## Registration 

Registration is opening soon. Sign-up to our [mailing list](https://groups.google.com/a/sheffield.ac.uk/forum/#!forum/bioinformatics-core-news/join)to get updates.


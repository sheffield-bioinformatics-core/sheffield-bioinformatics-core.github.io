---
layout: page
organizer: Sheffield Bioinformatics Core
category: workshop
permalink: /training/rna-seq-r-2024-12-02
title: Introduction to RNA-seq analysis in R
excerpt: "RNA-seq in R"
startDate: 2024-12-02
date: 2024-12-02
endDate: 2024-12-06
end-date: 2024-12-06
startTime: 13.00
from: "13:00"
endTime: 16.00
to: "16:00"
city: Sheffield, or online
postcode: S3 7RD
location: Bartolome House EG03, 301 Glossop Road Workshop 1 or ONLINE
country: United Kingdom
venue: Bartolome House EG03, 301 Glossop Road Workshop 1 or ONLINE
description: "In this workshop, you will be learning how to analyse RNA-seq count data, using R. This will include reading the data into R, quality control and performing differential expression analysis and gene set testing, with a focus on the DESeq2 analysis workflow. You will learn how to generate common plots for analysis and visualisation of gene expression data, such as boxplots and heatmaps. This workshop is aimed at biologists interested in learning how to perform differential expression analysis of RNA-seq data when reference genomes are available.."
keywords: bioinformatics, NGS, RNA-seq, R
difficulty: beginner
contact: bioinformatics-core@sheffield.ac.uk
speaker: Dr. Mark Dunning, Dr. Akshay Bhat
---

## Workshop Information

- Monday 2nd December 13:00 - 16:00; 301 Glossop Road, Workshop 1
- Wednesday 4th December 13:00 - 16:00; Bartolome House EG03
- Friday 6th December 13:00 - 16:00; 301 Glossop Road, Workshop 1

You will need to attend **all three sessions**, or be commited to catch-up on any materials you missed, in order to complete the workshop


***Some basic R knowledge is assumed (and is essential). Without it, you will struggle on this course. If you are not familiar with the R statistical programming language we strongly encourage you to work through an introductory R course before attempting these materials. We recommend reviewing Parts 1 and 2 of our R introductory course before deciding if you can attend***

- [R crash course Part 1](https://sbc.shef.ac.uk/r-online/part1.nb.html)
- [R crash course Part 2](https://sbc.shef.ac.uk/r-online/part2.nb.html) 

## Registration Link

University of Sheffield staff / students are recommended to book via myDevelopment

Otherwise, please use [this link](https://onlineshop.shef.ac.uk/conferences-and-events/faculty-of-health/the-medical-school) to register for the course. There are options for attending online and in-person.

## Materials



## Overview

In this workshop, you will be learning how to analyse RNA-seq count data, using R. This will include reading the data into R, quality control and performing differential expression analysis and gene set testing, with a focus on the DESEq2 analysis workflow. You will learn how to generate common plots for analysis and visualisation of gene expression data, such as boxplots and heatmaps. You will also be learning how alignment and counting of raw RNA-seq data can be performed in R. This workshop is aimed at biologists interested in learning how to perform differential expression analysis of RNA-seq data when reference genomes are available.

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
- Differential expression analysis using DEseq2
- Annotation resources in Bioconductor
- Identifying over-represented gene sets among a list of differentially expressed genes 
    
## Software installation

You will need to bring an internet-enabled laptop to the course and install the latest versions of both R ***and*** RStudio before coming to the course

1) Install R and RStudio 

### Windows

Install R by downloading and running [this .exe](http://cran.r-project.org/bin/windows/base/release.htm) file from CRAN. Also, please download and run the [RStudio installer for Windows](https://www.rstudio.com/products/rstudio/download/#download). Note that if you have separate user and admin accounts, you should run the installers as administrator (right-click on .exe file and select “Run as administrator” instead of double-clicking). Otherwise problems may occur later, for example when installing R packages.

### Mac

Install R by downloading and running [this .pkg](http://cran.r-project.org/bin/macosx/R-latest.pkg) file from CRAN. Also, please download and run [the RStudio installer for Mac](https://www.rstudio.com/products/rstudio/download/#download)

### Linux

You can download the binary files for your distribution from CRAN. Or you can use your package manager (e.g. for Debian/Ubuntu run `sudo apt-get install r-base` and for Fedora run `sudo yum install R`). Also, please download and run the [RStudio installer](https://www.rstudio.com/products/rstudio/download/#download).

2) Install the R packages required for the course

Enter the following into the console prompt in RStudio
```
source("https://raw.githubusercontent.com/sheffield-bioinformatics-core/rnaseq-r-online/main/install_bioc_packages.R")
```

You can check that this worked by running

```
source("https://raw.githubusercontent.com/sheffield-bioinformatics-core/rnaseq-r-online/main/check_packages.R")

```

3) Download and unzip this file containing the data for the course

- [Link to Data](https://drive.google.com/file/d/178yZSaG1tTr3akeN0DQ2f1Pu2rMoJkBT/view?usp=sharing)


4) (Optional) Watch these short introductory videos

- [A gentle introduction to RNA-seq](https://youtu.be/tlf6wYJrwKY)
- [RNA-seq count normalisation explained](https://youtu.be/TTUrtCY2k-w)

## Instructors

- Dr. Mark Dunning, Bioinformatics Core Director
- Dr. Akshay Bhat, Cancer Bioinformatician
- Dr. Manoj Valluru, Bioinformatician

## Timetable (provisional)

- Session 1 Monday 22nd December 13:00  13:00 - 16:00
  + Importing RNA-seq counts into R
  + Quality assessment of raw counts
  + Checking sources of variation using PCA and clustering
  
- Session 2 Wednesday 4th December 13:00 - 16:00
  + Differential expression using DESeq2 to generate gene-lists
  + Manipulating and filtering gene-lists
  + Basic plotting of differential-expression results
  + More-advanced designs using DESeq2
  
- Session 3 Friday 6th December 13:00 - 16:00
  + Advanced plotting with heatmaps
  + Using Bioconductor resources to interrogate Gene Ontologies
  + Identifying over-represented and enriched gene sets
  
## Feedback




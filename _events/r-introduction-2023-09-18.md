---
layout: page
category: workshop
permalink: /training/r-introduction-2023-09-18
organizer: Sheffield Bioinformatics Core
title: Data Manipulation and Visualization
excerpt: "Data Manipulation and Visualization using the R programming language"
startDate: 2023-09-18
date: 2023-09-18
endDate: 2023-09-22
end-date: 2023-09-22
startTime: 13.00
from: "13:00"
endTime: 17.00
to: "16:00"
city: Sheffield, or online
postcode: S10 2HQ
country: United Kingdom
venue: University of Sheffield, or ONLINE
description: "As the data generated from high-throughput biological experiments increase in volume and become more complex, the ability to manipulate and visualise data is a highly-desirable skill in academia and industry. Whilst familiar tools such as Excel allow basic manipulations, they are often not scalable to larger datasets and are not ameanable to reproducible analysis. 
R is a highly-regarded, free, software environment for statistical analysis, with many useful features that promote and facilitate reproducible research."
keywords: bioinformatics, R, data analysis, data visualization, ggplot2, dplyr, online
scientific keywords: data science, data visualization, R, data manipulation
difficulty: beginner
contact: bioinformatics-core@sheffield.ac.uk
location: Bartolome House, Seminar Room EG03 or Online
speaker: Dr. Mark Dunning, Dr. Emily Chambers
---

## Dates

There are options for attending online and in-person. If you are based in Sheffield, we would strongly recommend attending in-person if possible.

- Monday September 18th 13:00 - 16:00 Bartolome House, Seminar Room EG03, or Online
- Tuesday September 19th, 09:00 - 12:00 Bartolome House, Seminar Room EG03 or Online
- Friday September 22nd 13:00, - 16:00 - Bartolome House, Seminar Room EG03 or Online

Please only sign-up to the course if you are available on these dates, or prepared to devote time to review any sessions that you miss

## Contact

web : [sbc.shef.ac.uk](https://sbc.shef.ac.uk)  
twitter: [SheffBioinfCore](https://twitter.com/SheffBioinfCore)  
email: [bioinformatics-core@sheffield.ac.uk](bioinformatics-core@sheffield.ac.uk)


# Registration Link

Please use [this link](https://onlineshop.shef.ac.uk/conferences-and-events/faculty-of-medicine-dentistry-and-health/medical-school) to register for the course


## Overview

As the data generated from high-throughput biological experiments increase in volume and become more complex, the ability to manipulate and visualise data is a highly-desirable skill in academia and industry. Whilst familiar tools such as Excel allow basic manipulations, they are often not scalable to larger datasets and are not ameanable to reproducible analysis. 

R is a highly-regarded, free, software environment for statistical analysis, with many useful features that promote and facilitate reproducible research.

In this course, we give an introduction to the R environment and explain how it can be used to import, manipulate and visualise tabular data. 

After the course you should feel confident to start exploring your own dataset using the materials and references provided. 

## Setup

These instructions are also described in a video:- [https://youtu.be/QIubJ8W8R4g](https://youtu.be/QIubJ8W8R4g)

1) First, install both R **and** RStudio for your operating system. 

### Windows

Install R by downloading and running [this .exe file](http://cran.r-project.org/bin/windows/base/release.htm) from CRAN. Also, please install the [RStudio IDE](http://www.rstudio.com/ide/download/desktop). Note that if you have separate user and admin accounts, you should run the installers as administrator (right-click on .exe file and select "Run as administrator" instead of double-clicking). Otherwise problems may occur later, for example when installing R packages.

### Mac

Install R by downloading and running one of the following pkg files depending on your model of Mac

- [Apple silicon (M1/M2) Macs](https://cran.r-project.org/bin/macosx/big-sur-arm64/base/R-4.3.1-arm64.pkg)
- [Older models](https://cran.r-project.org/bin/macosx/big-sur-x86_64/base/R-4.3.1-x86_64.pkg)

Also, please install the free [RStudio IDE](https://www.rstudio.com/products/rstudio/download/#download) 

### Linux

You can download the binary files for your distribution from CRAN. Or you can use your package manager (e.g. for Debian/Ubuntu run `sudo apt-get install r-base` and for Fedora run `sudo yum install R`). Also, please install free [the RStudio IDE](https://www.rstudio.com/products/rstudio/download/#download). 


  
2) Please download and extract (un-zip) this zip file into the directory on the computer that you wish to work in

- [https://github.com/sheffield-bioinformatics-core/r-online/raw/master/CourseData.zip](https://github.com/sheffield-bioinformatics-core/r-online/raw/master/CourseData.zip)

3) Type the following into the R console to install some extra R packages required for the workshop

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


4) Check your installation. You can check everything is installed by copying and pasting this into the R console

```
source("https://raw.githubusercontent.com/sheffield-bioinformatics-core/r-online/master/check_packages.R")

```

## Course Notes


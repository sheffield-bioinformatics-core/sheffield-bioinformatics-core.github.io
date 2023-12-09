---
layout: page
title: FAQ
excerpt: "Answers to common support questions"
---

# FAQ

On this page we will add questions that we are often asked by researchers learning Bioinformatics

## How can I upload large files to Galaxy?

Galaxy recommend uploading large files using FTP. Instructions and a video are provided on the following website. If uploading to the galaxy.eu server, make sure that you replace **usegalaxy.org** with **usegalaxy.eu** in the instructions below.

[https://galaxyproject.org/ftp-upload/](https://galaxyproject.org/ftp-upload/)

Installing an FTP client, such as [FileZilla](https://filezilla-project.org/) will help to transfer files.

------

## How can I analyse data from GEO in R / RStudio?

There is a package called `GEOquery` available through Bioconductor that will greatly help this process. It can be installed as follows.

```
install.packages("BiocManager")
BiocManager::install("GEOquery")
```

We have created a tutorial to go through a workflow to analyse data from GEO

[https://sbc.shef.ac.uk/geo_tutorial/tutorial.nb.html](https://sbc.shef.ac.uk/geo_tutorial/tutorial.nb.html)

Alternatively, GEO provide a GEO2R tool that provide the code for you

[https://www.ncbi.nlm.nih.gov/geo/geo2r/](https://www.ncbi.nlm.nih.gov/geo/geo2r/)

------

## How can I perform survival analysis?

The Winship Biostatistics and Bioinformatics Shared Resource (BBISR) of Emory University have developed a nice web interface for performing survival analysis

http://bbisr.shinyapps.winship.emory.edu/CASAS/

The web page is running R code under-the-hood using the [Shiny](https://shiny.rstudio.com/) R package. If you want to perform survival analysis in R, there is a brief explanation in our [GEO tutorial](https://sbc.shef.ac.uk/geo_tutorial/tutorial.nb.html#survival-analysis).

A much more comprehesive guide can be found here:-

- [https://www.emilyzabor.com/tutorials/survival_analysis_in_r_tutorial.html](https://www.emilyzabor.com/tutorials/survival_analysis_in_r_tutorial.html)


## Can I read data from Excel into R?

Yes, if you have `.xls` or `.xlsx` file they can be read into R. The recommended approach would be to save then as `.csv` files, and proceed as normal. Otherwise, the `readxl` package can be used

```
## do this the first time if you don't have the package
install.packages("readxl")
library(readxl)
data <- readxl("<YOUR_FILE_NAME_HERE>")
```

However, you may wish to consult this guide on data organisation to make sure your data are in a suitable form for analysis in R

[https://datacarpentry.org/spreadsheet-ecology-lesson/](https://datacarpentry.org/spreadsheet-ecology-lesson/)

------

## Is there a package to do .... in R?

Aside from google, the main places to look would be Bioconductor (for Biological data):-


[Bioconductor packages](http://bioconductor.org/packages/release/BiocViews.html#___Software)

or the main R repository at CRAN

[Browse R packages](https://www.r-pkg.org/)

------

## I get a `file not found` error when trying to read a file into R

R is having problems with the *file path* or *file name* that you specified.

1) check the file name to make sure there are no typos
2) check that the file exists in your current working directory. The working directory can be printed to screen using `getwd()`.

The recommended way to organise your files in RStudio is using *R projects*.

[https://support.rstudio.com/hc/en-us/articles/200526207-Using-Projects](https://support.rstudio.com/hc/en-us/articles/200526207-Using-Projects)

Any files that you want to analyse should be placed inside the project directory.

If you are still having problems, RStudio has an **Import Dataset** option through the file menu. This will read your file, and also print the R code that would be required.


------

## How do I make a heatmap from my differentially-expressed genes

There is a heatmap tool available through Galaxy, and here is a tutorial

https://galaxyproject.github.io/training-material/topics/transcriptomics/tutorials/rna-seq-viz-with-heatmap2/tutorial.html

The Degust tool can also make heatmaps

http://degust.erc.monash.edu/


In R, the `pheatmap` or `ComplexHeatmap` packages are recommended for their flexibility. You will need to filter your count matrix to contain rows for just your genes of interest.

A recent Bitesize Bioinformatics video from Babraham Bioinformatics explains the process

- https://www.youtube.com/watch?v=pTeTH9bz-_s&list=PLbiByRpDb_hP7b-I1GR4eEWCD2OqdZEg1&index=7

------


## Do you have any courses on ....?

Check our website for the courses that we currently run. All should have links to materials. We have now created a link to other resources online that you can check out

http://sbc.shef.ac.uk/training/
http://sbc.shef.ac.uk/training/other-materials

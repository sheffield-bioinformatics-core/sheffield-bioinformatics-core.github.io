---
layout: page
title: High Performance Computing (HPC) and Bioinformatics pipelines
---

The University of Sheffield HPC is centrally-managed and administered by the IT services and Research IT teams. Our recommendation is to use the *stanage* cluster launched in 2023. Please see these pages for how to get access to the HPC. 

- [Getting an account](https://docs.hpc.shef.ac.uk/en/latest/hpc/accounts.html)

The Sheffield Bioinformatics Core is able to advised on the usage of HPC for Bioinformatics applications and we have experience configuraing and running common pipelines (see below). The best way to request help is to schedule a code clinic via the Research Software Engineering (RSE) booking system. 

- [Request a code clinic](https://goo.gl/forms/5MVy0jM6xQhWlpmn1)

Bioinformatics Core staff monitor these requests and will be able to attend the clinic, along with members of Research-IT as required. 

# Configuring and running Bioinformatics pipelines on the HPC

Out strong recommendation for running Bioinformatics pipelines is to make use of the nf-core set of pipelines written using nextflow. If you are running a standard analysis (such as RNA-seq), there is no need to create your own bespoke pipeline from scratch. The pipelines available through nf-core have been created and maintained by the research community and can produce a consistent and reproducible set of outputs. The software included as part of the RNA-seq pipeline is shown below.

![](/assets/images/nf-core-rnaseq_metro_map_grey.png)

One advantage of using nf-core is that you do not need install all the individual software that comprise the pipeline separately. You also don't need to worry about formatting the results of individual steps so that they are compatible with the inputs expected later on. The pipeline will take care of managing the scheduling of jobs and resuming after a failed run, and make full use of the HPC resource available so that you get your analysis results returned as efficiently as possible.



- [Documentation on configuring nf-core](https://sbc.shef.ac.uk/nf-core-user-docs/)
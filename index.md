# Introduction to RNA-seq data analysis 
### 22nd - 24th March 2021
#### Taught remotely
#### Bioinformatics Training, Craik-Marshall Building, Downing Site, University of Cambridge

![](images/CRUK_Cambridge_Major_Centre_logo.jpg)

## Instructors

* Abigail Edwards - Bioinformatics Core, Cancer Research UK Cambridge Institute
* Ashley D Sawle - Bioinformatics Core, Cancer Research UK Cambridge Institute
* Chandra Chilamakuri - Bioinformatics Core, Cancer Research UK Cambridge Institute
* Dominique-Laurent Couturier - Bioinformatics Core, Cancer Research UK Cambridge Institute 
* Jon Price - Miska Group, Gurdon Institute, Cambridge
* Stephane Ballereau - Bioinformatics Core, Cancer Research UK Cambridge Institute
* Zeynep Kalender Atak - Miller Group, Cancer Research UK Cambridge Institute

## Outline

In this workshop, you will be learning how to analyse RNA-seq data. This will
include read alignment, quality control, quantification against a reference,
reading the count data into R, performing differential expression analysis, and
gene set testing, with a focus on the DESeq2 analysis workflow. You will learn
how to generate common plots for analysis and visualisation of gene expression
data, such as boxplots and heatmaps. 

This workshop is aimed at biologists interested in learning how to perform
differential expression analysis of RNA-seq data. 

Whilst we have run this course for several years, we are still learning how to
teach it remotely.  Please bear with us if there are any technical hitches, and
be aware that timings for different sections laid out in the schedule below may
not be adhered to. There may be some necessity to make adjusments to the course
as we go.

> ## Prerequisites
>
> __**Some basic experience of using a UNIX/LINUX command line is assumed**__
> 
> __**Some R knowledge is assumed and essential. Without it, you
> will struggle on this course.**__ 
> If you are not familiar with the R statistical programming language we
> strongly encourage you to work through an introductory R course before
> attempting these materials.
> We recommend our [Introduction to R course](https://bioinformatics-core-shared-training.github.io/r-intro/)

## Shared Google Document

This 
<a href="https://docs.google.com/document/d/1IVA-m22xtWxYusdG-giIFAk0AzC9F2E6k8I-YfBRoVM" target="_blank">Google Document</a> contains useful information and links.. 

Please use it to post any questions you have during the course.

The trainers will be monitoring the document and will answer questions as quickly
as they can.

## Introduce Yourself

There is another Google Doc 
<a href="https://docs.google.com/document/d/13HGBzBK_5ePGVEpo6oMD-p2kTuUIb832ZQlp0tieluU/edit#" target="_blank">here</a>. 
Please write a couple sentences here to introduce yourself to the class, tell
us a bit about your background and what you hope to get out of this course.  If
you are a student or staff at the University of Cambridge, tell us which
Department you are in.


## Course etiquette

As this course is being taught online and there are a large number of participants,
we will all need to follow a [few simple rules](https://docs.google.com/presentation/d/e/2PACX-1vQv9nTlsdRC9iZJU138tLL1jrwNoryp8P-FnXxb_ugOOWjbav4QHTLYLLZj2KK4kTO0_3x3VlzSdrUu/pub?start=false&loop=false&delayms=3000) to ensure things run as smoothly as possible:

1. Please mute your microphone

2. To get help from a tutor, please click the "Raise Hand" button in Zoom:

    ![](images/raise_hand.png)
   
   This can be found by clicking on the 'Participants' button. A tutor will
   then contact you in the chat. If necessary, you and the tutor can be moved
   to a breakout room where you can discuss your issue in more detail.

3. Please ask any general question by typing it into the Google Doc mentioned above

4. During practicals, when you are done, please press the green "Yes" button: 
    
    ![](images/yes_button.png)

   This way we will know when we can move on.

## Timetable

**We are still learning how to teach this course remotely, all times here should be
regarded as aspirations**

### Day 1

9:30 - 9:45 - Welcome! <!-- Ash -->

9:45 - 10:15 - [Introduction to RNAseq 
Methods](Markdowns/01_Introduction_to_RNAseq_Methods.html) - Jon Price

10:15 - 11:15 [Raw read file format and 
QC](Markdowns/02_FastQC_introduction.html)  - Jon Price  
    - [Practical](Markdowns/02_FastQC_practical.html)  
    <!-- - [Practical solutions](Markdowns/02_FastQC_practical.Solutions.html) -->

11:15 - 12:45 [Short read alignment with 
HISAT2](Markdowns/03_Alignment_with_HISAT2_introduction.html) - Zeynep Kalender Atak  
    - [Practical](Markdowns/03_Alignment_with_HISAT2_practical.html)  
   <!-- - [Practical solutions](Markdowns/03_Alignment_with_HISAT2_practical.Solutions.html)  -->

12:45 - 13:45 Lunch

13:45 - 15:30 [QC of alignment](Markdowns/04_QC_of_aligned_reads_introduction.html) - Zeynep Kalender Atak  
    - [Practical](Markdowns/04_QC_of_aligned_reads_practical.html)  
   <!-- - [Practical solutions](Markdowns/04_QC_of_aligned_reads_practical.Solutions.html) -->

15:30 - 17:00 [Quantification of Gene Expression with Salmon](Markdowns/05_Quantification_with_Salmon_introduction.html) - Ashley Sawle  
    - [Practical](Markdowns/05_Quantification_with_Salmon_practical.html)  
   <!-- - [Practical solutions](Markdowns/05_Quantification_with_Salmon_practical.Solutions.html) -->

### Day 2

9:30 - 10:15  [Introduction to RNAseq Analysis in 
R](Markdowns/06_Introduction_to_RNAseq_Analysis_in_R.html) - Jon Price  

10:15 - 12:30 - [RNA-seq 
Pre-processing](Markdowns/07_Data_Exploration.html) - Chandra Chilamakuri   
   <!-- - [Practical solutions](Markdowns/07_Data_Exploration.Solutions.html) -->

12:30 - 13:30 Lunch

13:30 - 15:30 [Statistical Analysis of Bulk RNAseq Data]() - Dominique-Laurent  
Couturier        
    - [Practical (html)]() [(rmd)]()  

15:30 - 17:00 [Experimental Design of Bulk RNAseq studies]() - Abigail Edwards    
    - [Practical]()    

### Day 3

9:30 - 12:15 - [Differential Expression for
RNA-seq](Markdowns/10_DE_analysis_with_DESeq2.html) - Ashley Sawle   
   <!-- - [practical solutions](Markdowns/10_DE_analysis_with_DESeq2.Solutions.html)   -->

12:15 - 13:15 Lunch

13:15 - 15:30 [Annotation and Visualisation of RNA-seq
results]() - Abigail Edwards    
   <!-- - [practical solutions]() -->

15:30 - 17:00 [Gene-set testing]() - Stephane Ballereau    
    - [slides](Markdowns/12_Gene_set_testing_introduction.html)
   <!-- - [practical solutions]() -->

<!-- Goodbye: Ash -->

## Source Materials for Practicals

The lecture slides and other source materials, including R code and 
practical solutions, can be found in the course's [Github 
repository](https://github.com/bioinformatics-core-shared-training/Bulk_RNAseq_Course_2021)

## Extended materials

The [Extended Materials](Extended_index.md) contain extensions to some of the
sessions and additional materials, including instruction on downloading and
processing the raw data for this course, a link to an excellent R course, and
where to get further help after the course.

## Additional Resources

* [Bioconductor for relevant R packages](https://bioconductor.org/)
* [DESeq2 Vignette](https://bioconductor.org/packages/release/bioc/vignettes/DESeq2/inst/doc/DESeq2.html)  
* [RNAseq Workflow](http://master.bioconductor.org/packages/release/workflows/vignettes/rnaseqGene/inst/doc/rnaseqGene.html)  
* [RStudio CheatSheets](https://rstudio.com/resources/cheatsheets/)

## Acknowledgements

This course is based on the course [RNAseq analysis in
R](http://combine-australia.github.io/2016-05-11-RNAseq/) prepared by [Combine
Australia](https://combine.org.au/) and delivered on May 11/12th 2016 in
Carlton. We are extremely grateful to the authors for making their materials
available; Maria Doyle, Belinda Phipson, Matt Ritchie, Anna Trigos, Harriet
Dashnow, Charity Law.

![](images/combine_banner_small.png)

The materials have been rewritten/modified/corrected/updated by various
contributors over the past 5 years including:

Abigail Edwards
Ashley D Sawle
Chandra Chilamakuri
Dominique-Laurent Couturier
Guillermo Parada González
Jon Price
Mark Dunning
Mark Fernandes
Oscar Rueda
Sankari Nagarajan
Stephane Ballereau
Zeynep Kalender Atak

Apologies if we have missed anyone!

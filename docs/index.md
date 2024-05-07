<center>
# Analysis of single cell RNA-seq data
</center>

<center>
![image](./theme_images/theme-image.png){width="300"}
</center>


!!! calendar-days "Episodes"

    1. [Alignment and feature counting with Cell Ranger](./episodes/1.md)
    1. [QC and Exploratory Analysis](./episodes/2.md)
    1. [Normalisation](./episodes/3.md)
    1. [sctransform: Variance Stabilising Transformation](./episodes/4.md)
    1. [Feature Selection and Dimensionality Reduction](./episodes/5.md)
    1. [Batch correction and data set integration](./episodes/6.md)
    1. [Clustering](./episodes/7.md)
    1. [Identification of cluster marker genes](./episodes/8.md)
    1. [Differential expression analysis](./episodes/9.1.md)
    1. [ Differential Abundance](./episodes/9.2.md)

!!! check-to-slot "Prerequisites"
 
    - [x] Inermediate level knowledge on R (programming language)
    - [x] Familiarity with terminal and basic linux commands
    - [x] Some knowledge on shell environment variables and `for` loops
    - [x] Ability to use a terminal based text editor such as `nano` 
        * [ ] This is not much of an issue as we are using JupyterHub which has a more friendlier text editor.   
    - [x] Intermediate level knowledge on Molecular Biology and Genetics

    **Recommended but not required**

    - [ ] Attend [Genomics Data Carpentry](https://datacarpentry.org/genomics-workshop/),  [RNA-Seq Data Analysis](https://genomicsaotearoa.github.io/RNA-seq-workshop/), [Introduction to R](https://genomicsaotearoa.github.io/Introduction-to-R/) and/or [Intermediate R](https://genomicsaotearoa.github.io/Intermediate-R/)

<br>




!!! database "Data set"

    - Data used in this workshop is based on [CaronBourque2020](https://www.nature.com/articles/s41598-020-64929-x_) relating to pediatric leukemia, with four sample types, including:
        - pediatric Bone Marrow Mononuclear Cells (PBMMCs)
        - three tumour types: ETV6-RUNX1, HHD, PRE-T

!!! tags "Attribution notice"

    * Material used in this workshop is based on folloowing repositories

        - Introduction to single-cell RNA-seq data analysis - University of Cambridge https://bioinformatics-core-shared-training.github.io/SingleCell_RNASeq_Jan23/
        - Analysis of single cell RNA-seq data - Welcome Sanger Institute https://www.singlecellcourse.org/


!!! book-atlas "References"

    - https://genomebiology.biomedcentral.com/articles/10.1186/s13059-016-0947-7
    - https://www.nature.com/articles/nbt.4091
    - https://arxiv.org/abs/physics/0512106
    - https://www.nature.com/articles/s41598-019-41695-z
    - https://www.nature.com/articles/s41598-019-41695-z#Fig3
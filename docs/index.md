<center>
# Analysis of single cell RNA-seq data
</center>


!!! database "Data set"

    - Data used in this workshop is based on [CaronBourque2020](https://www.nature.com/articles/s41598-020-64929-x_) relating to pediatric leukemia, with four sample types, including:
        - pediatric Bone Marrow Mononuclear Cells (PBMMCs)
        - three tumour types: ETV6-RUNX1, HHD, PRE-T

    

<center>
```mermaid
flowchart TD
    id1["Sequencing QC"] --> id2["Read alingment, Feature Counting, Cell calling"] --> id3["QC"] --> id4["Count normalisation"] --> id5["Feature selection"] --> id6["Dimensionality reduction"] --> id7["Data set integration"] --> id8["Clustering"] --> id9["Cluster marker genes"] --> id10["DE between conditions"] --> id11["Differential abundance between conditions"]
```
</center>
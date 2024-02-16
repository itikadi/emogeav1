# EMOGEA
**EMOGEA (Error Modeled Gene Expression Analysis )** is a computational method for the analysis of RNA-Seq gene expression data. It is suitable for the analysis of data 
deriving from three of the most common experimental design strategies in -omics research: Binary comparisons(case/control), Temporal (ordinal) measurements, and single-cell
RNA-seq (scRNAseq) for trajectory inference.

Technical description of the method and extended usage examples will soon be available upon completion of the academic peer-review process.

The current **implementation** of EMOGEA is in R (this repository).
The **output** from any of the implementations can be explored either in R or Python.

### Tutorials

To use **R** for the whole analysis, there is the main tutorial:
> The tutorials in R include a more detailed explanation of the workflow and source code.

  - [Introduction and setup](https://github.com/itikadi/emogeav1/blob/master/vignettes/EMOGEA.md)
  
To install the package, type the following in the R console: 
```R
devtools::install_github("itikadi/emogeav1", build_vignettes = TRUE)
```

Check the vignette to see how to use the package:
```R
browseVignettes("EMOGEA")
```

It is highly recommended to use the Microsoft R Open distribution to use the package (R >= 4.0.0).

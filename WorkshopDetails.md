# Summary

I make the package requirements as below. 
One of them as a dependency on `rgl` which has a whole lot of system dependencies.
I tested on my system & fixed it with OpenGL via a shortcut:

```
sudo apt install libglu1-mesa-dev freeglut3-dev mesa-common-dev
```

```
pkgs <- c(
    "cluster", "survival", "randomForest", "missForest", "glmnet", "Rcpp", 
    "foreach", "itertools", "iterators", "Matrix", "devtools", "impute",
    "WangLab-MSSM/DreamAI/Code", "PengyiYang/PhosR", "directPA", "ClueR", 
    "Bioconductor/BiocIntro", "usethis", "roxygen2", "devtools", "goodpractice",
    "BiocCheck", "ExperimentHub", "CATALYST", "diffcyt", "sa-lee/fluentGenomics", 
    "workflowr"
    )
BiocManager::install(pkgs)
```

# Thursday

## Pei Wang: Imputation and data quality control for proteomics data

- Package Requirements:
    - "cluster", "survival", "randomForest", "missForest", "glmnet", "Rcpp", "foreach", "itertools", "iterators", "Matrix", "devtools", "impute"
    - https://github.com/WangLab-MSSM/DreamAI/Code
- Data Requirements:
    - TBC

## Pengyi Yang: Computational analysis for biological discovery from (phospho)proteomic data

- Package Requirements:
    - https://github.com/PengyiYang/PhosR
    - CRAN: directPA, ClueR
- Data Requirements:
    - Pengyi's code links to these directly on dropbox, which makes me a little nervous
    - https://github.com/Bioconductor/BiocAsia/blob/master/workshops/PhosR_workshop/ESC_Phospho%20(STY)Sites.txt
    - https://github.com/Bioconductor/BiocAsia/blob/master/workshops/PhosR_workshop/phosphoESC_cluster.RData
- Course Material:
    - https://bioconductor.github.io/BiocAsia/workshops/PhosR_workshop/index.html
    
## Martin Morgan: R and Bioconductor for Genomic Analysis

- Package Requirements
    - BiocIntro

## Peter Hickey & Saskia Freytag: Building a Bioconductor package

- Package Requirements:
    - usethis, roxygen2, devtools, goodpractice, BiocCheck
- Data Requirements:
    - None.
    
# Friday

## Helena Crowell: Differential discovery in high-dimensional cytometry data

- Package Requirements:
    - ExperimentHub, CATALYST, diffcyt
- Data Requirements
    - It looks like her material downloads on the fly. The main material is here: https://bioconductor.org/packages/release/bioc/vignettes/CATALYST/inst/doc/differential_analysis.html
    
## Stuart Lee: Fluent genomics: a plyranges and tximeta case-study

- Package Requirements:
    - https://github.com/sa-lee/fluentGenomics
- He's done his as a package, so I tihnk loading that will cover everything. His session is here: https://sa-lee.github.io/fluentGenomics/articles/fluentGenomics.html

## Dave Tang: Reproducible bioinformatics

- Dave wants to run everything locally, but I think having a contingency plan is wise:
- Package Requirements:
    - workflowr
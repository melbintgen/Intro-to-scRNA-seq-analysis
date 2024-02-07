# Introduction to scRNA-seq analysis
**Authors: Xiaochen Zhang, Jiadong Mao, Kim-Anh L&#234; Cao, Saritha Kodikara, Daniel Rawlinson**

| Audience      | Prerequisites | Duration    |
| ------------- | ------------- | ----------- |
| Anyone    |Install R & R Studio|~ 10 min    |
| Anyone    |Install Seurat and SeuratData|~ 30 min    |


### Description

This repository includes material for a hands-on workshop 'Introduction to scRNA-seq analysis'. We show you how to use Seurat to analysis your own scRNA-seq data.

### Installation Requirements

Install R first, then RStudio. Download the most recent version of R and RStudio using the links below:
- [R](https://cran.r-project.org/)
- [RStudio](https://posit.co/download/rstudio-desktop/#download)

Install the R packages (you will need R version > 4.0,  preferably 4.2 to avoid most issues with the installation).
Type the R command lines:
``` 
install.packages('Seurat')
if (!requireNamespace("remotes", quietly = TRUE)) {
  install.packages("remotes")
}
remotes::install_github("satijalab/seurat-data", quiet = TRUE)

# then test if packages have been installed
library(Seurat) 
library(SeuratData)
```

More details on the packages:
- [Seurat 5](https://satijalab.org/seurat/articles/install_v5.html)
- [Seurat-data](https://github.com/satijalab/seurat-data)

### Material

[Click here](https://melbintgen.github.io/Intro-to-scRNA-seq-analysis/scRNAseq_workshop.html) to access the HTML workshop document.

### Data
Datasets are from the SeuratData package.

-----

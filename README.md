# `genomeVerse`: Framework for Genomic data Processing and Analysis

`genomeVerse` is an umbrella package for genomic data processing and analysis with the `genomeVerse` ecosystem of R packages developed in the department of [Epidemiology & Biostatistics at Memorial Sloan Kettering Cancer Center](https://www.mskcc.org/departments/epidemiology-biostatistics).

The `library(genomeVerse)` loads the following packages:

  - [**gnomeR**](https://axelitomartin.github.io/gnomeR/) for data downloading and processing from [cBioPortal](https://www.cbioportal.org/) a genomic tool distributed by Memorial Sloan Kettering Cancer Center. The source code can be found on [github](https://github.com/AxelitoMartin/gnomeR).
  - [**panelmap**](https://arorarshi.github.io/panelmap/) creates panels for summarizing binary data, categorical data (more than 2 categories) and continuous data for known groups. `panelmap` is a visual aid to understand associations and trends in data instead from tedious tables and trying to infer multiple plots. The source code can be found on [github](https://github.com/arorarshi/panelmap).
  - [**survClust**](https://github.com/arorarshi/survClust) an outcome weighted supervised clustering algorithm, designed to classify patients according to their molecular as well as time-event or end point of interest. We present classification of samples on molecular data supervised by time-event data like Overall Survival (OS), Progression Free Survival etc.
  - [**OncoCast**](https://github.com/AxelitoMartin/OncoCast) an ensemble learner for survival prediction and stratification with improved interface. Allows for multiple machine learning to be applied to a high-dimensional data set with survival outcome (including left-truncated data).
  - [**iClusterPlus**](https://bioconductor.org/packages/release/bioc/html/ensembldb.html) Programs iClusterPlus and iClusterBayes are developed for integrative clustering analysis of multi-type genomic data, which are significant extension of the iCluster program (Shen, Olshen and Ladanyi, 2009). Multi-type genomic data arise from the experiments where biological samples (e.g., tumor samples) are analyzed by multiple techniques, for instance, array comparative genomic hybridization (aCGH), gene expression microarray, RNA-seq and DNA-seq, and so on. Examples of these data can be obtained from the Cancer Genome Atlas (TCGA) (http://cancergenome.nih.gov/).

# Installation

``` r
# install.packages("devtools")
devtools::install_github("AxelitoMartin/genomeVerse")
```


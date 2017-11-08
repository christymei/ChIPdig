# ChIPdig
user-friendly tool for mining multi-sample ChIP-seq data

ChIPdig is an R Shiny app designed to allow experimental biologists with little computational skills to analyze ChIP-seq data composed of multiple samples / conditions.
Tasks such as mapping reads to a reference genome, peak calling, differential enrichment analysis, annotation of genomic intervals, and visualization of coverage by heatmaps and metaplots can be performed.

To be able to use the app, clone this repository to your computer and install the necessary packages by typing in R studio console:

* `install.packages("shiny")`
* `install.packages("shinyFiles")`
* `install.packages("ggplot2")`
* `install.packages("ggsignif")`
* `install.packages("reshape2")`
* `install.packages("valr")`
* `install.packages("circlize")`
* `source("https://bioconductor.org/biocLite.R")`
* `biocLite("BSgenome")`
* `biocLite("QuasR")`
* `biocLite("csaw")`
* `biocLite("edgeR")`
* `biocLite("GenomicAlignments")`
* `biocLite("BayesPeak")`
* `biocLite("ChIPseeker")`
* `biocLite("GenomicFeatures")`
* `biocLite("EnrichedHeatmap")`

Please contact me for questions and suggestions for improvement: rmesse@bu.edu.

# This repository contains R scripts for analyzing 10x Genomics single-cell RNA-seq (scRNA-seq) data generated from EEC knockout project

## Data

The raw sequencing data associated with this analysis are publicly available through the Gene Expression Omnibus (GEO) database:

GEO accession: GSE295240 [https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE295240]

GEO accession: GSEGSE295239 [https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE295239]


## Detail

The R scripts contain the analysis workflow for the scRNA-seq dataset, including data processing, quality control, downstream analysis, and visualization.

## Usage

Please ensure that the required version of R and packages are installed before running the scripts. Scripts should generally be run in the order specified by the analysis workflow.

### Software Requirements

The analysis was performed using **R version 4.2.2**.

**R Packages**

| Package | Version |
|---|---|
| `tidyverse` | 1.3.2 |
| `Seurat` | 4.3.0 |
| `SeuratObject` | 4.1.3 |
| `hdf5r` | 1.3.8 |
| `SeuratDisk` | 0.0.0.9021 |
| `dplyr` | 1.1.4 |
| `Matrix` | 1.5-3 |
| `ggplot2` | 3.5.1 |
| `sctransform` | 0.3.5 |
| `rgl` | 1.1.3 |
| `cowplot` | 1.1.3 |
| `patchwork` | 1.3.0 |
| `fields` | 15.2 |
| `DoubletFinder` | 2.0.4 |
| `EnhancedVolcano` | 1.16.0 |


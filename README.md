# RGS_BreastCancer_Analysis

This repository contains the analysis code for the study: "Comprehensive analysis of RGS family expression and prognostic value in human breast cancer".

## Overview
- Bioinformatics analysis of RGS family genes in breast cancer using TCGA, GEO datasets, CCLE cell lines, and tools like limma, ggplot2, pheatmap.
- Focus: Differential expression, prognostic value, immune infiltration, pathway enrichment, and drug sensitivity.

## Files
- `GEO_Analysis.R`: Scripts for GEO dataset validation (e.g., differential expression with limma).
- `CCLE_CellLine_Analysis.R`: Z-score normalization and clustering for breast cancer cell lines.
- `Enrichment_Analysis.R`: GO/KEGG pathway enrichment using Enrichr and ggplot2.

## Requirements
- R version 4.2.1 or higher.
- Packages: limma, dplyr, pheatmap, ggplot2, readr, stringr, org.Hs.eg.db, RColorBrewer.

## Usage
1. Install required packages: `install.packages(c("limma", "dplyr", ...))`
2. Run scripts: `source("GEO_Analysis.R")`

Contact: mirzaeizohreh8@gmail.com for questions.

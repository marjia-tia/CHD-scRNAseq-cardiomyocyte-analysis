# Single-Cell Transcriptomic Analysis of Cardiomyocyte Maturation Arrest in Congenital Heart Disease (PAIVS)

## Overview
This project investigates cardiomyocyte cell state dysregulation in Pulmonary Atresia with Intact Ventricular Septum (PAIVS) using single-cell RNA sequencing analysis.

## Key Finding
PAIVS cardiomyocytes show a maturation arrest — 80.22% remain in immature states compared to 62.59% in healthy controls, suggesting CHD in PAIVS is driven by failed cardiomyocyte maturation rather than simple cell damage.

## Dataset
- Source: GEO GSE157157
- 11,263 human iPSC-derived cardiomyocytes
- 6 Control + 6 PAIVS patient samples

## Pipeline
1. Data loading and quality control
2. Normalization and highly variable gene selection
3. PCA dimensionality reduction
4. UMAP visualization and Leiden clustering
5. Cell state annotation
6. Differential expression analysis

## Tools
- Python 3.11
- Scanpy 1.11.5
- AnnData 0.10.7

## Author
Marjia Islam Tia

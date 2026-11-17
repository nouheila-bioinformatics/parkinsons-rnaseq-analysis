# Parkinson's Disease RNA-seq Analysis

## Project Overview

This project focuses on the analysis of RNA sequencing (RNA-seq) data to investigate gene expression differences between individuals with Parkinson's disease and neurologically normal controls.

The study uses publicly available human post-mortem brain tissue data (Brodmann Area 9) and applies bioinformatics tools and statistical methods to explore differentially expressed genes and biological pathways.

## Project Objectives

- Analyze RNA-seq sequencing data.
- Perform quality control and preprocessing of sequencing reads.
- Align sequencing reads to the reference genome.
- Quantify gene expression.
- Identify differentially expressed genes.
- Explore enriched biological processes and pathways.
- Visualize gene expression and enrichment results.

## Tools and Technologies

### Data Processing and Quality Control
- SRA Toolkit (Fasterq-dump)
- FastQC
- Trimmomatic
- Galaxy

### Read Alignment and Quantification
- HISAT2
- featureCounts

### Data Analysis and Visualization
- R
- edgeR
- DESeq2
- Python
- clusterProfiler

### Galaxy Data Management
- Collapse Collection
- Column Join

## Analysis Workflow

1. **Data Retrieval:** Download RNA-seq sequencing data from the SRA database using Fasterq-dump.
2. **Quality Control:** Assess sequencing read quality using FastQC.
3. **Read Preprocessing:** Remove low-quality reads and adapter sequences using Trimmomatic.
4. **Read Alignment:** Map sequencing reads to the reference genome using HISAT2.
5. **Gene Quantification:** Count aligned reads using featureCounts.
6. **Differential Expression Analysis:** Identify differentially expressed genes using edgeR.
7. **Functional Enrichment:** Explore Gene Ontology (GO) terms and KEGG pathways using clusterProfiler.
8. **Visualization:** Generate plots to present the analysis results.

## Results and Visualizations

The repository includes the following visualizations:

- **Volcano Plot:** Displays differential gene expression patterns.
- **GO Dotplot:** Shows enriched Gene Ontology terms.
- **KEGG Dotplot:** Illustrates enriched biological pathways.

## Project Status

Academic bioinformatics project. Results, figures, and documentation are being organized and reviewed.

## Author

Bioinformatics Student


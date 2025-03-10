# RP1SkinAgeing_scRNA-Prot

# Research Project 1: Characterizing Skin Ageing Mechanisms through Multi-Omics Approaches Using scRNA-seq and Proteomics Data
### Objective:
The objective of this research project is to analyze existing scRNA-seq and proteomics datasets to derive novel insights by integrating these two modalities. The project focuses on skin ageing mechanisms using both **single-cell RNA sequencing (scRNA-seq)** and **proteomics data**.

### Project Tasks:
1. **Data Analysis**:
    - Analyze scRNA-seq data using the **Yascp pipeline** (GitHub repository: [wtsi-hgi/yascp](https://github.com/wtsi-hgi/yascp)).
    - Analyze proteomics data from skin samples (DIA mass spectrometry).
    - Integrate the two datasets to derive meaningful insights about skin ageing mechanisms.

2. **Key Areas of Focus**:
    - **Single-cell RNA-seq (scRNA-seq)**: Identifying cell type-specific gene expression patterns, protein modifications, and potential biomarkers linked to ageing.
    - **Proteomics**: Identifying protein modifications associated with ageing, especially in extracellular matrix and structural proteins.

### CSF3 Resources (HPC For Project) :
- **CSF3 Support Email**: [its-ri-team@manchester.ac.uk](mailto:its-ri-team@manchester.ac.uk)
- **CSF3 Documentation**: [Getting Started with CSF3](https://ri.itservices.manchester.ac.uk/csf3/getting-started/user-accounts/)
  
---

## Project Outline

### Skin Ageing Mechanisms:
Skin ageing involves cellular and molecular changes that affect skin structure, resilience, and function. This project aims to provide a comprehensive, multi-omics perspective by combining **scRNA-seq** data and **proteomics data** to uncover gene regulatory networks and protein modifications linked to ageing in human skin.

### scRNA-seq:
- **Dataset**: A dataset from the study “A Single-Cell Transcriptomic Atlas of Human Skin Aging” has been processed through the **Yascp pipeline**.
- **Donor Samples**: Data includes samples from individuals of various age groups, with **quantification matrices** (h5ad files) available for analysis.
- **Annotations**: Four different **CellTypist annotation models** were run on the dataset. The most relevant model for this analysis is **Adult_Human_Skin**.
    - **Key cell types**: Keratinocyte subtypes, Immune cells, Melanocytes, Pericytes, Endothelial cells, Schwann cells, and Dendritic cells.

### Proteomics:
- **Dataset**: Data from the study **“Quantitative proteomics analysis of young and elderly skin with DIA mass spectrometry”**.
- **Processing**: The raw proteomics data will be processed using either **Nextflow** or an alternative pipeline.
- **Analysis**: Differential expression analysis of proteins, focusing on those involved in skin ageing, especially in the extracellular matrix.

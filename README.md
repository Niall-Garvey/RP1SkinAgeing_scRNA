# RP1SkinAgeing_scRNA

# Research Project 1 - Mapping Skin Ageing: An scRNA-seq Analysis of Cell Type-Specific Changes in Human Eyelid Across Age Groups

### Objective:
The objective of this research project is to analyze an existing scRNA-seq dataset from this Human skin cell atlas dataset - https://ngdc.cncb.ac.cn/aging/landscape?project=Human_Skin, in this case human eyelid from 9 donors aged 18-76 years old. The project focuses on skin ageing changes using  **single-cell RNA sequencing (scRNA-seq)** data and mapping these age-related changes on skin cell subtype variation and function via edgeR Differential expression and gene enrichment (GO) analysis to derive novel insights.

### Project Tasks:
1. **Data Analysis**:
    - Analyze scRNA-seq data using the **Yascp pipeline** (GitHub repository: [wtsi-hgi/yascp](https://github.com/wtsi-hgi/yascp)).

2. **Key Areas of Focus**:
    - **Single-cell RNA-seq (scRNA-seq)**: Identifying cell type-specific gene expression patterns and potential biomarkers linked to ageing.

### CSF3 Resources (HPC For Project) :
- **CSF3 Support Email**: [its-ri-team@manchester.ac.uk](mailto:its-ri-team@manchester.ac.uk)
- **CSF3 Documentation**: [Getting Started with CSF3](https://ri.itservices.manchester.ac.uk/csf3/getting-started/user-accounts/)
  
---

## Project Outline

### Skin Ageing Mechanisms:
Skin ageing involves cellular and molecular changes that affect skin structure, resilience, and function. This project aims to analyse **scRNA-seq** data to map gene function and skin cell subtype variations linked to ageing in human eyelid.

### scRNA-seq:
- **Dataset**: A dataset from the study “A Single-Cell Transcriptomic Atlas of Human Skin Aging” has been processed through the **Yascp pipeline**.
- **Donor Samples**: Data includes samples from individuals of various age groups, with **quantification matrices** (h5ad files) available for analysis.
- **Annotations**: Four different **CellTypist annotation models** were run on the dataset. The most relevant model for this analysis is **Adult_Human_Skin**.
    - **Key cell types**: Keratinocyte subtypes, Immune cells, Melanocytes, Pericytes, Endothelial cells, Fibroblasts and Dendritic cells.


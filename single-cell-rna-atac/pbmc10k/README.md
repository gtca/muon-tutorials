# Single-cell RNA-seq and ATAC-seq integration

Information on joint gene expression and open chromatin profiling [can be found here](https://www.10xgenomics.com/products/single-cell-multiome-atac-plus-gene-expression/).

Data processing and analysis workflow is split into multiple chapters.

1. [Gene Expression Processing](1-Gene-Expression-Processing.ipynb). This notebook largely follows [this scanpy tutorial](https://scanpy-tutorials.readthedocs.io/en/latest/pbmc3k.html) on processing and clustering PBMCs. 

1. [Peaks Processing](2-Chromatin-Accessibility-Processing.ipynb). While following the flow of the previous chapter, it introduces ATAC-related functionality for data processing and visualisation.

1. [Multimodal Omics Data Integration](3-Multimodal-Omics-Data-Integration.ipynb). This notebook demonstrates how multiple modalities can be combined in a single Python workflow and how multi-omics methods such as [multi-omics factor analysis (MOFA)](https://github.com/bioFAM/MOFA2) can be applied for data analysis and interpretation.

There are also notebooks showcasing specific details and alternative processing steps.

- [Gene Expression Processing using Pearson residuals](1.1-Gene-Expression-Processing-with-Pearson-Residuals.ipynb) shows how normalization strategy presented by [Lause et al.](https://www.biorxiv.org/content/10.1101/2020.12.01.405886) can be used when working with RNA counts.

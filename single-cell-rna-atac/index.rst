Single-cell RNA-seq and ATAC-seq integration in Python
======================================================

Information on joint gene expression and open chromatin profiling `can be found here <https://www.10xgenomics.com/products/single-cell-multiome-atac-plus-gene-expression/>`_.

Different datasets are covered:

- 10k peripheral blood mononuclear cells (PBMCs) (data by 10x Genomics can be found `here <https://support.10xgenomics.com/single-cell-multiome-atac-gex/datasets/1.0.0/pbmc_granulocyte_sorted_10k>`_):

	
	1. `gene expression processing notebooks <pbmc10k/1-Gene-Expression-Processing.html>`_ — largely follows `this scanpy tutorial <https://scanpy-tutorials.readthedocs.io/en/latest/pbmc3k.html>`_ on processing and clustering PBMCs;

	2. `peaks processing notebook <pbmc10k/2-Chromatin-Accessibility-Processing.html>`_ introduces ATAC-related functionality for data processing and visualisation,

	3. `multimodal omics data integration notebook <pbmc10k/3-Multimodal-Omics-Data-Integration.html>`_ demonstrates how multiple modalities can be combined in a single Python workflow and how multi-omics methods such as `multi-omics factor analysis (MOFA) <https://biofam.github.io/MOFA2/>`_ can be applied for data analysis and interpretation.


.. toctree::
   :hidden:
   :maxdepth: 3

   pbmc10k/1-Gene-Expression-Processing.ipynb
   pbmc10k/2-Chromatin-Accessibility-Processing.ipynb
   pbmc10k/3-Multimodal-Omics-Data-Integration.ipynb


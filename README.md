# preliminaryMPALworkflow
current s/w for MPAL network set-up, data processing, analysis, and visualization

MPALprogram.ipynb -- This s/w can be used to personalize and perform PageRank on a network of scRNA-seq and scATAC-seq data with options to specify the types of mutations to include. There also exists a function to artificially mutate a genome prior to performing PageRank.

MPALanalysis.R -- Using data obtained from Python workflow, this s/w is used to create a Seurat object of the PageRank and network data, clean and process it, and create visualizations of results.

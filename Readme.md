# Multiplex, Multimodal Mapping of Variant Effects in Secreted Proteins

This github repo contains all code required to recreate the analysis and figures from "Multiplex, multimodal mapping of variant effects in secreted proteins".

## Downloading and preparing the repository for analysis

1. Clone or fork this GitHub repository

2. Navigate to the downloaded folder. All input data will be present, but has been compressed to accommodate github file size restrictions. To decompress and rebuild the input files, run the following script.

`sh rebuild_input_files.sh`

## Requirements:

R 4.0.0 or greater

PyMOL 2.5.2 or greater

## Analysis and figures

The MultiSTEP_analysis.Rmd file contains all the code required to recreate the analysis and generate the figures and tables from the paper. The code is written to check for any required R packages and install them if necessary.

For figures involving protein structures, this script outputs .pml files. When the .pml files are opened in PyMOL, they will generate and save the publication figures.  

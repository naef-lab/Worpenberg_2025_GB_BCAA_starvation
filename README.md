# Worpenberg_2025_GB_BCAA_starvation
This repository contains the code and instructions to reproduce the main figures from the paper: "Codon-specific ribosome stalling reshapes translational dynamics during branched-chain amino acid starvation". Worpenberg et al., 2025, Genome Biology.

The full dataset, including larger files required for analysis, is permanently archived on **Zenodo**: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17036737.svg)](https://doi.org/10.5281/zenodo.17036737) 

To reproduce a specific figure, navigate to its corresponding folder (e.g., `Figure_1/`) and follow these steps:

1.  **Run Processing Scripts:** First, execute the R Markdown (`.Rmd`) script(s) located in the `Code/` subfolder. This step processes the raw data and generates the necessary intermediate files for plotting.
2.  **Assemble Final Figure:** Once the processing scripts are finished, run the main R Markdown (`.Rmd`) script located in the root of the figure folder. This will use the files generated in step 1 to create the final figure.


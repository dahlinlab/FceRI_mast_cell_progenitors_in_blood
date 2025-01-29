# FceRI_mast_cell_progenitors_in_blood

This repo contains information pertaining to the publication "Single-cell transcriptomics reveals the identity and regulators of human mast cell progenitors", https://doi.org/10.1182/bloodadvances.2022006969

In this publication we explored the presence of the FceRI receptor during mast cell differentiation. Through the generation of 2 single-cell transcriptomic datasets we identified a population of FceRI positive mast cell progenitors, and identified cytokines that modulate these progenitors.

An interactive web app to view the data is available at http://dahlinlab.cmm.se. The annotated .h5ad files are also available to download through the web app.

A conda environment .yml file is available under /init to reproduce the analysis environment.

2 .ipynb files in /Processing describe the processing of the data available on GEO:GSE184351, for each respective dataset, to match the analysis described in the manuscript:

Dataset1_Sample1_P15054_filteredmatrix: https://github.com/dahlinlab/FceRI_mast_cell_progenitors_in_blood/blob/main/Processing/BuffyC1_processing.ipynb

Dataset2_Sample2_P20409_1003-4_filteredmatrix: https://github.com/dahlinlab/FceRI_mast_cell_progenitors_in_blood/blob/main/Processing/Buffy210208_processing.ipynb

The raw count matrix files are available through NCBI GEO via the following link: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE184351.

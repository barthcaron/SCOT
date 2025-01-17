# Information about this fork
This fork extends SCOT by allowing for unbalanced Gromov-Wasserstein optimal transport using the implementation by Thibault Sejourne [here](https://github.com/thibsej/unbalanced_gromov_wasserstein). I have included an example of why unbalanced GW is useful in this general context in `unbalanced_GW.ipynb` (simulated data) and `unbalanced_GW_SNAREseq.ipynb` (SNARE-seq dataset).

# SCOT

Repository for "Gromov-Wasserstein based optimal transport for aligning single-cell multi-omics data" manuscript:
https://www.biorxiv.org/content/10.1101/2020.04.28.066787v1  
Alignment benchmarking results and a detailed description of the method can be found in this manuscript.

Python packages required:
numpy, sklearn, matplotlib, scipy, cython, POT (note that numpy and cython must be installed prior to POT)

scGEM.py contains a sample script for running SCOT, data files can be found here: https://github.com/jw156605/MATCHER/tree/master/pymatcher/data


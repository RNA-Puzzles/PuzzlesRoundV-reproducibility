# PuzzlesRoundV

This repository contains Jupyter notebooks and code for reproducing the results and figures presented in the forthcoming paper.

"RNA-Puzzles Round V: Blind predictions of 23 RNA structures"

The web portal of RNA-Puzzles Round V together with all the datasets are publicly available at [https://www.rnapuzzles.org/](https://www.rnapuzzles.org/).

# Repository Structure
This repository contains the codes necessary to replicate all figures from Puzzles Round V. It includes:

- `The figures_reproducibility.ipynb notebook` : this file can generate all the figures found in the Puzzles, with scores holding the original data for the figures. For details on how to generate data using various metrics, please refer to https://github.com/RNA-Puzzles/RNA_assessment.
- `scores`: this folder contains specific information on how the figures were produced.
- `figures`: This folder stores the output figures generated by the notebooks.

## Installation
matplotlib                3.8.0   
numpy                     1.26.4    
pandas                    2.1.4  
seaborn                   0.12.2     

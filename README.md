# Hierarchical Clustering Analysis Based on Anodic Limits and Solvation Free Energy of Lithium Salts

### Description
Scripts from the manuscript S. Chen, et al. Foreign Li-ion supply reshapes Li-oriented material discovery and lifetime limit of batteries.

J.W. and Y.W. calculated the molecular descriptor and conceived the machine learning workflow.T.C., W.W. and G.W. contributed to the debugging process and provided optimization suggestions.

1. Input Folder: "Data" ; 
2. Main code: "Cluster_by_Gsol_and_Val.ipynb"; 
3. Output folder: "Figure"

This program performs a hierarchical clustering analysis predicated on the anodic limits and solvation free energy of lithium salts. The data for the anodic limits and solvation free energy are obtained through quantum chemical computations.

### Operating system
- Windows, Mac , Linux

### Dependencies required to replicate the figures in the paper
- RDKit (most versions should be fine)
- matplotlib

### Dpendencies if you want to retrain on your own data
- RDKit
- sklearn
- scipy
- numpy
- matplotlib
- pandas

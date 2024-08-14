# Hierarchical Clustering Analysis Based on Anodic Limits and Solvation Free Energy of Lithium Salts

### Description
Scripts from the manuscript S. Chen, et al. Foreign Li-ion supply reshapes Li-oriented material discovery and lifetime limit of batteries.
J.W. and Y.W. calculated the molecular descriptor and conceived the machine learning workflow.

·Script for the generation of the machine learning.

·"Cluster_by_Gsol_and_Val.ipynb" to reproduce the data.

·Data files to draw the hierarchical cluster dendrograms.

This program performs a hierarchical clustering analysis predicated on the anodic limits and solvation free energy of lithium salts. The data for the anodic limits and solvation free energy are obtained through quantum chemical computations.

### Usage
Open Jupyter Notebook:
Launch Jupyter Notebook in your environment. You can do this by opening your terminal (or command prompt) and typing jupyter notebook. This command will open Jupyter in your default web browser.

Navigate to the Current Directory:
Once Jupyter Notebook is open in your browser, use the file browser within the Jupyter interface to navigate to the directory where the program is located.

Open the Notebook File:
Find the .ipynb file that you want to run. Click on it to open the notebook.

Run the Program:
After opening the notebook, you can run the program by executing each cell in sequence. You can run a cell by clicking on it and then pressing the Run button in the toolbar, or by pressing Shift + Enter on your keyboard.

View the Results:
Once all cells have been run, the output (including any figures) will be displayed directly in the notebook below the corresponding cells.

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

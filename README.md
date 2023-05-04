VSB Power Line Fault Detection using Spectral Analysis
This repository contains code that demonstrates the superiority of spectral analysis over time-domain methods for VSB Power Line Fault Detection. The code was written for the VSB Power Line Fault Detection Kaggle competition.

Contents
AML.ipynb: Jupyter Notebook containing the code for our spectral analysis approach.
README.md: This file.
Requirements
Python 3.6+
Jupyter Notebook
NumPy
Pandas
Matplotlib
SciPy
Usage
Clone this repository.
Download the data from the Kaggle competition page and place it in the data folder.
Open the spectral_analysis.ipynb Jupyter Notebook and run the cells to generate the results.
Open the time_domain.ipynb Jupyter Notebook (optional) and run the cells to generate the results.
The results will be saved in the results folder.
Results
Our spectral analysis approach achieved an accuracy of 0.96 on the test set, while the time-domain approach achieved an accuracy of only 0.76 for lower epochs. This demonstrates the superiority of spectral analysis for this particular problem.





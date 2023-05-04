## VSB Power Line Fault Detection using Spectral Analysis

This repository contains code that demonstrates the superiority of spectral analysis over time-domain methods for VSB Power Line Fault Detection. The code was written for the VSB Power Line [Fault Detection Kaggle competition](https://www.kaggle.com/competitions/vsb-power-line-fault-detection).

### Contents <a name="61"></a>
* <ins>AML.ipynb</ins>: Jupyter Notebook containing the code for our spectral analysis approach.
* <ins>README.md</ins>: This file.

### Requirements
* Python 3.6+
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* SciPy
* Usage

### Process
* Clone this repository.
* Download the data from the Kaggle competition page and place it in the data folder.
* Open the AML.ipynb Jupyter Notebook and run the cells to generate the results.
* The results will be saved in the results folder.


### Results
Our spectral analysis approach achieved an accuracy of 0.96 on the test set, while the time-domain approach achieved an accuracy of only 0.76 for lower epochs. This demonstrates the superiority of spectral analysis for this particular problem.


## Contributors 
* Srikanth Karri [srikanthkarri@vt.edu](srikanthkarri@vt.edu).
* Sai Pavan Bathala [bspavan25@vt.edu](bspavan25@vt.edu).
* Mohith Kamanuru [mohith@vt.edu](mohith@vt.edu).
* Sagar Atla [sagaratla@vt.edu](sagaratla@vt.edu).





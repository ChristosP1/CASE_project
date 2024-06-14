# CASE Data Preprocessing and Analysis
<p align="center">
  <img src="readme_images/data_acquisition.png" alt="Experiment setup">
</p>

(ORIGINAL, as in made by us) Presentation video of experiment setup:
[ECG-GSR-Annotations-Video Visualization](https://youtu.be/-avJuYvJ5Aw)

## Overview
This repository contains the code for preprocessing and analyzing the CASE dataset. Follow the steps below to execute the code in the provided Jupyter notebooks.
IMPORTANT: The statistical_analysis notebook is very big because it is meant to be used with a table of contents. Please consider opening the notebook in an environment that supports this functionality, for easier navigation.


## Prerequisites
Clone the repository
```bash
git clone https://github.com/ChristosP1/CASE_project.git
cd CASE_project
```
Make sure you have the necessary dependencies installed. You can install them using the following command:
```bash
pip install -r requirements.txt
```

## Steps to Run the Code
### 1. Open and Run the case1_preprocessing Notebook

- Open the case1_preprocessing.ipynb notebook in Jupyter.

- Set CPA = False and run all cells.

- After completion, set CPA = True and run all cells again.

### 2. Open and Run the statistical_analysis Notebook
- Open the case1_statistical_analysis.ipynb notebook in Jupyter.

- Set CPA = False and run all cells.

- After completion, set CPA = True and run all cells again.

### Note1: 
The CASE dataset (FULL) folder must be in the same directory as the notebooks (or adjust location in first lines)
### Note2: 
The preprocessed files have already been created for convenience. However if something goes wrong, the safest option would be to delete the preproceseed folder and recreate everything. Please keep in mind that CPA takes too long (>20 min), so not recommended :)

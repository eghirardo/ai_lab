# AI Lab 2024 Repository

This repository contains materials for the AI Lab 2024, held at Bocconi University. The project authors are: Ghirardo Edoardo, Iannone Giuseppe, Hoche Francois, Ronzino Filippo A., Tofanelli Elisa

## Introduction

This repository hosts all the necessary files and documentation pertaining to the AI Lab project. While the data files are strictly confidential and not public, the project structure, methodologies, and results are available in the accompanying Jupyter notebooks.

## Repository Structure

The repository is organized as follows:
1. HCC1806_datapreprocessing.ipynb: this notebook contains the data preprocessing steps for the HCC1806 cell line.
   This notebook contains a detailed explanation of EDA (Exploratory Data Analysis), data preprocessing and dimensionality reduction.
2. MCF7_datapreprocessing.ipynb: this notebook contains the data preprocessing steps for the MCF7 cell line. This second one aims instead at replicating the same steps for the MCF7 cell line, as they were performed for the HCC1806 cell line. As it reproduces the same steps, we will not provide a detailed explanation but just the necessary comments.
3. HCC1806_training.ipynb: this notebook contains the training steps for the HCC1806 cell line.
It includes dimensionality reducton, feature selection, unsupervised learning (K-means and hierarchical clustering) and supervised learning.
4. MCF7_training.ipynb: this notebook contains the training steps for the MCF7 cell line. Once again, the same steps are replicated for the MCF7 cell line and the notebook has the same flavour of 2.
5. Bonus_KAN.ipynb: this notebook contains a bonus part of the project, which is a first try to use the recently published Kolmogorov-Arnold Networks.
6. Pathway_analysis.ipynb: this notebook contains the pathway analysis, an important bioinformatics tool to understand the biological processes particularly related to molecular pathways within living organisms.
7. HCC1806_Predictions.ipynb: this notebook contains the predictions for the given testing dataset for the HCC1806 cell line, we will use the ensemble model to predict and label 1 Normoxia and 0 Hypoxia. We will store them into a csv file.
8. MCF7_Predictions.ipynb: this notebook contains the predictions for the given testing dataset for the HCC1806 cell line, we will use the ensemble model to predict and label 1 Normoxia and 0 Hypoxia. We will store them into a csv file.

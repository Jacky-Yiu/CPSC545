# CPSC 545 Project Repository

This repository contains the code and data for our project in the CPSC 545 course. The project focuses on predictive modeling using various machine learning techniques, specifically targeting gene expression prediction based on chemical and cellular interactions. Our approach integrates cutting-edge algorithms to address complex bioinformatics challenges.

The dataset and biological question came from this Kaggel competition: (https://www.kaggle.com/competitions/open-problems-single-cell-perturbations/data)[https://www.kaggle.com/competitions/open-problems-single-cell-perturbations/data]

## Repository Structure

- `CaTboost-model.ipynb`: Jupyter notebook containing the implementation of the CatBoost model. This notebook includes data preprocessing, model training, and evaluation using the provided datasets.
  
- `NN-model-rowwise-rmse.ipynb`: This notebook details the implementation of a neural network model with a specific focus on minimizing row-wise RMSE. It includes data handling, network architecture design, training, and performance evaluation.

- `VAE.ipynb`: Implementation of a Variational Autoencoder (VAE) for our dataset. This notebook covers the entire pipeline from data processing to model training and result analysis.

- `cpsc545_project_report.pdf`: A comprehensive report of our project. This document includes background information, methodology, results, and discussions on the findings.

- `de_train.parquet`: The training dataset used for model development. This file contains differential expression data crucial for training our predictive models.

- `id_map.csv`: Test dataset for evaluating model performance. This file includes only the input data, as it is part of a competition. Participants submit their predictions based on this dataset, and scores are assigned based on the accuracy of these predictions.

## Getting Started

To get started with this project, clone the repository to your local machine:

```bash
git clone https://github.com/your-username/your-repository-name.git
```
Ensure you have Jupyter Notebook installed to run the .ipynb files. For data processing and model training, additional Python libraries such as pandas, numpy, catboost, and tensorflow might be required.


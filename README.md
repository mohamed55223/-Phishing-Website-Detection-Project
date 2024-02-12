# Phishing Website Detection Project

## Overview

This project focuses on building a machine learning model for detecting phishing websites. The model is trained on a dataset containing features related to website characteristics and is validated using an additional dataset.

## Project Structure

The project structure includes the following files:

- `final_data_phishing.csv`: CSV file containing the dataset used for training the machine learning model.
- `final_data_old.csv`: CSV file containing a separate dataset used for validation and testing the trained model.
- `Phishing_Model_Training.ipynb`: Jupyter Notebook file containing code for training the Random Forest classifier.
- `Phishing_Model_Validation.ipynb`: Jupyter Notebook file containing code for validating the trained model and generating visualizations.
- `First_Version.joblib`: Serialized joblib file containing the trained Random Forest model.

## Requirements

To run the provided Jupyter Notebooks, make sure you have the following libraries installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib

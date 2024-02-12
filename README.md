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
- Playing with dataset.ipynb : Jupyter Notebook file containing code for converting data from arff file into csv file and change values into binary values
- confusion_matrix_valid.txt : text file has information about validation calssification output and a validation confusion matrix
- Output.ipynb : Jupyter Notebook file containing code for making a prediction output

## Requirements

To run the provided Jupyter Notebooks, make sure you have the following libraries installed:
joblib==1.0.1
matplotlib==3.4.3
numpy==1.21.2
pandas==1.3.3
scikit-learn==0.24.2
seaborn==0.11.2





## How to Use
Training the Model:

Open Phishing_Model_Training.ipynb in a Jupyter Notebook environment.
Execute the cells to load the training data, train the model, and save the trained model.
--------------------------------------------------------------------------
Validation and Visualization:

Open Phishing_Model_Validation.ipynb in a Jupyter Notebook environment.
Execute the cells to load the validation data, make predictions, and visualize the model's performance.
-------------------------------------------------------------------------
Pre-trained Model:

If you just want to use the pre-trained model without retraining, load First_Version.joblib in your code:
import joblib

# Load the pre-trained model
loaded_model = joblib.load('First_Version.joblib')

## Results
The project achieves an accuracy of 96% on the Training dataset 
The project achieves an accuracy of 87% on the validation dataset. Visualizations include a confusion matrix and feature importance.

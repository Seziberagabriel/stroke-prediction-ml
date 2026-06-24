# Stroke Risk Prediction: Classical ML vs. Deep Learning

A comparative machine learning project predicting stroke risk from clinical and demographic patient data, using both Scikit-learn (classical ML) and TensorFlow (deep learning) pipelines.

## Project Overview

Stroke is the second leading cause of death globally, responsible for approximately 11% of total deaths (WHO, 2020). Early identification of at-risk patients from routinely collected clinical data could enable timely preventive intervention. This project frames stroke prediction as a binary classification problem and systematically compares traditional machine learning approaches against deep learning architectures, with particular attention to the challenges posed by severe class imbalance (~4.9% positive class).

## Dataset

**Source:** fedesoriano, "Stroke Prediction Dataset," Kaggle, 2021.  
**Link:** https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset  
**File:** `data/healthcare-dataset-stroke-data.csv`  
**Records:** 5,110 patients | **Features:** 11 clinical/demographic | **Target:** `stroke` (binary)

The dataset is included in the `data/` folder for reproducibility. It is publicly available under the Open Database License.

## Repository Structure

stroke-risk-prediction/
├──  healthcare-dataset-stroke-data.csv   
├── stroke_prediction_notebook.ipynb      
├── experiment_results.csv                     
├── README.md                                  
└── requirements.txt                           

## Author
*TUYISINGIZE SEZIBERA Gabriel*  
*Machine Learning Module Final Summative Project*  
*ALU 2026*



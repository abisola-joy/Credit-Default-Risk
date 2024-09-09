# Credit Default Risk Prediction

## Overview

In this project, a comparative analysis of various machine learning and a deep learning model was carried out and the models include random forest, decision tree, SVM (Support Vector Machine), XGBoost (eXtreme Gradient Boosting), ADABoost (ADAptive Boosting) and multilayered perceptron (MLP) with three-hidden layers, so as to predict credit default using loan data from LendingClub. The goal here was to identify the most effective model for predicting defaults. This project involved several stages, including data preparation, model training, evaluation, analysis and model deployment.

## Data Collection

The data used in this project was from LendingClub, they are a lending platform that provides detailed information on loans issued from 2007 to 2018. The publicly available dataset was downloaded from Kaggle, a popular data science platform and no personally identifiable information (PPI) of borrowers was used, so as to adhere to data privacy regulations and ethical guidelines. 

## Methodology

The methodology was split into different notebooks, to allow for organisation and quick access. The project includes the following notebook:

1. **Stratified Sampling (LoanStatus)**: Data collection process, downloading the dataset and carrying out stratified sampling of the dataset.
2. **Clean Data**: Data preparation, cleaning and multi-observational analysis of the data.
3. **Further Cleaning**: Data preprocessing and testing of outliers and normalisation techniques.
4. **Class Imbalance Technique**: Testing various sampling techniques.
5. **Feature Selection**: Feature selection with recursive feature elimination with cross-validation (RFECV).
6. **Grid Search**: Hyperparameter Tuning
7. **Model Development**: Testing various machine learning (ML) and deep learning (DL) models to identify the most effective approach, as well as a combination of them. It also includes model performance evaluation using metrics such as accuracy, precision, recall, and AUC.
8. **Model Deployment**: conducting SHAP analysis to interpret model predictions and visualise decision-making processes.

Each stage must be completed sequentially to ensure a thorough analysis and effective model training.

<!-- ## How to Use

1. **Clone the Repository**: 
   git clone https://github.com/abisola-joy/credit-default-risk.git

2. **Install Dependencies**: 
Ensure you have the necessary Python packages installed. You can install them using pip.

bash
Copy code
pip install -r requirements.txt
Upload Data: Prepare your data in a CSV format and upload it using the provided GUI. The application will handle data cleaning, model prediction, and SHAP analysis.

Run the Application: Execute the main script to start the application:

bash
Copy code
python main.py -->
## Results
The performance of the models is detailed in the evaluation section, showing a comparison between individual and ensemble models. The proposed model outperforms traditional methods and is validated against baseline results from previous research, all of which can be found in the projects documentation (*not included*)

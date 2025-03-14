# OM_ImagoAI_TASK
 README

Project Overview
This repository contains a machine learning pipeline for predicting `vomitoxin_ppb` using both a Random Forest model and an LSTM neural network.

## Installation & Dependencies
Ensure you have Python installed and install the required dependencies using:
bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow


## Running the Code
1. Place your dataset file (`TASK-ML-INTERN.csv`) in the project directory.
2. Run the script using:
bash
python ml_pipeline.py

3. Model performance metrics will be displayed in the console.

## Repository Structure
ml_pipeline.py: Main script containing data processing, training, and evaluation functions.
README.md: Instructions on setting up and running the project.
`report.md`: Summary of preprocessing, modeling, and key insights.

## Results & Future Improvements
- Random Forest performed well with lower MAE.
- LSTM may require further tuning for better results.
- Future improvements include feature selection and additional data collection.


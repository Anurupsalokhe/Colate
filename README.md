# Adult Income Prediction Project

## Project Overview
This project predicts whether a person earns more than $50,000/year using census data. The process involves data cleaning, exploratory analysis, model training, and evaluation.

## Process Steps

1. **Data Collection**
   - Downloaded from UCI Machine Learning Repository
   - Contains demographic and employment information

2. **Data Cleaning**
   - Handled missing values marked as "?"
   - Converted categorical features to numerical
   - Created new combined features

3. **Exploratory Analysis**
   - Analyzed income distribution
   - Visualized relationships between features
   - Checked for class imbalance

4. **Feature Engineering**
   - Scaled numerical features
   - Encoded categorical variables
   - Selected most important features

5. **Model Training**
   - Trained Random Forest classifier
   - Trained XGBoost classifier
   - Optimized hyperparameters using GridSearch

6. **Evaluation**
   - Compared model performance
   - Analyzed precision/recall tradeoffs
   - Generated ROC curves

7. **Interpretation**
   - Identified most influential features
   - Analyzed model decision patterns
   - Documented key findings

## Model Results

**Random Forest**
- Accuracy: 86.7%
- Best for: Stable predictions

**XGBoost** 
- Accuracy: 87.5%
- Best for: Slightly better performance

## How to Run

1. Install requirements:
```bash
pip install -r requirements.txt
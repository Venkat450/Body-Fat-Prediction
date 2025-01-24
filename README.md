# Body Fat Prediction

## Overview
This project focuses on predicting body fat percentage using various regression models. The dataset includes measurements of physical attributes such as weight, height, and body dimensions. The analysis applies techniques such as linear regression, ridge regression, lasso regression, and elastic net, along with hyperparameter tuning.

## Dataset
The dataset used is the [Body Fat Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/body-fat-prediction-dataset) from Kaggle. It contains 252 entries and 15 attributes. All features are continuous, with no missing categorical variables.

## Requirements
The following Python libraries are required:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

Install these libraries using:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
Project Workflow
Data Exploration:

Summary statistics for continuous attributes.
Visualization of feature distributions and correlations.
Data Preprocessing:

Handling missing values by imputing medians.
Scaling features using StandardScaler.
Model Training and Evaluation:

Split data into training (80%) and testing (20%) sets.
Applied models:
Linear Regression
Stochastic Gradient Descent (SGD) Regression
Ridge, Lasso, and Elastic Net regularizations
Evaluation metrics:
Root Mean Square Error (RMSE)
Validation losses during cross-validation
Hyperparameter Tuning:

Explored the impact of regularization strengths (alpha).
Evaluated learning rate and batch size effects for SGD.
Polynomial Regression:

Investigated the impact of feature interactions using polynomial features.
Key Findings
Attributes such as abdomen, chest, hip, and weight strongly correlate with body fat percentage.
Ridge and Elastic Net regularizations performed well with lower alpha values.
Polynomial regression showed potential for overfitting with higher degrees.
Results
Best model: Linear Regression with Ridge regularization.
RMSE for the best model:
Training: ~1.3
Validation: ~1.4
How to Run
Clone the repository:
bash
Copy
Edit
git clone <repository-link>
cd <repository-folder>
Ensure all dependencies are installed.
Run the provided notebook or script to reproduce results.
Acknowledgments
The dataset was sourced from Kaggle: Body Fat Prediction Dataset.

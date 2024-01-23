# Titanic Survival Prediction Project

## Overview
This project aims to predict the survival of passengers on the Titanic based on various features such as age, gender, and ticket class. The dataset includes training and test data, with ground truth provided in the gender_submission.csv file.

## Files
- **train.csv**: Training dataset with features and ground truth labels.
- **test.csv**: Test dataset for making predictions.
- **gender_submission.csv**: A sample submission file with the correct format.

## Data Cleaning and Feature Engineering
- Numeric conversion of 'SibSp' and 'Parch'.
- Creation of 'Family_Size' based on the sum of 'SibSp' and 'Parch'.
- Categorization of passengers into age groups.
- Extraction of deck information from the 'Cabin' column.
- Extraction of ticket prefixes.
- Calculation of 'Fare_Per_Person'.
- Additional feature engineering based on titles, family size, age class, fare family, cabin type, and ticket length.

## Visualization and Analysis
- Visualizations of survival counts by various features, including titles, family size, age group, deck, ticket prefix, cabin type, and fare per person.

## Machine Learning Models
- Training of logistic regression, random forest, and support vector machine models.
- Model evaluation using accuracy, classification report, and confusion matrix.
- Hyperparameter tuning for the random forest model.

## Usage
1. Clone the repository: `git clone <repository_url>`
2. Install required packages: `pip install -r requirements.txt`
3. Run the Jupyter Notebook: `jupyter notebook`
4. Open the Titanic_Survival_Prediction.ipynb file and execute the cells.

## Results
- The best-performing model is a random forest classifier with tuned hyperparameters.
- Evaluation metrics include accuracy, precision, recall, and F1-score.

## Further Steps
- Explore additional feature combinations for improved model performance.
- Collaborate with domain experts for deeper insights.
- Refine and iterate on the models for better predictions.

# Medical Expenses Predictor

This project predicts medical expenses based on various factors such as age, BMI, number of children, smoking status, and region. The dataset used for this analysis is derived from a medical insurance dataset.

## Features

The following features are used for prediction:
- **Age**: The age of the individual.
- **Sex**: Gender of the individual (male/female).
- **BMI**: Body Mass Index, a measure of body fat based on height and weight.
- **Children**: Number of children covered by health insurance.
- **Smoker**: Whether the individual is a smoker (yes/no).
- **Region**: The region where the individual resides (northeast, northwest, southeast, southwest).

## Dataset

The dataset contains 1,338 entries with the following columns:
- `age`
- `sex`
- `bmi`
- `children`
- `smoker`
- `region`
- `charges` (target variable)

## Methodology

1. **Data Exploration**: The dataset is analyzed to understand the distribution of features and their relationship with medical charges.
2. **Data Preprocessing**: Missing values are handled, and categorical variables are encoded.
3. **Model Training**: A linear regression model is trained to predict medical expenses.
4. **Evaluation**: The model's performance is evaluated using metrics such as RMSE (Root Mean Square Error).

## Results

The model provides insights into how different factors influence medical expenses. For example:
- Smokers tend to have significantly higher medical expenses.
- BMI and age also have a notable impact on charges.

## How to Run

1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

2. Open the Jupyter notebook notebook.ipynb and run the cells to train the model and visualize the results.


## Dependencies
- Python 3.7+
- pandas
- numpy
- matplotlib
- scikit-learn


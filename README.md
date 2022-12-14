# Medical-Charges-Prediction

**Project Status: Finished**

## Objective
In this project, we will be training a regression model on the "Insurance" dataset. The model is to predict the insurance costs for a person based on their age, sex, BMI (Body Mass Index), and more.

## About Dataset
This dataset is contributed by Brett Lantz, the author of the textbook Machine Learning with R. The dataset can be found on GitHub [here](https://github.com/stedy/Machine-Learning-with-R-datasets/blob/master/insurance.csv). 

The dataset has 1338 records, each representing a beneficiary. It also has 7 columns, namely:
- age
- sex
- bmi
- children
- region
- charges

## Methods
- Data Visualization
- Label Encoding
- One-Hot Encoding
- Scaling
- Predictive Modeling

## Tools
- AWS SageMaker
- Python 3.9.15
- Jupyter
- Sci-Kit Learn
- NumPy
- Pandas
- Matplotlib
- Seaborn
- YellowBrick

## Results
The final model (GradientBoostingRegressor) has an R2 score of 91.5%. The model seems to suffer a slight underfitting, though.

Insurance Charges Prediction using Linear Regression

Project Overview

This project uses Machine Learning to predict medical insurance charges based on personal attributes such as age, gender, BMI, number of children, and smoking status.
A Linear Regression model is trained using Python and Scikit-learn to estimate insurance charges from the available data.

Objectives
* Analyze the factors associated with medical insurance charges.
* Explore the relationship between BMI and insurance charges.
* Preprocess categorical features for machine learning.
* Train a Linear Regression model.
* Evaluate model performance using R² and Adjusted R² scores.

Dataset Information
The dataset contains **1,338 records and 7 columns**.
| Feature  | Description                                 |
| -------- | ------------------------------------------- |
| age      | Age of the individual                       |
| sex      | Gender                                      |
| bmi      | Body Mass Index                             |
| children | Number of children                          |
| smoker   | Smoking status                              |
| region   | Residential region                          |
| charges  | Medical insurance charges (target variable) |

Technologies Used
* Python
* Pandas
* Seaborn
* Scikit-learn
* Jupyter Notebook
* Machine Learning
* Linear Regression

Project Workflow
1. Load the dataset using Pandas.
2. Explore the data and visualize the relationship between BMI and insurance charges.
3. Select the input features and target variable.
4. Encode categorical features such as `sex` and `smoker`.
5. Split the dataset into training and testing sets using an 80:20 ratio.
6. Train a Linear Regression model.
7. Predict insurance charges for the test dataset.
8. Evaluate the model using R² and Adjusted R² scores.

Model Details
**Algorithm:** Linear Regression
**Input Features:**
* Age
* Sex
* BMI
* Children
* Smoker

Results
Evaluation Metric   Score 
R² Score            0.7811
Adjusted R² Score   0.7770
The model achieved an R² score of approximately 0.78 on the test dataset.

Conclusion
This project demonstrates a basic Machine Learning workflow for predicting medical insurance charges using Linear Regression. It covers data loading, visualization, feature encoding, model training, prediction, and evaluation.


# HealthInsuranceCostPredictionModelWithPython



Health Insurance Cost Prediction With Python

This project focuses on predicting medical insurance costs based on key factors such as age, gender, BMI, number of children, smoking status, and region. We use Linear Regression as the predictive model.

Table of Contents

1. Project Overview


2. Dataset


3. Installation


4. Dependencies


5. Data Analysis and Visualization


6. Data Pre-Processing


7. Model Training


8. Model Evaluation


9. Usage


10. Contact



Project Overview

The objective of this project is to develop a model that can accurately estimate medical insurance costs for individuals based on relevant attributes provided in the dataset.

Dataset

The dataset used contains 1,338 entries with the following features:

age: Age of the individual

sex: Gender of the individual (male or female)

bmi: Body Mass Index, a measure of body fat based on height and weight

children: Number of children/dependents covered by the insurance

smoker: Whether the individual smokes or not (yes or no)

region: Residential region within the U.S. (northeast, northwest, southeast, southwest)

charges: Medical insurance cost, which serves as the target variable in the prediction model


Installation

Clone the repository and install the necessary libraries as specified in the dependencies.

Dependencies

The project requires the following Python libraries:

NumPy

Pandas

Matplotlib

Seaborn

scikit-learn


Data Analysis and Visualization

Exploratory Data Analysis (EDA) is performed to understand the distribution and relationships among the features. Key steps include visualizing the distributions of continuous variables (age, BMI, and charges) and analyzing categorical variables (sex, smoker status, children, and region).

Data Pre-Processing

The categorical data (sex, smoker, and region) is converted to numerical format, allowing it to be used effectively in the model. This includes mapping categories to numbers for model compatibility.

Model Training

The data is split into training and test sets (80-20 split), and a Linear Regression model is trained on the training set. The model learns to predict the insurance charges based on the input features.

Model Evaluation

The model is evaluated based on the R-squared metric to determine its effectiveness in capturing the variance in the data. Current R-squared values indicate that the model performs well, with separate scores for training and test data.

Usage

The model can predict insurance costs for any new individual based on their input data across the six features. Users can input their own data to receive an estimated insurance cost.

Roll number

PDS-05(MU)-09






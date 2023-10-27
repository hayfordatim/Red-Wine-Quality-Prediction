# Red Wine Quality Prediction



### Project Overview

This project is dedicated to classifying wine quality into poor or good. The primary objective is to employ machine learning to classify wine quality based on various chemical parameters. By following data analysis, preprocessing, model training, and evaluation, we aim to provide insights into the factors influencing wine quality ratings, enabling users to make informed quality assessments for red wines.


### Key Objective

- Perform exploratory data analysis (EDA) to gain insights into the relationships between various chemical properties and wine quality.
- Train a machine learning model, specifically a Random Forest Classifier, to predict the quality of red wines based on chemical attributes.
- Evaluate the model's accuracy and performance in wine quality prediction.


### Approach

- Data Analysis: The project begins with data analysis, exploring statistical measures, data visualization, and uncovering correlations between different chemical parameters and wine quality.
- Data Preprocessing: The dataset undergoes data preprocessing, including handling duplicated values and binarizing the quality ratings into 'good' and 'poor' labels (1 and 0, respectively).
- Data Splitting: The data is divided into training and testing sets, ensuring that the model is both trained and evaluated on different subsets.
- Model Training: A Random Forest Classifier is used to train the machine learning model. The Random Forest Classifier is an ensemble model of decision trees, known for its accuracy and robustness.
- Model Evaluation: The project assesses the model's accuracy using the 'accuracy_score' function.


### Data Source

The data was acquired from the UC Irvine Machine Learning Repository [site](http://archive.ics.uci.edu/dataset/186/wine+quality).

The columns(properties) present are:

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality


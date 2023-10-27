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

### Data Preparation

In the data preparation section, I meticulously processed the Wine Quality-Red dataset to ensure its suitability for machine learning. I began by importing essential Python libraries, such as NumPy, Pandas and Sklearn, and loaded the dataset into a Pandas DataFrame. After examining the data's shape and structure, I conducted a preliminary analysis to identify and handle any missing values as well as duplicates. 

![data](https://github.com/hayfordatim/Red-Wine-Quality-Prediction/blob/main/Images/carbon-4.png)

![data](https://github.com/hayfordatim/Red-Wine-Quality-Prediction/blob/main/Images/s1.png)

![data](https://github.com/hayfordatim/Red-Wine-Quality-Prediction/blob/main/Images/carbon-6.png)

![data](https://github.com/hayfordatim/Red-Wine-Quality-Prediction/blob/main/Images/s2.png)


### Exploratory Data Analysis

In the exploratory data analysis (EDA) phase, I delved deeper into the Wine Quality-Red dataset to uncover valuable insights and patterns. Employing libraries like Matplotlib and Seaborn, I visualized the data's characteristics. Diverse plots and histograms were created to better understand the distribution of each feature. Through these visualizations, I observed the relationships between attributes and the quality of the wines, shedding light on potential correlations and trends. Additionally, statistical summaries and descriptive statistics were used to provide a comprehensive overview of the data's central tendencies and dispersions. This EDA process played a pivotal role in guiding my model development and feature selection.

![data](https://github.com/hayfordatim/Red-Wine-Quality-Prediction/blob/main/Images/carbon-7.png)

![data](https://github.com/hayfordatim/Red-Wine-Quality-Prediction/blob/main/Images/s4.png)

![data](https://github.com/hayfordatim/Red-Wine-Quality-Prediction/blob/main/Images/carbon-8.png)

![data](https://github.com/hayfordatim/Red-Wine-Quality-Prediction/blob/main/Images/s5.png)

![data](https://github.com/hayfordatim/Red-Wine-Quality-Prediction/blob/main/Images/carbon-9.png)

![data](https://github.com/hayfordatim/Red-Wine-Quality-Prediction/blob/main/Images/s6.png)

![data](https://github.com/hayfordatim/Red-Wine-Quality-Prediction/blob/main/Images/carbon-10.png)

![data](https://github.com/hayfordatim/Red-Wine-Quality-Prediction/blob/main/Images/s7.png)

### Maching Learning Modeling

![data](https://github.com/hayfordatim/Red-Wine-Quality-Prediction/blob/main/Images/carbon-11.png)

![data](https://github.com/hayfordatim/Red-Wine-Quality-Prediction/blob/main/Images/carbon-12.png)

![data](https://github.com/hayfordatim/Red-Wine-Quality-Prediction/blob/main/Images/carbon-13.png)

![data](https://github.com/hayfordatim/Red-Wine-Quality-Prediction/blob/main/Images/carbon-14.png)

![data](https://github.com/hayfordatim/Red-Wine-Quality-Prediction/blob/main/Images/carbon-15.png)

![data](https://github.com/hayfordatim/Red-Wine-Quality-Prediction/blob/main/Images/s8.png)

# Classification---Wine-Quality-Dataset
This repository contains various ML based classification algorithm experimented on Wine dataset. Also, optimization techniques are implemented to improve the model

Dataset - The dataset has been taken from UCI Machine Learning Repository under the name of Wine Quality Dataset(https://archive.ics.uci.edu/ml/datasets/wine+quality)

Attributes - 
1. fixed acidity
2. volatile acidity
3. citric acid
4. residual sugars
5. chlorides
6. free sulfur dioxide
7. total sulfur dioxide 
8. density
9. pH
10. sulphates
11. alcohol
12. quality 
We have 2 files , one for red_wine and other for white_wine

Problem Statement -

1. Prediction of wine_type(red/white)
2. Prediction of quality label (low, medium and high)

Problem Type - Classification(Since the response variable(wine_type and quality_label) are categorical) 

Approach Used-

1. Exploratory data analysis- 
(https://github.com/Saloni3108/Classification---Wine-Quality-Dataset/blob/main/1.%20EDA%20and%20Pre-processing.ipynb)
a) Descriptive Statistics - Five point summary 
b) Frequency Distribution plot - Concentration 
c) Boxplot - Treatment for Outliers 
d) Heatmap - Correlation

2. Data preprocessing -
(https://github.com/Saloni3108/Classification---Wine-Quality-Dataset/blob/main/1.%20EDA%20and%20Pre-processing.ipynb)
a) Feature importance 
b) Scaling 
c) Missing values 
d) Checking class imabalance
e) Train and test split

3. Modelling -

a) Logistic Refression (wine_type - red and white)
(https://github.com/Saloni3108/Classification---Wine-Quality-Dataset/blob/main/2.%20Logistic%20Regression.ipynb)

b) Multinomial regression(quality_type - high, medium and low) 
(https://github.com/Saloni3108/Classification---Wine-Quality-Dataset/blob/main/3.%20Multinomial%20Regression.ipynb)

c) SVM and K-SVM
(https://github.com/Saloni3108/Classification---Wine-Quality-Dataset/blob/main/4.%20SVM%20and%20K-SVM.ipynb)

d) Naive Bayes
(https://github.com/Saloni3108/Classification---Wine-Quality-Dataset/blob/main/5.%20Naive%20Bayes.ipynb)

e) Decision Tree 
(https://github.com/Saloni3108/Classification---Wine-Quality-Dataset/blob/main/5.%20Naive%20Bayes.ipynb)

f) Random Forest Classification
(https://github.com/Saloni3108/Classification---Wine-Quality-Dataset/blob/main/6.%20Decision%20and%20Random%20Forest.ipynb)


4. Optimization (Model improvement) Techniques used- 

a) SMOTE - For class imbalance 
b) Bagging and Boosting - To oversome Overfitting of train dataset
c) GridSearhCV - for optimality 
d) Kernel functions transformation(SVM)

# Coronary-Heart-Disease-Classification-Problem
Colloborator: Parth Modhia

## Executive Summary:
Cardiovascular disease is one of the most significant reasons for the number of deaths among all people around the world. The early forecast of cardiovascular ailments can help in compelling high-risk patients to change their risky habits and follow a healthy routine such that any unfavorable events can be prevented.
The goal of this study was to forecast if a patient would get coronary heart disease in a 10-year span or not according to the traits he possesses.
The dataset is publicly accessible on the Kaggle website, and it is from an in progress cardiovascular examination, on the inhabitants of the town of Framingham, Massachusetts. The dataset has over 4000 records and 15 features or attributes. Each attribute is a potential risk factor. There are both demographic, behavioral, and medical risk factors.
While exploring our data, we found that the total number of rows with missing values were 582 which is only 13 percent of the entire dataset, so we excluded them. As we have a classification problem, we have applied kNN, Naive Bayes, Random Forest, Logistic Regression, Neural Net, Linear Discriminant Analysis and Support Vector Machine and then evaluated the performances of each model.
We formulated 7 different supervised learning models and created confusion matrices, Lift Charts/ ROC curves and found out accuracies for all of them. Men appear to be more vulnerable to coronary illness than Women. An expansion in age, number of cigarettes smoked every day and systolic Blood Pressure additionally show expanded chances of having coronary illness.
Out of all the 7 supervised learning models, our KNN model is most accurate with an accuracy of 86%.

## I. Background and Introduction:
Cardiovascular diseases are probably the most significant reason for the number of deaths among all people around the world. The prediction of cardiovascular diseases is viewed as one of the most significant subjects in the field of data analytics under the healthcare domain. World Health Organization has evaluated 12 million demises happening around the world, consistently because of heart related problems. Around 610,000 individuals fall at the hands of coronary illness in the United States each year–that is 1 in every four demises; that is, one person dies every 37 seconds due to it.
Coronary illness portrays a scope of conditions that influences the heart. Sicknesses under the coronary illness umbrella comprises of blood vessels ailments, heart rhythm issues (arrhythmias); and heart absconds you're brought into the world with (congenital heart defects), etc.
The expression "coronary illness" is frequently utilized conversely with the expression "cardiovascular diseases." Cardiovascular sickness by and large alludes to conditions that include restricted or blocked vessels that can prompt a respiratory failure, chest torment (angina) or stroke. Other heart conditions, for example, those that influence your heart's muscle, valves or rhythm, likewise are viewed as types of coronary illness. Numerous types of coronary illness can be prevented or treated by following and implementing solid & healthy lifestyle decisions. The early forecast of cardiovascular ailments can help in compelling high-risk patients to change their risky habits and follow a healthy routine such that any unfavorable events can be prevented.
Our study means to pinpoint the most pertinent/hazardous elements involved in the cardiovascular diseases and to anticipate the general hazard. The classification goal is to forecast if a patient would get coronary heart disease in a 10-year span.

## II. Data Exploration and Visualization:
We utilized different visualization techniques to understand data. We checked the multi-collinearity for linear models.
In the end, the model is intended to pinpoint the most relevant/risk factors of heart disease as well as predict the overall risk. It’s a binary classification problem.
Predictors are Age, Glucose level, Gender, Education, Current Smoker, Cigarette per day, Blood Pressure Medications, Prevalent Stroke, Prevalent Hypertension, Diabetes, Total Cholesterol, Systolic Blood Pressure, Diastolic Blood Pressure, Body Mass Index & Heart rate.The Outcome variable is a binary variable, the 10-year risk of coronary heart disease CHD with the class either Yes or No.

## III. Data Preparation and Preprocessing:
We had checked for missing or NA values in the dataset & descriptive statistic of each variable to see if there were any outliers. We eliminated the rows which had missing values because if we had imputed the values here, I would create a bias in our features
Total number of rows with missing values was 582. Since it was only 13.72 percent of the entire dataset the rows with missing values were excluded.
We performed Principal Component Analysis. PCA looks for properties that show as much variation across classes as possible to build the principal component space. The algorithm uses the concepts of variance matrix, covariance matrix, eigenvector and eigenvalues pairs to perform PCA, providing a set of eigenvectors and its respectively eigenvalues as a result. It is very simple; the eigenvectors represent the new set of axes of the principal component space and the eigenvalues carry the information of quantity of variance that each eigenvector have. So, in order to reduce the dimension of the dataset we are going to choose those eigenvectors that have more variance and discard those with less variance.

## IV. Data Mining Techniques and Implementation: 
As we have a classification problem, we have applied kNN, Naive Bayes, Random Forest, Logistic Regression, Neural Net, Linear Discriminant Analysis and Support Vector Machine. We will compare the models to find the best fit model for our problem.

### 1. K-Nearest Neighbors:
RMSE was used to select the optimal model using the smallest value. The final value used for the model was k = 43. The model is classified as level 0 thus the patient will not have coronary heart disease in 10 years.

### 2. Random Forest:
Percentage of predicted classifications correct 84.6994%
The model is classified as level 0 thus the patient will not have coronary heart disease in 10 years.

### 3. Logistic Regression:
For logistic regression algorithm, we found the accuracy to be 83.87%.

### 4. Neural Net:
The model is classified as level 0 thus the patient will not have coronary heart disease in 10 years.

### 5. Support Vector Machine:
The model is classified as level 0 thus the patient will not have coronary heart disease in 10 years.

## V. Performance Evaluation: 
Evaluating our machine learning algorithm is an essential part of any project. Most of the times we use classification accuracy to measure the performance of our model, however it is not enough to truly judge our model. In this project, we have made use of confusion matrices, ROC curves & Lift charts to evaluate different models. Classification Accuracy is what we usually mean, when we use the term accuracy. It is the ratio of number of correct predictions to the total number of input samples. Confusion Matrix as the name suggests gives us a matrix as output and describes the complete performance of the model.

## VI. Discussion and Recommendation:
We formulated 7 different supervised learning models and created confusion matrices, Lift Charts/ ROC curves and found out accuracies for all of them. Out of all the 7 supervised learning models, our KNN model is most accurate with an accuracy of 86%.
• Men appear to be more vulnerable to coronary illness than Women. An expansion in age, number of cigarettes smoked every day and systolic Blood Pressure additionally show expanded chances of having coronary illness.
• Total cholesterol shows no huge change in the chances of getting coronary heart disease. This could be because of the presence of 'good cholesterol(HDL) while the total cholesterol was calculated. Glucose also causes a truly irrelevant change in the chances of getting coronary heart disease.
• Overall model could be improved if more amount of data is available.

## VII. Summary:
The goal of our study was to forecast if a patient would get coronary heart disease in a 10-year span or not according to the traits he possesses. The early forecast of cardiovascular ailments can help in compelling high-risk patients to change their risky habits and follow a healthy routine such that any unfavorable events can be prevented. For our classification problem, we have applied kNN, Naive Bayes, Random Forest, Logistic Regression, Neural Net, Linear Discriminant Analysis and Support Vector Machine and then evaluated the performances of each model.
Out of all the 7 supervised learning models, our KNN model is most accurate with an accuracy of 86%. Changes in features like age, number of cigarettes smoked every day and systolic Blood Pressure have a directly proportional relationship with the 10 year coronary heart disease. Changes in the level total cholesterol and glucose level do not cause much changes in the chances of getting coronary heart disease.

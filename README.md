# machine_learning_project-supervised-learning

## Project Outcomes
- Supervised Learning: use supervised learning techniques to build a machine learning model that can predict whether a patient has diabetes or not, based on certain diagnostic measurements. The project involves three main parts: exploratory data analysis, preprocessing and feature engineering, and training a machine learning model. 
### Duration:
Approximately 3 hours and 20 minutes.
### Project Description:

Diabetes, is a group of metabolic disorders in which there are high blood sugar levels over a prolonged period. In this project we are trying to predict if a patient has diabetes or not based on certain measures using machine learning model. Supervised learning techniques and data visualization tools are used to communicate the insights gained from the analysis.

The data set for this project is the "Diabetes" dataset from the National Institute of Diabetes and Digestive and Kidney Diseases 
The project involves the following tasks:

- Exploratory data analysis and pre-processing: import all required libraries and clean the data sets, analyze and visualize the relationships between the different variables, handle missing values and outliers, and perform feature engineering as needed. There are 9 columns in the data set & 768 rows. After exploring data set we found out that there are some missing vales in the dataset, those were replaced by median values. Histograms, box plot & heatmap is used for data visualization. Evaluation of predictor variable is also done for patients with and without diabetes. 

We used hist plot to see the distribution of the datasetData. The best way for analysis of the dataset is in the graphical structure which in turn lets us know the range of the data. 

- Some findings from data : 
    1. Average Glucose level for with diabetes 141 & without 109.
    2. Average BMI with diabetes 35 & without 30.
    3. Average age is 33.
    4. Average Insulin with diabetes 100 & without 68.
Note : Based on BMI & Glucose data is divided into new categories.

-	Supervised learning: Two models were selected and compared, Random Forest & Decision Tree. We used Random forest model for prediction with the accuracy of 0.76, using appropriate evaluation metrics such as accuracy, precision, recall, F1-score.

Random Forest - In our confusion matrix we can see that, we have 71% precision for predicting diabetes. Its accuratley predicating for diabetes. We can see 82% were accurately predciated didn't have diabetes. Our model captured 66% of all true diabetics. This model has a better precision and recall as compared to decision tree.

Decision Tree - In our confusion matrix we can see that, we have 60% precision for predicting diabetes. Its accuratley predicating for diabetes. We can see 77% were accurately predciated didn't have diabetes. Our model captured 58% of all true diabetics. 

Random Foreset is preferred model for predicting diabetes. Random Forest model had a higher recall, we would rather have lower false negatives to capture as many potential diabetices as possible so they can be diagnosed. 

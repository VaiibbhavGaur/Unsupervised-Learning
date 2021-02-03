# Objective:  
Predict the Bankruptcy from Qualitative parameters from experts

## Domain:  
BFSI  

## Data Description:  
Data contains details of some decision rules which can help in predicting  
qualitative bankruptcy.  

## Attribute Information:  
(P=Positive,A-Average,N-negative,B-Bankruptcy,NB-Non-Bankruptcy)
1. Industrial Risk: {P,A,N}
2. Management Risk: {P,A,N}
3. Financial Flexibility: {P,A,N}
4. Credibility: {P,A,N}
5. Competitiveness: {P,A,N}
6. Operating Risk: {P,A,N}
7. Class: {B,NB}  

## Learning Outcomes:
● Exploratory Data Analysis
● Clustering
● Supervised Learning ( SVC)  

## Steps and tasks:  
1. Read the dataset and understand the features and target variable.  
2. Encode independent features. You can use manual encoding.  
3. Separate the dependent variable (class) from the data.  
4. Check distribution of target column and independent features and
comment your findings.  
5. Apply KMeans or hierarchical clustering algorithm on the above data.  
6. Select optimal number of clusters and form clusters of the data.  
7. Create a new column in the data and populate it with the cluster
labels.  
8. Split the data into train and test set.  
9. Apply SVC model on train dataset and predict target for test dataset.  
10. Check accuracy and confusion matrix.  

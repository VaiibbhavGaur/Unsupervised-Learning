# Title: 
Qualitative_Bankruptcy database

## Objective:  
Predict the Bankruptcy from Qualitative parameters from experts

## Domain:  
BFSI  

## Data Description:  
Data contains details of some decision rules which can help in predicting  
qualitative bankruptcy.  

## Number of Instances: 
250 
 
## Number of Attributes:  
6, each corresponding to Qualitative Parameters in Bankruptcy  

## Attribute Information:  
(P=Positive,A-Average,N-negative,B-Bankruptcy,NB-Non-Bankruptcy)
1. Industrial Risk: {P,A,N}
2. Management Risk: {P,A,N}
3. Financial Flexibility: {P,A,N}
4. Credibility: {P,A,N}
5. Competitiveness: {P,A,N}
6. Operating Risk: {P,A,N}
7. Class: {B,NB}  

## Internal Risks:  
i.Industry risk (IR) : 
	Government policies and International agreements, 
	Cyclicality, 
	Degree of competition,				
	The price and stability of market supply,
	The size and growth of market demand,	
	The sensitivity to changes in macroeconomic factors,
	Domestic and international competitive power, 
	Product Life Cycle.
ii.Management risk(MR): 
	Ability and competence of management, 
	Stability of management,
	The relationship between management/ owner, 
	Human resources management, 
	Growth process/business performance, 
	Short and long term business planning, 
	achievement and feasibility. 
iii.Financial Flexibility(FF): 
	Direct financing, 
	Indirect financing, 
	Other financing 
iv.Credibility (CR):  
	Credit history,  
	reliability of information, 
	The relationship with financial institutes.
v.Competitiveness (CO):  
	Market position, 
	The level of core capacities, 
	Differentiated strategy, 
vi.Operating Risk (OP):  
	The stability and diversity of procurement, 
	The stability of transaction, 
	The efficiency of production, 
	The prospects for demand for product and service, 
	Sales diversification,
	Sales price and settlement condition, 
	Collection of A/R,
	Effectiveness of sale network.
 
7. Missing Attribute Values: None
 
8. Class Distribution: [143 instances For Non-Bankruptcy] [107 instances For Bankruptcy]
        Information about the dataset
  	CLASSTYPE: nominal  
    
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

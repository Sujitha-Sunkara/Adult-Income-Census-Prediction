# Adult-Income-Census-Prediction

## Domain:
Income of US Citizes, Census Bureau

Objective:
The goal here is to predict wether a person has an income of more than 50k or not. This is basically a binary classification problem where a person's salary is classified into the two groups
50K group or <=50K group,
as well as to detect patterns in the dataset utilizing Association rules. This allows us to estimate things like the profitability of establishing a business in a place based on average income, 
Real Estate preferences, and bank loan eligibility for a certain person. Furthermore, we can determine what types of tourist attractions a given socioeconomic group would want to visit, as well as whether that person's children would choose a public or private institution in the future.


Source :

https://www.kaggle.com/uciml/adult-census-income

This data was extracted from the 1994 Census bureau database by Ronny Kohavi and Barry Becker (Data Mining and Visualization, Silicon Graphics). 
The prediction task is to predict whether income exceeds $50k per year based on the provided. census data provided above. 
The Datasets consists of a list of records , each of which explains various features of a person along with his income per year.

A brief description of the features are as follows: Attributes: income (Target Variable): >50K, <=50K Predictors :-

age: continuous workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay,
Never-worked fnlwgt: continuous education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, 
Preschool education-num: continuous marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, 
Married-AF-spouse occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, 
Armed-Forces relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black sex: Female, Male capital-gain: continuous 
capital-loss: continuous hours-per-week: continuous 
native-country: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, 
Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands

## Data Preprocessing  :  
 1.Null velaues were detected and found nul values is from categorical columns and Null velues were dropped. 
 2. Unnecessary columns were dropped
 3. Feqture scaling is performed to normalise the independent variables
 4. Corelation between variables is performed
 
## Machine Learning models

1. Logistic Regression
2. Random Forest
3. Decision Tree classifier models were performed to find the performance metrics

Evaluation
To measure model performance, model assessment metrics are necessary. The assessment measures used are determined by the machine learning activity at hand (such as classification, regression, ranking, clustering, topic modeling, among others). Some measures, such as precision-recall, may be used to a variety of jobs.

Classification Metrics include the following scores

1.Classification Accuracy

2.Confusion Matrix

3.F1 score on test

4.Precision

5.Specificity

6.Recall

1.Classification Accuracy: Accuracy is a common evaluation metric for classification problems. It’s the number of correct predictions made as a ratio of all predictions made. We use sklearn module to compute the accuracy of a classification task

2.Confusion Matrix A confusion matrix provides a more detailed breakdown of correct and incorrect classifications for each class.The diagonal elements represent the number of points for which the predicted label is equal to the true label, while anything off the diagonal was mislabeled by the classifier. Therefore, the higher the diagonal values of the confusion matrix the better, indicating many correct predictions.

3.Area under Curve (AUC) Area under ROC Curve is a performance metric for measuring the ability of a binary classifier to discriminate between positive and negative classes.

4.F-Measure F-measure (also F-score) is a measure of a test’s accuracy that considers both the precision and the recall of the test to compute the score. Precision is the number of correct positive results divided by the total predicted positive observations.

5.Recall, Itis the number of correct positive results divided by the number of all relevant samples (total actual positives).
 
 Evaulation scores & Performance metrics obtained in our model:
 Accuracy on test: 0.8317586606994861 

F1 score on test: 0.6230969179353881 

Precision : 0.7214101461736887 

Specificity : 0.9280479680213192 

Recall : 0.5483660130718955 

ROC AUC Score :  0.7382069905466073

## Conclusion:

Finally, we forecast if a person earns more than $50,000 per year based on the dataset.




# IRIS-data-set
Prediction of class of Iris plant (Classification)

## Introduction
This project is aimed to train a prediciton model to predict type of Iris plant.

## Data Sets
- Source: [Iris Data Set](https://archive.ics.uci.edu/ml/datasets/Iris)
- Data set is of 150 record with 4 dependent variables and one independent variable.

### ***Description of Data Variables:***
**Train Data:**
| Variable | Definition |	         Key                       |
| -------- | ---------- | ---------------------------------- |
| Sepal length| Numerical variable (Continuous)|
| Sepal width | Numerical variable (Continuous)	  |
|Petal length| Numerical variable (Continuous)|
|Petal width	 |Numerical variable (Continuous)|
| Class | Categorical/Qualitative variable (Nominal)|

## Research Problems
***Problems we want to solve:***
We want to predict a plant with given features will fall into which category of Iris plants.
We will be using Classification model since our label is Nominal.
- Data Cleaning
- Data Transformation
- Data Reduction

## Potential Solutions
To build prediction models, we need to go for required preprocessing as per the model:
1. Data Cleaning: We need to take care of the noisy data and missing values if any. For missing values
in Nominal features, we can use below mentioned techniques:
- Use the most frequent value to fill in missing values of that attribute
- Use the most frequent value belonging to the same class to fill in the missing values
- Build a prediction model (Classification – in case of Nominal feature) to predict missing values
(if the feature is extremely important).
2. Data Transformation: If required.
3. Data Reduction: We need to take care of the unnecessary columns in the data set which have
very less correlation with the label and eventually drop them.
There will be various other issues while creating our prediction models. For example,
corresponding to every prediction model we need to incorporate different preprocessing
techniques. Naïve Bayes will consider Nominal values whereas KNN will consider Numerical
features, hence corresponding to every model, we need to do preprocessing and finally create
prediction model.

## Evaluations
We will use Accuracy metric for our Evaluation purpose.

## Expected Outcomes
Expectedly, we will build a machine learning prediction model which will predict the class of Iris plant.

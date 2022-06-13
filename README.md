# Neural_Network_Charity_Analysis

## Purpose
The purpose of this analysis is to predict which loans are successful using Neural Networks and Deep Learning

## Analysis
---
### Data Preprocessing
The target variables for this analysis is "IS_SUCESSFUL" and then the features are: APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'STATUS', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS' and 'ASK_AMT'. The variables that are irrelveant are "EIN" and "NAME" which are removed.

### Compiling
While compling I made four hiden layers with 80, 30, 20, then 15 neurons respectively in each layer. I chose to use the LeakyReLU for the hidden layers with the Sigmoid ufnction with the output layer. I chose the neruon and layer configuration because this seemed to give me the best results as well as the LeakyReLU. I was not able to achieve model performance coming short at 73.85% accuracy. Steps I took to try and increase model performance was to increase the layers and amount of neruons used in each layer as well as reducing the amount of epochs used. I also increased the bin limit for CLASSIFICATION variable to 4000 attempting to take out the outliers in the data. 
![image](https://github.com/evanbruno617/Neural_Network_Charity_Analysis/blob/main/Resources/keras.png)

---

## Results
The results of this model isn't the best falling short of the 75% goal however there are other methods to attempt to achieve this accuracy using similiar approach such as a logisitc regression model using randomForest to classify the data. 

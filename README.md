# Mobile-Price-Prediction
Prediction of mobile prices based on phone hardware specifications.

## Problem Statement: 

The client plans to start a mobile phone company. He wants to give tough fights to big companies such as Apple, Samsung, Huawei and others. However, the cient now faces a problem to set the price of the mobile phone. 

In order to set a reasonable price, he needs to predict the price of the mobile phone based on the features of the mobile phone. Hence, the client has collected the sales data of mobile phones of different companies. He cannot simply set a price for the mobile phone because the price is the main consideration for many people when buying a mobile phone. He needs to figure out the relationship between features of a mobile phone(eg:- battery power, RAM etc) and its selling price. 

To solve this problem, he decided to approach us to help him using Machine Learning techniques. In this problem we are predicting the price range indicating how high the price should be relative to the competition instead of the actual prices.

## Summary:

The dataset is obtained from Kaggle - titled 'Mobile Price Classification', uploaded by Abhishek Sharma.<br>
The dataset is widely used, with over 1500 code submitted, though not all are complete models.

In one model, Gulsah Demiryurek used SVM to predict the price range, employing cross validation and GridSearchCV to refine her model. The final model performed with 96.44% accuracy on training data and 93.75% on test data.

Feri Haldi Tanjung wrote a multiclass classification using 5 models with a resulting accuracy score of 93%. He improved upon his initial code by creating a feature importance graph for the models, which showed RAM, Power Battery, Height and Width as the most important features, then updating these features in the models. He concluded that Extra Tree Classifier with feature selection possessed the best condition for classifying (No overfitting or underfitting).

Vikramaditya Singh Bhati concluded in his exploration that KNN and Linear Regression performed the best among his models. KNN returned a score of 93% while LR had a score of above 90%.

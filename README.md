# Predicting House Prices

### Conclusion

We can see that our blended predictions had an **r2 score of 0.969781 on the train set** and a **root mean squared error of 13,810 dollars on the original scale.** Our best performing individual model was the Lasso model with an **r2 score of 0.914418** and a **root mean squared error of 18,919 dollars on the original scale**. We will use the blended model to make predictions on the test set and submit those predictions to the kaggle competition.

Below we can see a summary of the performance of all the models:

![image.png](attachment:fa20cc19-a9c2-4c31-96d3-792fc2a93878.png)

Looking the feature importance for the Lasso and Ridge models we can conclude that the characteristics most important to the house price are related to **the size of the house, the size of the land and the quality of the house**.

In the kaggle competition my submission got a score of **0.13205**. This placed me in position 925 out of 3869 teams **(top 24%)**

### Project Goal
In this project I want to use regression models (lasso regression, ridge regression, decision trees regressor, xgboost and a combined model) to build a model that predicts house prices based on the characteristics of a house. I want to compare the r2 scores on validation sets for the different models to see which performs the best and create a combined prediction using all the models to submit to the kaggle competition. 

I also want to look at what characteristics are considered most important when it comes to predicting house prices.

### Data Source
The data can be found with detailed descriptions for the features at: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data


### Acknowledgements

Here are some other projects that helped me with this project.

https://www.kaggle.com/code/apapiu/regularized-linear-models

https://www.kaggle.com/code/lavanyashukla01/how-i-made-top-0-3-on-a-kaggle-competition/notebook

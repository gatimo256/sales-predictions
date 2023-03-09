# Sales Pedictions

Using Machine Learning models like linear Regression and  to make Item Sales predictions and based on item and outlet features

# An overview of the project

This sales prediction spans 5 parts in 2 notebooks with data cleaning, data visualization and machine learning models like linear regression and random forest which were used to predict the sales.

# Relevant insights from the data.

The heatmap below shows that there is a moderate correlation between Item Outlet Sales and Item Maximum Retail Price (Item_MRP). Most of the features have very low correlation with the Item Outlet Sales that we are trying to predict.

![alt text](https://github.com/gatimo256/sales-predictions/blob/f897128aac4d6f4186e0c48a282239d9964bf9c2/Item%20Sales%20Correlation%20HeatMap.png)

The graph below shows that Fruit's and Vegetables and Snack Foods had the most sales compared to the rest of the Item Types. 

![alt text](https://github.com/gatimo256/sales-predictions/blob/f897128aac4d6f4186e0c48a282239d9964bf9c2/Item%20Type%20Sales%20Bar%20Graph.png)


# Summary of the model and its evaluation metrics

After using a Linear Regression Model and Random Forest Model to predict, the best choice appears to be Random Forest Model for prediction. After evaluating the model using the R^2 score,the model can explain 55% of the variation in the test data. 

The Linear Regression Model had a larger RMSE 2463741878196.166 compared to the Random Forrest Model RMSE of 1113.0555230597365

These results showed that the Random Forest Model performed better than the Linear Regression model.
Its also possible to tune the Random Forest Model to get better results at a later date.

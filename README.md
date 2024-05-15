# Predicting-Taxi-Fare-using-PySpark
Predicting Taxi Fares for Chicago Taxi Rides (over 20 million observations) in 2016 using pyspark.ml libraries. <br /> <br />
Main objective is to forecast taxi fare based on trip time and trip distance. I built and evaluated the following models: Linear Regression with Elastic Net Regularization, Decision Tree, Random Forest, Gradient-Boosted Tree, and K-Means Clustering. Evaluation of models used root mean square error and r-squared.  <br /> <br />
My best models were the random forest and gradient-boosted tree models, both achieving a RMSE of 3.77 and a R2 of 0.91. For comparison, the decision tree model yielded RMSE: 4.25 and R2: 0.89. The linear regression model performed the worst with scores of 5.64 and 0.80 for RMSE and R2 respectively. Finally, I found 3 centroids to be optimal for k-means and plotted the groups (can be seen in the ppt). <br /> <br />
In the Code folder, ChicagoTaxiTrips.ipynb and .html are the code file and rendered html output respectively. <br /> 
The rendered html can be seen here: https://html-preview.github.io/?url=https://github.com/KevinWa3/Predicting-Taxi-Fare-using-PySpark/blob/main/Code/ChicagoTaxiTrips.html. <br /><br />
ChicagoTaxiTrips.pptx is the presentation of results. The ppt can be viewed without downloading by clicking "View raw." <br /> <br />
Dataset from: https://www.kaggle.com/datasets/chicago/chicago-taxi-rides-2016. 

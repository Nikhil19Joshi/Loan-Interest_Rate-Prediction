# Loan-Interest_Rate-Prediction
- This project was a part of data mining course assignment at the University of Chicago.

## DATA:
- Data is a masked data of a bank which is close to real world data. Metadata.csv contains the descriptions of the features. Size of the file is large which is why it is not possible to upload. Moreover, I have attached an HTML file in addition with python notebook for ease of reading.

## Assignment Instructions:

**Step 1:** Clean and prepare your data: There are several entries where values have been deleted to simulate dirty data. Please clean the data with whatever method(s) you believe is best/most suitable. Note that some of the missing values are truly blank (unknown answers) and thus may be impossible to clean; use your discretion.

**Step 2:** Build your models: Please build machine learning/statistical models in Python to predict the interest rate assigned to a loan. When writing the code associated with each model, please have the first part produce and save the model, followed by a second part that loads and applies the model.

**Step 3:** Test your models using the data found within the **"Holdout for Testing.csv" file**. Save the results of the final model (remember you will only predict the first column in holdout test set with your best model results) in a single, separate CSV titled "Results from" *insert your name or UChicago net ID.

**Step 4:** Submit your work: Please submit all of your code for cleaning, prepping, and modeling your data, your "Results" file, a brief write-up comparing the pros and cons of the modeling techniques you used (no more than a paragraph). Your work will be scored on techniques used (appropriateness and complexity), model performance - measured by RMSE - on the data hold out, an understanding of the techniques you compared in your write-up, and your overall code.

## Models Applied  
- This is a Supervised Machine Learning Problem as we have labels with us which are "Interest Rate" column. Our data seems to be Linearly distributed which is why it is a Regression probelm. We have tried to apply below ML models into our problem and have also tried to Cross validate our models.  
1) Linear Regression (Test_RMSE: 1.94, CV_RMSE: 1.95, Train_RMSE: 1.95)  
2) Decision Tree Regressor (Test_RMSE: 2.14, CV_RMSE: 2.14, Train_RMSE: 2.14)  
3) Random Forest (Test_RMSE: 2.48, CV_RMSE: 2.44, Train_RMSE: 2.44)  

## Result
- As can be seen from above RMSE and CV scores Linear Regression model performed the best because of low scores and was selected as the best model.

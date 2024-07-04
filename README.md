# Employee Attrition Prediction

This model is about predicting weather employ will leave or stay in company in long run based on various factors.

## Steps:

1. Imported neccesary modules we will need for this project.
2. Imported data and saved in variable called df.
3. Converted the target variable "attrition" to 1 and 0  instead of Yes and No.
4. Identified Catergorical and numerical columns using select.dtype function.
5. Preprocess the data using ColumnTransformer to scale the numerical values and Encode the categorical values.
6. Spliting the data for training.
7. Created Logistic regression model.
8. Evaluated model Performance.
9. Created RandomForest model to check if we can improve the model performance.
10. Evaluated the RandomForest model.
11. Saving the model in our local device.




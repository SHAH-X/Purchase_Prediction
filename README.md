# Purchase_Prediction
Predictive Analytics

* Objective : Minimize business cost by avoiding fruitless calls to individuals who aren't interested in the product.

* Dataset : A Financial Product's marketing campaign dataset in a CSV format was used having around 4000 records and 16 features. 

* Tools and Models Used : This project was completely using Python. The models implemented in the project were Logistic Regression, K-Nearest Neighbours, Decision Tree, Random Forest and Naive Bayes.

* Data Pre-processing : The data was checked for collinearity and cleaned after performing outlier analysis. Label encoding and one-hot encoding techniques were used to convert categorical data to numerical data. The values were standardized before using it with models. Applied feature engineering to identify most important features using decision tree. The most important features were used for model training.

* Model Evaluation : Confusion matrix was used to evaluate the performance metrics (accuracy, precision, sensitivity, specificity) of all the models. The model with highest 'Precision' was selected, as required for the business objective.

* Result : Random Forest Model performed the best out of all models. The model was then trained and deployed for use. The model performed on actual test set with an accuracy of 83.5%.

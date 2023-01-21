Problem statement: Ola wants to predict if an employee will be leaving the company based on the attributes of the employee.
Dataset: We are provided with data of the drivers .The target variable in the dataset is "Last working date" which is null if he/she has not left the company yet. We will be using this dataset to draw meaningful insights and predict if an employee will churn based on the given date.
The features present in the dataset are: MM-YYYY,Driver_id,Age,Gender,city,education_level,income,date of joining,last working date(target),joining designation,grade,total business value,quarterly rating.
Steps: The steps involved in this project are data loading,non graphical analysis , graphical analysis(univariate and bivariate),missing values and outlier detection,handling missing values using knn imputation,feature engineering,splitting the training and test data,hyperparameter tuning,building the decision tree classifier using bagging and boosting,evaluating the model performance,oversampling the data due to imbalance in the dataset and building the model after oversampling.
Pyhton libraries used: Pandas,Numpy,Seaborn,Matplotlib,sklearn,imblearn
Models built: Baggingclassifier,XGBoost,ADAboost,Gradientboosting classifier
Metrics used to evaluate the model: ROC-AUC curve,classification report

Important Note: The insights and comments are mentioned under each visualization in the ipynb file. Recommendations are mentioned at the end of the code.

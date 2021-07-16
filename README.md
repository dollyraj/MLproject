# MLproject
Loan eligibility prediction model created with Machine Learning algorithm in python.
loan-train.csv contains training data and loan-test.csv contains testing data.
As data was not fit for directly creating predictive model from the given data, i have to preprocess the dataset .
1)List out the features name ,their datatypes,number of unique values and number of null values in each of the columns int training dataset.
2)List out the total number of data present in dataset.
3)Null values is replaced with mean and mode of training data
4)categorical values is converted to numerical values

I have used logistic regression model. After fitting data into model , got an accuracy of 80.94 percentage. And after comparing coefficient of each feature it is clear that 'credit_History' is the most important feature for getting home loan.

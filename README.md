# Problem Statement

* There are a lot of customer on a company's InvestorAI platform. Whenever they login in their app and view anything, they get pings from their mobile phone indicating that the customers are using the app. 
* Provided with 4 weeks of sample data : 3 weeks of training data and 1 week of test data. 
* Training data contains id, gender, age, number of kids the customer has and all the pings that have been received (during the training data period). 
The task is to predict how many hours the customer will be online / using our app on a given day. So the test data contains customer id, and date (during the test data period). The test data also contains the actual online hours, which is what your model should predict. 
* Root Mean Squared Error or RMSE should be the metric for evaluation.

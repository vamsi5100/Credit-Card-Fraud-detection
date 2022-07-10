# Credit-Card-Fraud-detection
1.	Problem Statement:

      At present many bank customers that use credit cards were unnecessarily losing money for which they didn’t pay from credit cards. So, it is essential to detect those fraudulent transactions that are being done. In this case, machine learning plays a vital role to be able to detect fraudulent transactions using various machine learning algorithms. In this project we try to detect fraudulent transactions using machine learning.

2.	Market/Customer/Business Need Assessment:

   In banks manually trying to detect fraudulent transactions is very tough as we see fraudulent transactions every day and requires more employees in the job which results high cost revenue for salary payments for the company but if we use some machine learning classifier to do the specific job it can save a lot of money and manpower. 

3.	Target Specifications and Characterization:

    Our target specifications are small banks which have more credit card customers as there is a lot of fraudulent data present.

4.	External Search (information source / references):

For this project I used credit card fraud dataset from Kaggle.
Link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
References : https://www.geeksforgeeks.org/ml-credit-card-fraud-detection/,
                        https://towardsdatascience.com/credit-card-fraud-detection-using-machine-learning-python-5b098d4a8edc

5.	Benchmarking alternate products:

    We need to do benchmarking in order to check how efficient the fraud detection model was performing. We can assume some bench markings like number of fraudulent transactions per day the model is detecting, amount of customers’ money that’s being saved by the model and also the amount of revenue that’s being saved from paying salaries to employees.

6.	Patents:

    We can use open source python libraries like pandas, NumPy and scikit learn which are free to use and hence no patents are required.
7.	Applicable Regulation:

•	In order to build a fraud detection model we need a lot of credit cards customers’ transaction data in which many banks try to maintain the information confidential and there is a chance of marking this as a crime as we are seeing into confidential data.

8.	Applicable Constraints:

•	Requires a lot of computation cost as the data is very high.
•	Needs assistance check for exceptional cases and to take care and store the data as even a little amount of data is very essential.
•	Refunding the fraud transaction money.
•	Needs high data storage facility to store the data.

9.	Business Opportunity:

•	Get rid of fraudulent transactions as many as possible to get customer satisfaction.
•	Reduce the interest rate of credit cards for a particular amount of time to get more credit customers.
•	 Taking care of fraudulent transactions over time and done with it as fast as possible as customer satisfaction is important.

10.	Concept generation:

     As day to day life goes on we have many financial problems in our life and in that financial crisis some times some of our money gets deducted for no reason and in order to get rid of this problem I thought about the idea of building credit card fraud model. 

11.	Concept development:
   
•	Once the model is trained we perform cross validation for the checking of generalization of model and when get a accurate model we save that model.
•	The banks’ website should be able take the date and time of fraud transaction and the transaction id and the account name.
•	Keep track on each and every customers’ transactions data separately.
•	Giving a pre-warning to the customers where the scenario of fraud detection is being detected.

12.	Final Product Prototype:











13.	Product details:

	How does it work?

•	When we go to the website the employee takes the customer reports about the transaction and run the data on the model and identify the fraud transactions and saves the incoming data and retrain the model in a cycle so that the model can identify frauds more accurately.
	Data Sources:

•	Kaggle: : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
	Algorithms, Frameworks, and Software needed:

•	Used machine learning algorithms like Logistic Regression, Decision trees and ANN.
•	For deploying the model we need Flask framework because its easy to implement and simple.
•	Needed libraries like TensorFlow, Keras, Pandas, NumPy , scikit learn, matplotlib and seaborn etc
•	For storing and implementing the new data we need cloud services like AWS.
	Team required to develop:

•	For data pre-processing, model building and training we need a data scientist and a machine learning engineer.
•	For deploying the saved model we need full stack developer.
•	For continuous incremental and implementation of data we need MLOps engineer.
•	For data storage we need cloud engineer.

14.	Conclusion:

     Credit  card  fraud  is  without  a  doubt  an  act  of  criminal dishonesty. Handling this type of problem is beneficial to both the credit card customers as well as the company. So, we can definitely say that machine learning played a vital role in the field of business sector and is also very helpful in other sectors like food tech, tourism chatbots etc.


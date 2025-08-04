# Building a Decision Tree to Predict Customer Churn
Imagine you are a data analyst at a telecom company. The marketing department has noticed an increase in customer churn and needs your help to identify which customers are most likely to leave next month.  
In this exercise, you will build a decision tree model to predict customer churn for a telecom company. **Customer churn** refers to when a customer stops doing business with a company. Predicting churn is crucial for businesses to retain customers by addressing their issues proactively.  
## Dataset Description
We will use a synthetic dataset for this exercise. The dataset contains the following columns:  
1. **CustomerID**: A unique identifier for each customer.
2. **Age:** The age of the customer.
3. **MonthlyCharge:** The monthly bill amount for the customer.
4. **CustomerServiceCalls:** The number of times the customer contacted customer service.
5. **Churn:** This is our target variable, indicating whether the customer churned (Yes) or not (No).
## Step-by-Step Instructions  
1. ### Setup the Environment:
Import necessary libraries: Pandas for data manipulation, Scikit-learn for machine learning, and Matplotlib for visualization.  
### 2. Create the Dataset:
Use Python to create a synthetic dataset. We'll make a small dataset for simplicity.  
### 3. Data Preparation:
Split the data into features (X) and the target variable (y).
Further split the dataset into training and testing sets.
### 4. Build the Decision Tree Model:
Use Scikit-learn to create a DecisionTreeClassifier.
Train the model on the training data.
### 5. Evaluate the Model:
Make predictions on the test set.
Calculate the accuracy of the model.
### 6. Visualize the Decision Tree:
Use Matplotlib to visualize how the decision tree makes decisions.
### 7. Discuss the Results:
Interpret the decision tree.
Discuss how it can be used by the company to reduce customer churn.  
  
  With this exercise, you will gain hands-on experience in building and evaluating a decision tree model. You will also understand how machine learning can provide actionable insights to help businesses make informed decisions, such as reducing customer churn.

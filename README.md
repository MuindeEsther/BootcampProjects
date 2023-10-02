# BootcampProjects
This repository contains projects i did during Lux Academy Bootcamp
## Project Option 2
Imagine you're working with Sprint, one of the biggest telecom companies in the USA. They're really keen on figuring out how many customers might decide to leave them in the coming months. Luckily, they've got a bunch of past data about when customers have left before, as well as info about who these customers are, what they've bought, and other things like that. So, if you were in charge of predicting customer churn, how would you go about using machine learning to make a good guess about which customers might leave? What steps would you take to create a machine learning model that can predict if someone's going to leave or not?
**Customer Churn** also known as customer attrition or customer turnover, refers to the rate at which customers stop doing business with a company or cease using its services during a specific period

Predicting churn is a critical task for telecom companies. Using machine learning, particularly XGBoost algorrithim, can help create a predictive model to identify customers at risk of leaving. Here's step by step process for building a customer churn prediction model with XGBoost:

### 1. Data Collection

Collect historical customer data, including features such as customer demographics (age, gender, location), subscription details (plan type, contract length), usage patterns (call duration, data usage), customer service interactions, and past churn history. You may also need data on customer satisfaction surveys if available.

### 2. Data Preprocessing
*  Clean and preprocess the data by handling missing values, outliers, and duplicates.
*  Encode categorical variables (e.g., one-hot encoding or label encoding) into numerical formats.
*  Split the dataset into training and testing sets for model evaluation.

### 3. Feature Engineering
Create relevant features that may influence customer churn. For example, we will calculate metrics like customer lifetime value (CLV), customer tenure, and average monthly usage.

### 4. Exploratory Data Analysis
We will conduct EDA to gain insights into the data and identify patterns, correlations, and potential factors contributing to churn.

### 5. Model Selection
We will choose XGBoost as the machine learning algorothim for churn prediction.
XGBoost is a powerful gradient boosting algorithm known for its high predictive accuracy and ability to handle complex datasets.

### 6. Model Training
* Train the XGBoost model on the training dataset. Define the target variable as "churn" (1 for churned customers, 0 for non-churned customers).
* Tune hyperparameters, such as learning rate, maximum depth, and the number of trees, using techniques like cross-validation to find the best model configuration.

### 7. Model Evaluation
WE will evaluate the model's perfomance on the test data using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC
We will anlyze iportant scores provided by XGBoost to understand which features have the most significant impact on churn prediction.

### 8. Interpretation
Interpret the model results to understand which customer attributes or behaviors are strong indicators of churn. This insight can inform marketing and retention strategies.

# Decision-Tree-Project-ML 

  Project Goal
This project aims to build a complete Decision Tree Classification Model using a structured workflow. The purpose is to identify the key patterns in the dataset, run Exploratory Data Analysis (EDA), perform Feature Engineering, train a Decision Tree model, evaluate it, and finally allow users to test predictions.



 # 1. Exploratory Data Analysis (EDA)

The first step is understanding the dataset. In this phase, we:
Inspected the shape, missing values, and data types
Visualized the target variable distribution
Examined relationships using countplot
Explored categorical variables and their relationship with the target

Goal of EDA:
To understand the structure of the data, detect imbalance, find important features, and prepare for Feature Engineering.

 # 2. Feature Engineering

This step prepares the dataset for modeling. It included:

Handling missing values
Dropping duplicated or unnecessary columns
Encoding categorical variables (Label Encoding, One-Hot Encoding)
Generated a correlation poxplot for numerical features
Scaling numerical features when necessary

Goal of Feature Engineering:
To transform raw data into a clean, machine-learning-ready format that improves model performance.

 # 3. Building the Decision Tree Model

In this phase, we:

define the target and feature
Split the dataset into training and testing sets
useing the randomizedsearchCV to select the pest hyperparamere 
Built a Decision Tree using:
Criterion: Gini Index or Entropy ,Max depth tuning ,Minimum samples for split and leaf

Trained the model on the training set

Goal of Model Building:
To create a Decision Tree capable of learning patterns and making accurate predictions.

# 4. Model Evaluation

We evaluated the model using:

Accuracy Score : Accuracy was good around 85% and that is mean it can detect patrterns effectively

Feature Importance analysis and we found that the most influential featurs MonthlyIncome _ Total Working Years  _  Marital Status            
Stock Option Level  _ Distance From Home  _ Age           

Goal of Evaluation:
To measure how well the model predicts and identify strengths and weaknesses.

# 5. User Testing

The project allows user interaction the model 

🚀 Conclusion

This project demonstrates the complete workflow of building a Decision Tree classifier, starting from raw data to a fully functional predictive model.
It serves as a practical example of how machine learning models are developed in real-world applications.

project related file 
DICSION TREE CODE  contains the full code for execution 
employee attration the datast

the data source is from kaggle

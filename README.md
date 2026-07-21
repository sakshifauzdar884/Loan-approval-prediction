# Loan-approval-prediction
A machine learning project that predicts whether a loan will be approved, based on income, credit history, and loan amount. Built using Python, Pandas, and scikit-learn. Includes data cleaning, basic charts, and a Logistic Regression model to make predictions.

What This Project Does:
- Loads real loan application data
- Cleans the data (fills in missing values)
- Explores the data with simple charts (EDA)
- Converts text columns into numbers so the model can understand them
- Trains a Logistic Regression model
- Checks how good the model is (Accuracy, Precision, Recall, Confusion Matrix)

Tech Stack:
- Python
- Pandas – for loading and cleaning data
- NumPy – for numerical operations
- Matplotlib – for charts
- scikit-learn – for the machine learning model

Dataset Information:The dataset (loan_approval_dataset) has 614 real loan applications.
Target:- Loan_Status — Y (Approved) / N (Rejected)
Features:- Gender, Married, Dependents, Education, Self_Employed, ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term, Credit_History, Property_Area

Machine Learning Model:
Algorithm Used:- Logistic Regression
Workflow:-
- Load dataset
- Handle missing values
- Encode categorical variables
- Split data into training and testing sets
- Train Logistic Regression model
- Generate predictions
- Evaluate model performance

How to Run:
- Clone the repository
- Navigate to the project folder
- Install the required libraries
- Open the Jupyter Notebook and run all cells.

Results:
- Accuracy: ~79%
- Key finding:Credit History is the strongest factor in whether a loan gets approved — applicants with a good credit history are approved far more often, which   matches how real banks make decisions.

What I Learned:
- How to clean messy, real-world data (filling missing values)
- How to explore data using simple charts before building a model
- How to convert text data into numbers for machine learning
- How to train a Logistic Regression model
- How to evaluate a classification model using Accuracy, Precision, Recall, and a Confusion Matrix

Author
Sakshi Fauzdar

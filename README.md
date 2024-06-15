Dream Housing Finance Loan Eligibility Prediction
Overview
This project aims to automate the loan eligibility process for Dream Housing Finance Company based on customer details. The solution uses a machine learning approach to predict whether a loan should be approved or not based on historical data.

Approach
1. Data Loading
Objective: Load the training and test datasets.
Method: Use pandas to read CSV files containing the datasets.
2. Data Understanding
Objective: Understand the structure and summary statistics of the data.
Method: Inspect the first few rows and use info and describe methods.
3. Exploratory Data Analysis (EDA)
Objective: Perform univariate and bivariate analysis to understand the distribution and relationships between variables.
Method: Use histograms, bar plots, and scatter plots.
4. Data Preprocessing
Objective: Handle missing values and outliers.
Method: Use imputation techniques for missing values and statistical methods to detect and handle outliers.
5. Correlation Analysis
Objective: Visualize correlations between variables.
Method: Use a heat map to display correlation coefficients.
6. Model Building
Objective: Train a RandomForestClassifier and evaluate its performance.
Method: Split the data into training and validation sets, train the model, and evaluate using accuracy score, classification report, and confusion matrix.
7. Feature Engineering
Objective: Create new features to improve model performance.
Method: Create features such as TotalIncome, IncomePerMember, and EMI.
8. Hyperparameter Tuning
Objective: Optimize the hyperparameters of the RandomForestClassifier to improve the model's performance.
Method: Use GridSearchCV to find the best hyperparameters.
Results
Initial model accuracy: 0.77
Post-feature engineering accuracy: 0.80
Post-hyperparameter tuning accuracy: 0.79
Team Members
B.Vinitha
B.V.L.Kavya

📊 Personal Loan Acceptance Prediction (Machine Learning Project)

📌 Project Overview
This project focuses on predicting whether a customer will accept a personal loan offer using machine learning classification techniques. The analysis is based on the Bank Marketing Dataset (UCI Repository), which contains demographic, financial, and campaign-related information about customers.
The goal is to help financial institutions identify potential customers who are more likely to accept loan offers.


🎯 Objective
Predict whether a customer will accept a loan offer (yes/no)
Analyze customer behavior based on age, job, marital status, and other features
Build and compare classification models
Extract meaningful business insights from data


📂 Dataset Information
The dataset includes the following features:
age: Age of the customer
job: Type of job
marital: Marital status
education: Education level
default: Has credit in default
housing: Has housing loan
loan: Has personal loan
contact: Contact communication type
month: Last contact month
day_of_week: Last contact day
duration: Last contact duration
campaign: Number of contacts performed
pdays: Days since last contact
previous: Number of previous contacts
poutcome: Outcome of previous campaign
emp.var.rate: Employment variation rate
cons.price.idx: Consumer price index
cons.conf.idx: Consumer confidence index
euribor3m: Euribor rate
nr.employed: Number of employees
y: Target variable (loan acceptance: yes/no)


⚙️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn


🧠 Machine Learning Models
Logistic Regression
Decision Tree Classifier


🔧 Workflow
1. Data Exploration
Analyzed distribution of age, job, and marital status
Visualized loan acceptance trends across different groups
2. Data Preprocessing
Converted target variable (y) into numeric format (yes = 1, no = 0)
Applied one-hot encoding for categorical variables
Scaled features using StandardScaler for Logistic Regression
3. Model Building
Trained Logistic Regression model
Trained Decision Tree Classifier for comparison
4. Model Evaluation
Accuracy Score
Confusion Matrix
Precision, Recall, F1-score


📊 Results
Model Performance:
Logistic Regression Accuracy: ~91%
Decision Tree Accuracy: ~91.5%

Key Insight:
Decision Tree performed slightly better in identifying customers who are likely to accept the loan.

📈 Business Insights
Students and retired individuals show the highest loan acceptance rates
Single customers are more likely to accept loan offers compared to married customers
Older customers (60+) show significantly higher acceptance probability
The dataset is imbalanced, with most customers not accepting loans


🧾 Conclusion
Both models performed well in predicting loan acceptance, but the Decision Tree classifier provided better recall for positive cases, making it more suitable for business use. The analysis also revealed important customer segments that are more likely to respond positively to loan offers.

🚀 Future Improvements
Handle class imbalance using SMOTE
Use advanced models like Random Forest or XGBoost
Add ROC-AUC evaluation
Deploy model using Streamlit or Flask


👨‍💻 Author
Laiba Rehman

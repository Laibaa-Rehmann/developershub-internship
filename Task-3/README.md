📌 Customer Churn Prediction (Bank Customers)

📊 Project Overview
This project predicts whether a bank customer will leave (churn) or stay using machine learning. The goal is to help banks identify high-risk customers early and take actions to improve retention.

🎯 Problem Statement
Banks lose significant revenue when customers leave their services. The objective of this project is to build a classification model that predicts customer churn based on demographic, financial, and account-related features such as age, credit score, balance, and activity status.

📁 Dataset
Dataset: Churn Modelling Dataset
Source: Kaggle
Features:
CreditScore
Geography
Gender
Age
Tenure
Balance
NumOfProducts
HasCrCard
IsActiveMember
EstimatedSalary
Exited (Target variable)

🧹 Data Preprocessing
Removed unnecessary columns (RowNumber, CustomerId, Surname)
Handled missing values (if any)
Encoded categorical variables:
Gender → Label Encoding
Geography → One-Hot Encoding
Scaled numerical features using StandardScaler


📊 Exploratory Data Analysis (EDA)
Key insights from data:
Older customers are more likely to churn
Low balance and low activity increase churn risk
Geography impacts churn behavior
Credit score also influences customer retention

Visualizations included:
Churn distribution
Age vs churn
Credit score vs churn
Correlation heatmap


🤖 Model Building
Two classification models were used:
Logistic Regression
Random Forest Classifier
Random Forest performed better in capturing non-linear patterns in the data.


📈 Evaluation Metrics
Models were evaluated using:
Accuracy Score
Confusion Matrix
Classification Report (Precision, Recall, F1-score)


⭐ Feature Importance
The most important features influencing churn:
Age
Balance
Number of Products
IsActiveMember
Credit Score


🏁 Conclusion
Customer churn can be effectively predicted using machine learning.
Random Forest performed better than Logistic Regression.
Age and account activity are the strongest predictors of churn.
Banks can reduce churn by targeting inactive and high-risk customers.


⚙️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

👨‍💻 Author
Laiba Rehman 

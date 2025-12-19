# Telecom Customer Churn Prediction Project
This project is a Telecom Customer Churn Prediction Web Application built using Python and Streamlit.
It predicts whether a telecom customer is likely to churn (leave the service) based on key customer attributes.

The application loads a pre-trained machine learning model and scaler to make real-time predictions through an interactive user interface.

End-to-end customer churn prediction using Python, EDA, feature engineering, model comparison and machine learning models with Streamlit deployment.

Objective
To help telecom companies identify customers who are at risk of churning so that proactive retention strategies can be applied.

🧠 Features Used for Prediction

The model predicts churn using the following inputs:

Age
Gender
Tenure (number of months the customer has stayed)
Monthly Charges

Project Workflow
1.Data Loading & Cleaning
2.Exploratory Data Analysis (EDA)
3.Feature Engineering & Encoding
4.Feature Scaling
5.Model Training & Comparison
6.Final Model Selection
7.Model Deployment using Streamlit

🤖 Models Compared

Multiple machine learning models were trained and evaluated to identify the best-performing model:
1.Logistic Regression
2.K-Nearest Neighbors (KNN)
3.Decision Tree Classifier
4.Random Forest Classifier
5.Support Vector Machine (SVM)

🔍 Model Evaluation

All trained machine learning models were evaluated using the classification report from scikit-learn.
The classification report provides the following evaluation metrics:
Accuracy
Precision
Recall
F1-score
Support (number of samples per class)

Each model was evaluated using the same metrics, ensuring a fair and consistent comparison of performance across different algorithms.
Based on the results of the classification reports, the best-performing model was selected for deployment in the Streamlit application.

🛠️ Tech Stack

Python
1.Streamlit – for web application
2.NumPy – for numerical operations
3.Joblib – for loading trained model and scaler
4.Scikit-learn – used during model training

1.How to Run the Project
git clone <repository-url>
cd <project-folder>

2.Install Required Libraries
pip install streamlit numpy joblib scikit-learn

3.Run the Streamlit App
streamlit run app.py

4.Open in Browser
Once the app starts, open the URL shown in the terminal (usually):
http://localhost:8501

🧪 How the App Works
User enters customer details (age, gender, tenure, monthly charge).
Input data is scaled using a pre-trained scaler.

The machine learning model predicts churn:
Churn
Not Churn

Result is displayed instantly on the UI.

📊 Model Output
Churn → Customer is likely to leave
Not Churn → Customer is likely to stay

🚀 Future Enhancements

Add more customer features
Display churn probability
Improve UI with charts
Deploy on cloud (Streamlit Cloud / AWS)

👨‍💻 Author
Sanmitra Kamble

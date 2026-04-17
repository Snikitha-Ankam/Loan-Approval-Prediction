# Loan-Approval-Prediction
This project aims to predict whether a loan application will be approved or rejected using machine learning algorithms. The dataset includes personal and financial information of applicants and the loan approval status.
# 📁 Dataset

-Source: Kaggle/Other
-Format: CSV
 -Key Features:
    -Categorical: Gender, Married, Dependents, Education, Self_Employed, Property_Area, Loan_Status <br>
    -Numerical: ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term, Credit_History
# 🧹 Data Preprocessing

-Dropped Loan_ID as it's an identifier.<br>
-Imputed missing values using the most frequent strategy.<br>
-Applied Label Encoding for categorical variables.<br>
-Scaled numerical features using StandardScaler.
# 📊 Exploratory Data Analysis

-Bar plots for categorical feature distributions.<br>
-Heatmap of feature correlation.<br>
-Visual relationship between variables like Gender, Married, and Loan Status.
# 🧠 Machine Learning Models Used
The following models were trained and evaluated:<br>

-Logistic Regression<br>
-Support Vector Classifier (SVC)<br>
-Random Forest Classifier<br>
-K-Nearest Neighbors (KNN)<br>
#🔎 Evaluation Metrics
-Accuracy on training and test datasets
# 🚀 Predicting on New Loan Applications
An example prediction is demonstrated for a new applicant. The model outputs:<br>

-Predicted Class (0 = Rejected, 1 = Approved)<br>
-Predicted Probability of Approval<br>
-Confidence message based on how close the probability is to 0.5
# 🛠️ Technologies Used
-Python 🐍<br>
-Pandas & NumPy<br>
-Scikit-learn<br>
-Matplotlib & Seaborn<br>


# Projects-Machine-Learning
🛡️ Credit Card Fraud Detection – README
📌 Project Description

This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques. The dataset contains highly imbalanced classes where fraudulent transactions are rare. The goal is to build an accurate classification model that can identify fraud while minimizing false positives. The project includes data preprocessing, exploratory data analysis, model building, evaluation, and comparison of multiple ML models.

🔍 Steps Involved
1️⃣ Data Collection
Loaded the credit card transactions dataset.
Identified target variable: Class (0 = Genuine, 1 = Fraud).
2️⃣ Data Preprocessing
Checked missing values and data integrity.
Performed feature scaling using StandardScaler.
Handled data imbalance using SMOTE (if applied).
3️⃣ Exploratory Data Analysis (EDA)
Visualized distribution of fraudulent vs non-fraudulent transactions.
Inspected correlations between features.
Plotted key graphs (histograms, countplots, pairplots).
4️⃣ Train-Test Split
Split the dataset into training (80%) and testing (20%).
5️⃣ Model Building
Built and trained multiple ML models such as:
Logistic Regression
Decision Tree Classifier
Random Forest
XGBoost (optional)
SVM or KNN (optional)
6️⃣ Model Evaluation
Evaluated each model using:
Accuracy
Precision
Recall
F1-score
Confusion Matrix
ROC-AUC Curve
Special focus on Recall, as missing a fraud is more costly.
7️⃣ Model Comparison & Selection
Compared all models.
Selected the best model based on highest recall and AUC score.
8️⃣ Final Fraud Prediction
Used the selected model to predict if a new transaction is fraud or not fraud.

🛠️ Technologies Used
Python
NumPy
Pandas
Scikit-Learn
Matplotlib
Seaborn
Imbalanced-learn (SMOTE)
Jupyter Notebook

🎯 Outcome
Successfully built a machine learning model that detects fraudulent credit card transactions.
Achieved high recall ensuring most fraudulent transactions are correctly identified.

Visualized fraud patterns and gained meaningful insights from EDA.

Compared multiple algorithms and selected the best-performing model.

Final model can be used by financial institutions to reduce fraud losses.

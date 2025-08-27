🛡️ Fraud Detection System (Machine Learning)
📖 Project Overview

This project implements a Fraud Detection System using Machine Learning on the Credit Card Transactions dataset.
Fraud detection is a critical challenge in banking & e-commerce, where fraudulent transactions are less than 1% of the data.

The notebook demonstrates end-to-end Data Science skills including:

Data preprocessing & handling class imbalance

Feature scaling

Model training & evaluation

Performance comparison across multiple models

⚙️ Tech Stack

Language: Python 3

IDE/Notebook: Jupyter Notebook

Libraries:

Pandas, NumPy

Scikit-learn

Imbalanced-learn (SMOTE)

Matplotlib, Seaborn

XGBoost

📂 Dataset

The dataset used is the Credit Card Fraud Detection Dataset from Kaggle:
👉 Dataset Link

Rows: 284,807 transactions

Features: 30 (Time, Amount, and 28 anonymized PCA features)

Target: Class → 0 = Legitimate, 1 = Fraud

🚀 Workflow

Data Loading & Exploration

Checked missing values

Visualized class imbalance (fraud vs. non-fraud)

Preprocessing

Standardized Amount and Time

Applied SMOTE to handle imbalance

Model Training

Logistic Regression

Random Forest

XGBoost

Evaluation

ROC-AUC Score

Confusion Matrix

Precision, Recall, F1-Score

ROC & Precision-Recall curves

📊 Results
Model	ROC-AUC
Logistic Regression	0.971
Random Forest	0.968
XGBoost	0.980 ✅

✅ XGBoost gave the best performance with ROC-AUC of 0.98, while Logistic Regression and Random Forest also performed strongly.

▶️ How to Run

Clone this repository:

git clone https://github.com/vedshukla25/fraud-detection-ml.git


Navigate to project folder:

cd fraud-detection-ml


Install dependencies:

pip install -r requirements.txt


Run Jupyter Notebook:

jupyter notebook Fraud_Detection.ipynb

📌 Future Improvements

Deploy the model using Flask or Streamlit

Perform hyperparameter tuning for better recall

Analyze feature importance for explainability

Try deep learning models (LSTMs/Autoencoders)

👨‍💻 Author

Ved Shukla (@vedshukla25)

📌 Connect with me on LinkedIn
www.linkedin.com/in/ved-shukla25

⭐ If you found this project useful, please give it a star!

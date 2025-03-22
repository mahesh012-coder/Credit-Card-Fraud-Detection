This project detects fraudulent credit card transactions using Random Forest and SMOTE to handle class imbalance. It analyzes transaction data and classifies transactions as legitimate or fraudulent with high accuracy.

Credit_Card_Fraud_Detection.ipynb  # Google Colab/ Jupyter Notebook

📊 Dataset Details
Source: Kaggle - Credit Card Fraud Detection
Size: 284,807 transactions (0.17% fraud cases)
Features(columns):
* Time, Amount (Transaction details)
* V1 to V28 (PCA-transformed features)
* Class (0 = Legitimate, 1 = Fraudulent)

⚡ Features
✔ Exploratory Data Analysis (EDA) – Fraud distribution visualization
✔ Data Preprocessing – Handling missing values, feature scaling
✔ Class Imbalance Handling – SMOTE (Synthetic Oversampling)
✔ Machine Learning Model – Random Forest Classifier
✔ Evaluation Metrics – Precision, Recall, F1-score, Confusion Matrix
✔ Confusion Matrix Heatmap & Precision-Recall Curve

🚀 How to Run the Project?
🔹 1. Install Required Libraries
!pip install imbalanced-learn scikit-learn pandas numpy matplotlib seaborn

🔹 2. Run the Notebook
Open Google Colab or Jupyter Notebook
Upload creditcard.csv
Run Credit_Card_Fraud_Detection.ipynb step by step

📬 Contact & Credits
💡 Created by: Royal Mahesh
📧 Email: royaleducation536@gmal.com
🔗 GitHub: royal012-coder

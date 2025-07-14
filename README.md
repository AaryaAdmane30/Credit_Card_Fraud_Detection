# 💳 Credit Card Fraud Detection

A machine learning model to detect fraudulent credit card transactions using logistic regression. This project tackles the challenge of highly imbalanced data and applies various preprocessing and evaluation techniques to build a reliable binary classification system.

---

##  Features

- Real-world dataset with anonymized credit card transactions
- Handled class imbalance using undersampling
- Trained using Logistic Regression
- Evaluated using Accuracy, Precision, Recall, and F1-Score
- Future-ready for deployment with Streamlit

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn


---

##  Dataset Info

- **Source**: [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Rows**: 284,807
- **Fraudulent Transactions**: ~492 (Class = 1)
- **Legit Transactions**: ~284,315 (Class = 0)
- **Features**: 30 anonymized columns (`V1` to `V28`, `Amount`, `Time`)

---

## 📊 Model Workflow

1. **Data Loading & Exploration**
2. **Data Preprocessing**
   - Check for nulls
   - Distribution analysis
   - Correlation heatmap (optional)
3. **Handling Imbalance**
   - Separated legit and fraud
   - Undersampled legit to match fraud count
4. **Feature Selection & Split**
5. **Model Training**
   - Logistic Regression
6. **Model Evaluation**
   - Confusion Matrix
   - Classification Report
   - Accuracy Score
7. **Optional Deployment**
   - Using Streamlit for real-time predictions

---

 Results

| Metric     | Training Accuracy | Test Accuracy |
|------------|-------------------|----------------|
| Accuracy   | 96%+              | ~97%  |


---

## 🧪 How to Run the Project

pip install pandas numpy scikit-learn matplotlib seaborn streamlit

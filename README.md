# Fraudulent Transaction Detection 🚀

## 📑 Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques.  
We use a real-world, highly imbalanced dataset and apply Random Forest Classifier to predict fraudulent activities accurately.

---

## 📂 Project Structure
- `fraudulent-transaction.ipynb`: Jupyter Notebook containing the full code for data cleaning, EDA, and model building.
- `creditcard.csv`: Dataset used for training and testing (not included here for size/privacy reasons).
- `README.md`: Project documentation file.

---

## 🛠️ Technologies Used
- Python 3.x
- Libraries:
  - numpy
  - pandas
  - scikit-learn
  - matplotlib (optional for visualization)
  - seaborn (optional for visualization)

---

## 📊 Dataset Description
- **Dataset Name**: creditcard.csv
- **Total Rows**: 284,807 transactions
- **Features**:
  - Time, Amount, V1–V28 (anonymized features)
  - Class (0 → Non-Fraud, 1 → Fraud)
- **Challenge**: Extremely imbalanced dataset (fraudulent transactions < 0.2%).

---

## 📈 Project Workflow
1. **Data Collection**: Loaded the dataset using pandas.
2. **Data Cleaning**: Checked and confirmed no missing values.
3. **Exploratory Data Analysis (EDA)**:
   - Analyzed distribution of `Time`, `Amount`, and anonymized features.
   - Separated fraud and non-fraud transactions for comparison.
4. **Model Building**:
   - Applied Random Forest Classifier.
   - Splitted data into training and testing sets.
5. **Model Evaluation**:
   - Accuracy, Precision, Recall, F1-Score
   - Focused mainly on Precision and Recall due to class imbalance.

---

## 📋 Results
- **Model**: Random Forest Classifier
- **Performance**:
  - Achieved good balance between detecting frauds and minimizing false positives.
  - Precision and recall were optimized to handle imbalanced classes.

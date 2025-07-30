# 💳 Credit Card Fraud Detection

This project focuses on detecting fraudulent transactions using machine learning techniques. It leverages a real-world, imbalanced dataset of credit card transactions, exploring preprocessing, exploratory data analysis (EDA), and classification modeling.

## 📁 Dataset

* **Source**: The dataset contains transactions made by European credit card holders in September 2013.
* **Features**:

  * 28 anonymized PCA-transformed numerical features (`V1`–`V28`)
  * `Time` (seconds from first transaction)
  * `Amount` (transaction amount)
  * `Class` (target variable: 1 = Fraud, 0 = Normal)

> Note: The dataset is highly imbalanced with only \~0.17% fraudulent transactions.

## 📊 Exploratory Data Analysis (EDA)

* Data shape and basic statistics
* Distribution of fraud vs. normal transactions
* Visualization of `Amount` and `Time` by class
* Missing value check (none found)
* Class imbalance analysis

## 🧠 Modeling Techniques

* **Preprocessing**:

  * Standardization of `Amount` and `Time`
  * Train-test split
* **Models Used**:

  * Logistic Regression
  * Decision Tree
  * Random Forest
  * XGBoost (if included in later cells)
* **Evaluation Metrics**:

  * Accuracy (not sufficient alone due to imbalance)
  * Precision, Recall, F1-Score
  * Confusion Matrix
  * ROC-AUC Curve

## 📈 Performance Insights

* Special attention was given to **Recall** and **Precision** due to the cost of false negatives in fraud detection.
* The best-performing models are tuned for handling imbalanced data.

## 🛠️ Tools & Libraries

* Python (Pandas, NumPy, Matplotlib, Seaborn)
* Scikit-learn
* Google Colab



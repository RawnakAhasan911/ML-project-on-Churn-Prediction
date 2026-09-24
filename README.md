# 📊 Customer Churn Prediction Using Machine Learning

A machine learning project focused on predicting **customer churn** using customer-related data and supervised learning techniques.

The project explores the complete machine learning workflow, including **data exploration, preprocessing, feature analysis, model development, and evaluation**. The implementation is provided in a Jupyter Notebook.

---

## 📌 Project Overview

Customer churn refers to a customer discontinuing a service or relationship with a company.

Predicting potential churners allows organizations to identify customers who may leave and use the available customer information to understand patterns associated with churn.

This project applies machine learning techniques to build a predictive model for identifying customers who are likely to churn.

### Project Workflow

```text
Dataset
   ↓
Data Exploration
   ↓
Data Preprocessing
   ↓
Exploratory Data Analysis
   ↓
Feature Selection / Engineering
   ↓
Machine Learning Model
   ↓
Model Evaluation
   ↓
Churn Prediction
```

---

## 🎯 Objectives

The main objectives of this project are:

* Understand the structure and characteristics of the customer dataset.
* Perform exploratory data analysis (EDA).
* Identify missing or inconsistent data.
* Preprocess categorical and numerical features.
* Analyze relationships between customer attributes and churn.
* Select relevant features for machine learning.
* Train a classification model.
* Evaluate model performance using appropriate metrics.
* Predict whether a customer is likely to churn.

---

## 🤖 Machine Learning

This project focuses on **supervised machine learning for binary classification**.

The target variable represents whether a customer:

```text
0 → Does not churn
1 → Churns
```

The notebook follows a standard ML pipeline:

### 1. Data Exploration

The dataset is examined to understand:

* Dataset dimensions
* Data types
* Feature distributions
* Missing values
* Categorical variables
* Numerical variables
* Target distribution

### 2. Data Preprocessing

The preprocessing stage prepares the raw dataset for machine learning.

This may include:

* Handling missing values
* Converting categorical variables
* Encoding categorical features
* Preparing numerical features
* Removing unnecessary columns
* Preparing the target variable

### 3. Exploratory Data Analysis

EDA is used to investigate relationships between customer characteristics and churn.

Examples include:

* Churn distribution
* Feature distributions
* Categorical feature analysis
* Numerical feature analysis
* Feature relationships
* Correlation analysis

### 4. Feature Selection

Relevant features are analyzed and selected to provide useful information to the classification model while avoiding unnecessary variables.

### 5. Model Training

The processed dataset is used to train a supervised machine learning classification model.

### 6. Model Evaluation

The trained model is evaluated using classification metrics to understand how well it identifies customers who churn.

Common evaluation metrics include:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

---

## 🛠️ Technologies Used

* **Python**
* **Jupyter Notebook**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Machine Learning**
* **Exploratory Data Analysis**

---

## 📂 Repository Structure

```text
ML-project-on-Churn-Prediction/
│
├── Lab_Code.ipynb
│
└── README.md
```

### `Lab_Code.ipynb`

The main Jupyter Notebook containing the complete implementation of the project, including data analysis, preprocessing, visualization, machine learning, and evaluation.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/RawnakAhasan911/ML-project-on-Churn-Prediction.git
```

### 2. Navigate to the Project

```bash
cd ML-project-on-Churn-Prediction
```

### 3. Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Lab_Code.ipynb
```

and run the notebook cells sequentially.

---

## 📈 Project Highlights

* Performed **Exploratory Data Analysis** on customer data.
* Applied **data preprocessing** techniques for machine learning.
* Handled categorical and numerical features.
* Investigated relationships between customer attributes and churn.
* Applied **feature selection** as part of the ML workflow.
* Built a **classification-based churn prediction system**.
* Evaluated the model using standard machine learning evaluation techniques.

---

## 🧠 Skills Demonstrated

This project demonstrates practical experience in:

```text
Python
│
├── Data Analysis
│   ├── Pandas
│   └── NumPy
│
├── Data Visualization
│   ├── Matplotlib
│   └── Seaborn
│
├── Machine Learning
│   ├── Classification
│   ├── Feature Selection
│   └── Model Evaluation
│
└── Data Preprocessing
    ├── Missing Value Handling
    ├── Encoding
    └── Feature Preparation
```

---

## 🔮 Future Improvements

Possible extensions of the project include:

* Compare multiple classification algorithms.
* Perform hyperparameter tuning.
* Apply cross-validation.
* Handle class imbalance using appropriate techniques.
* Add ROC-AUC and Precision-Recall curves.
* Perform feature importance analysis.
* Add model explainability using SHAP.
* Build an interactive prediction interface using Streamlit.
* Deploy the trained model as an API.

---

## 👨‍💻 Author

**Md. Rawnak Ahasan**

GitHub: [RawnakAhasan911](https://github.com/RawnakAhasan911)

**Mosammat Joynab Binte Mosharraf**

GitHub: [joynab29](https://github.com/joynab29)

---

## 🔗 Repository

[ML-project-on-Churn-Prediction](https://github.com/RawnakAhasan911/ML-project-on-Churn-Prediction)

---

## 📄 License

This project was developed for educational and academic purposes.

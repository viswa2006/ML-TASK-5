# 🤖 ML Task 5 – Customer Churn Prediction

This repository contains **Machine Learning Task 5**, focused on analyzing customer data and developing a machine learning model to **predict customer churn**.

The project uses the **Churn Modelling dataset** and covers data exploration, preprocessing, feature selection, model training, and performance evaluation using Python and popular machine learning libraries.

---

## 📌 Project Overview

Customer churn prediction is a classification problem that aims to identify customers who are likely to leave a company based on their demographic, financial, and account-related information.

### Objectives

* Explore and understand the customer dataset
* Clean and preprocess the data
* Identify relevant features
* Train a machine learning classification model
* Evaluate the model using standard metrics
* Predict whether a customer is likely to churn

---

## 📂 Repository Structure

```text
ML-Task-5/
│
├── Churn_Modelling (MAM) - Churn_Modelling (3).csv
├── ML_Task_5(dc).ipynb
├── ML_Task_5(fs).ipynb
└── README.md
```

### 📄 Files

| File                                              | Description                                           |
| ------------------------------------------------- | ----------------------------------------------------- |
| `Churn_Modelling (MAM) - Churn_Modelling (3).csv` | Customer churn dataset                                |
| `ML_Task_5(dc).ipynb`                             | Main notebook for data analysis and model development |
| `ML_Task_5(fs).ipynb`                             | Notebook for feature selection analysis               |
| `README.md`                                       | Project documentation                                 |

---

## 📊 Dataset

The project uses the **Churn Modelling dataset**, which contains customer demographic and account information along with a target variable that indicates whether a customer has exited the company.

### Important Features

* `CreditScore`
* `Geography`
* `Gender`
* `Age`
* `Tenure`
* `Balance`
* `NumOfProducts`
* `HasCrCard`
* `IsActiveMember`
* `EstimatedSalary`

### 🎯 Target Variable

```text
Exited
```

The `Exited` column represents customer churn:

* `0` → Customer did not churn
* `1` → Customer churned

---

## 🛠️ Technologies Used

* 🐍 Python
* 📓 Jupyter Notebook
* 🧮 NumPy
* 🐼 Pandas
* 📊 Matplotlib
* 📈 Seaborn
* 🤖 Scikit-learn

---

## 🔄 Machine Learning Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Exploration
   ↓
Data Preprocessing
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Churn Prediction
```

---

## 🔍 Data Preprocessing

The following preprocessing steps are performed before training the model:

1. Load the dataset using Pandas
2. Check for missing values
3. Analyze data types and dataset structure
4. Remove unnecessary columns
5. Encode categorical variables
6. Select relevant features
7. Split the data into training and testing sets

---

## 🎯 Feature Selection

Feature selection helps identify the variables that contribute most to predicting customer churn.

The project includes a separate notebook:

```text
ML_Task_5(fs).ipynb
```

This notebook focuses on analyzing and selecting relevant features for the machine learning model.

---

## 🤖 Machine Learning Model

The selected features are used to train a **classification model** for customer churn prediction.

The model learns patterns from existing customer records and uses those patterns to predict whether a customer is likely to leave the company.

### Prediction Process

```text
Customer Information
        ↓
Machine Learning Model
        ↓
Churn Prediction
        ↓
0 → No Churn
1 → Churn
```

---

## 📈 Model Evaluation

The performance of the classification model can be measured using:

* **Accuracy** – Overall percentage of correct predictions
* **Precision** – How many predicted churn cases were actually churn cases
* **Recall** – How many actual churn cases were correctly identified
* **F1-Score** – Balance between precision and recall
* **Confusion Matrix** – Shows correct and incorrect predictions

These metrics provide a better understanding of how well the model identifies potential customer churn.

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/Rabinson-20/ML-Task-5.git
```

### 2. Open the Project Folder

```bash
cd ML-Task-5
```

### 3. Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the Notebook

Run either:

```text
ML_Task_5(dc).ipynb
```

or

```text
ML_Task_5(fs).ipynb
```

---

## 💡 Key Learning Outcomes

Through this project, I gained practical experience in:

* Working with real-world datasets
* Performing exploratory data analysis
* Cleaning and preprocessing data
* Encoding categorical variables
* Selecting relevant machine learning features
* Building classification models
* Evaluating model performance
* Understanding customer churn prediction

---

## 👨‍💻 Author

**Sam Rabinson P**

BCA Student | Aspiring Full Stack Developer | Machine Learning Enthusiast
# ML-TASK-5

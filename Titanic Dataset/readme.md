# Titanic Survival Prediction using Logistic Regression

## 📌 Project Overview

This project predicts whether a passenger survived the Titanic disaster using the **Logistic Regression** machine learning algorithm. The model is trained on the Titanic dataset by analyzing passenger information such as age, gender, passenger class, fare, and family members aboard.

The project demonstrates the complete machine learning workflow, including data understanding, exploratory data analysis (EDA), data preprocessing, model training, and model evaluation.

---

## 📂 Dataset

- **Dataset:** Titanic Dataset
- **Target Variable:** `Survived`
  - `0` → Did Not Survive
  - `1` → Survived

### Features Used

- Pclass
- Sex
- Age
- SibSp
- Parch
- Fare
- Embarked

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Project Workflow

### 1. Data Understanding

- Loaded the dataset
- Checked dataset shape
- Examined data types
- Identified missing values
- Generated descriptive statistics

### 2. Exploratory Data Analysis (EDA)

- Target variable analysis
- Categorical feature analysis
- Numerical feature analysis
- Survival analysis by gender and passenger class
- Correlation analysis

### 3. Data Preprocessing

- Filled missing values in the **Age** column using the median.
- Filled missing values in the **Embarked** column using the mode.
- Dropped unnecessary columns:
  - PassengerId
  - Name
  - Ticket
  - Cabin
- Encoded categorical variables using One-Hot Encoding.

### 4. Feature Selection

Selected the input features (`X`) and target variable (`y`).

### 5. Train-Test Split

- Training Data: 80%
- Testing Data: 20%

### 6. Model Building

Trained a Logistic Regression model using Scikit-learn.

### 7. Model Evaluation

The model was evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- ROC-AUC Score
- ROC Curve

---

## 📈 Machine Learning Algorithm

**Logistic Regression**

Logistic Regression is a supervised machine learning algorithm used for binary classification problems. Since the Titanic dataset has two classes (Survived / Not Survived), Logistic Regression is an appropriate choice.

---

## 📁 Project Structure

```
Titanic-Survival-Prediction/
│
├── Titanic Dataset.csv
├── Titanic_.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository.

```bash
git clone https://github.com/pavithra-576/Titanic-Survival-Prediction.git
```

2. Navigate to the project folder.

```bash
cd Titanic-Survival-Prediction
```

3. Install the required libraries.

```bash
pip install -r requirements.txt
```

4. Open the Jupyter Notebook.

```bash
jupyter notebook
```

5. Run all cells.

---

## 📋 Required Libraries

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
```

---

## 📊 Results

The Logistic Regression model successfully predicts passenger survival based on demographic and travel-related features.

Evaluation metrics include:

- Accuracy Score
- Precision
- Recall
- F1-Score
- ROC-AUC Score

---

## 📚 Learning Outcomes

Through this project, I learned:

- Data Understanding
- Exploratory Data Analysis (EDA)
- Data Cleaning and Preprocessing
- Handling Missing Values
- Feature Engineering
- One-Hot Encoding
- Train-Test Splitting
- Logistic Regression
- Model Evaluation
- Binary Classification

---

## 👨‍💻 Author

**Pavithra S**

B.Tech Artificial Intelligence and Data Science

GitHub: https://github.com/pavithra-576

---

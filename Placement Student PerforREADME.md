# Student Placement Prediction using Random Forest

## 📌 Project Overview

This project aims to predict:

1. **Placement Status** (Placed / Not Placed)
2. **Company Type** (Product-Based / Service-Based)

using Machine Learning. The project utilizes the **Random Forest Classifier** to analyze students' academic performance, technical skills, communication skills, internships, projects, and other placement-related attributes to make accurate predictions.

---

## 🎯 Objectives

- Predict whether a student will be placed.
- Predict whether the student is likely to be placed in a **Product-Based** or **Service-Based** company.
- Identify the most influential factors affecting placements.
- Compare model performance using classification metrics.

---

## 📂 Dataset

The dataset contains student-related information, including:

- Age
- Gender
- College Tier
- Branch
- Degree
- CGPA
- Backlog History
- Attendance Percentage
- DSA Problems Solved
- GitHub Repositories
- Development Projects Count
- AI/ML Projects
- Internships Completed
- Resume Score
- Communication Skills
- Aptitude Score
- Mock Interview Score
- Study Hours
- Self Learning Hours
- Motivation Level
- Adaptability Score
- Hackathons Participated
- Primary Programming Language
- AI Tool Usage Frequency
- Prompt Engineering Skill

### Target Variables

- **Placement Status**
- **Company Type**

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📚 Machine Learning Algorithm

### Random Forest Classifier

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

**Advantages**

- High prediction accuracy
- Handles categorical and numerical data
- Resistant to overfitting
- Provides feature importance
- Works well with complex datasets

---

## 🔄 Project Workflow

### 1. Import Libraries

Import all required Python libraries.

### 2. Load Dataset

Read the dataset using Pandas.

### 3. Data Preprocessing

- Check missing values
- Remove duplicates
- Encode categorical variables using One-Hot Encoding (`pd.get_dummies()`)
- Prepare the dataset for training

### 4. Exploratory Data Analysis (EDA)

- Dataset information
- Statistical summary
- Correlation analysis
- Distribution plots
- Class distribution

### 5. Feature Selection

Separate the input features (X) and target variable (y).

### 6. Train-Test Split

Split the dataset into:

- 80% Training Data
- 20% Testing Data

### 7. Model Training

Train the Random Forest Classifier using the training dataset.

### 8. Prediction

Predict the target values using the testing dataset.

### 9. Model Evaluation

Evaluate the model using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

### 10. Feature Importance

Identify the most important features influencing placement predictions.

---

## 📊 Evaluation Metrics

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## 📈 Expected Outputs

### Model 1

**Placement Status Prediction**

- Placed
- Not Placed

### Model 2

**Company Type Prediction**

- Product-Based Company
- Service-Based Company

---

## 📁 Project Structure

```
Student-Placement-Prediction/
│
├── student_placement.csv
├── Student_Placement_Prediction.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/student-placement-prediction.git
```

2. Navigate to the project folder.

```bash
cd student-placement-prediction
```

3. Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Run the Jupyter Notebook.

```bash
jupyter notebook
```

---

## 📌 Future Improvements

- Hyperparameter tuning using GridSearchCV or RandomizedSearchCV
- Compare Random Forest with XGBoost, CatBoost, and LightGBM
- Build a Streamlit web application for real-time predictions
- Deploy the model using Flask or FastAPI
- Save and load the trained model using Joblib or Pickle

---

## 👨‍💻 Author

**Pavithra S**

B.Tech Artificial Intelligence and Data Science

Machine Learning Project

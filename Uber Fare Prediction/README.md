# 🚖 Uber Fare Prediction using Machine Learning

## 📌 Project Overview

This project predicts the fare amount of an Uber ride using Machine Learning algorithms. The objective is to build a regression model that estimates the fare based on trip details such as pickup and dropoff locations, passenger count, and pickup date and time.

The project includes data cleaning, exploratory data analysis (EDA), feature engineering, model training, and model evaluation.

---

## 📂 Dataset

**Dataset:** Uber Fare Prediction Dataset

### Features

- Pickup Longitude
- Pickup Latitude
- Dropoff Longitude
- Dropoff Latitude
- Passenger Count
- Pickup Date & Time

### Target Variable

- Fare Amount

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 📊 Data Preprocessing

The following preprocessing steps were performed:

- Removed missing values
- Removed duplicate records
- Removed unnecessary columns (`key`, `Unnamed: 0`)
- Converted `pickup_datetime` into datetime format
- Extracted:
  - Year
  - Month
  - Day
  - Hour
  - Weekday
- Removed invalid passenger counts
- Removed negative fare values
- Removed invalid GPS coordinates

---

# 📈 Exploratory Data Analysis (EDA)

EDA techniques used:

- Histogram of Fare Amount
- Box Plot
- Correlation Heatmap
- Scatter Plot
- Descriptive Statistics

---

# 🤖 Machine Learning Models

## 1. Linear Regression

Performance:

- MAE: **5.12**
- RMSE: **8.41**
- R² Score: **0.256**

---

## 2. Random Forest Regressor

Performance:

- MAE: **1.87**
- RMSE: **4.13**
- R² Score: **0.820**

---

# 🏆 Best Model

**Random Forest Regressor**

The Random Forest model significantly outperformed Linear Regression by capturing the complex non-linear relationships between trip features and fare amount.

---

# 📊 Model Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

# 📁 Project Structure

```
Uber-Fare-Prediction/
│
├── Uber.csv
├── Uber.ipynb
├── README.md
└── requirements.txt
```

---

# 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/pavithra-576/DATA-SCIENCE-Training/Uber Fare Prediction.git
```

2. Install the required libraries

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook

```bash
jupyter notebook
```

4. Run all the cells.

---

# 📌 Results

| Model | MAE | RMSE | R² Score |
|------|------:|------:|----------:|
| Linear Regression | 5.12 | 8.41 | 0.256 |
| Random Forest Regressor | **1.87** | **4.13** | **0.820** |

---

# 📚 Key Learnings

- Data preprocessing improves model performance significantly.
- Cleaning invalid records is essential for reliable predictions.
- Feature engineering using date and time improves predictive performance.
- Random Forest is more effective than Linear Regression for this regression task.

---

# 🔮 Future Improvements

- Create a distance feature using pickup and dropoff coordinates.
- Hyperparameter tuning using GridSearchCV or RandomizedSearchCV.
- Try advanced models such as XGBoost, LightGBM, or CatBoost.
- Deploy the model using Streamlit or Flask.
- Save the trained model using Joblib for future predictions.

---

# 👨‍💻 Author

**Pavithra S**

B.Tech Artificial Intelligence and Data Science

Machine Learning | Data Science | Python | SQL

---

## ⭐ If you found this project helpful, consider giving it a star on GitHub!

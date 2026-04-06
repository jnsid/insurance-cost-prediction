# insurance-cost-prediction
Machine Learning project to predict insurance charges

# Insurance Cost Prediction using Machine Learning

## 📌 Problem Statement

This project aims to help insurance companies analyze how factors like age, BMI, smoking habits, and region influence medical costs. Based on historical data, a machine learning model is built to predict insurance charges for new customers, enabling better pricing decisions and risk assessment.

---

## 📊 Dataset

The dataset contains information about individuals including:

* Age
* Gender
* BMI (Body Mass Index)
* Number of children
* Smoking status
* Region
* Medical insurance charges

---

## 🔍 Exploratory Data Analysis (EDA)

Performed detailed analysis to understand data patterns:

* Checked data types, structure, and missing values
* Visualized distributions using histograms
* Used boxplots to detect outliers
* Applied countplots for categorical features
* Generated correlation heatmap
* Added insights and observations for each visualization

### Key Insights:

* Charges are highly right-skewed
* Smokers have significantly higher medical costs
* Age and BMI show moderate impact on charges
* Region has minimal influence

---

## ⚙️ Feature Engineering

* Converted categorical variables using encoding
* Created BMI category features
* Applied **log transformation** to reduce skewness in charges

---

## 🧪 Statistical Analysis

* Used **Pearson Correlation** to analyze relationships between numerical features and target
* Applied **Chi-Square Test** to evaluate dependency between categorical features and charges

---

## 🤖 Model Building

### 1. Linear Regression

* Baseline model
* Achieved strong performance due to linear relationships in data

### 2. Random Forest Regressor

* Used to capture non-linear patterns
* Performance slightly lower without hyperparameter tuning

---

## 📈 Model Evaluation

| Metric   | Linear Regression | Random Forest |
| -------- | ----------------- | ------------- |
| R² Score | 0.82              | 0.81          |

### Observations:

* Linear Regression performed slightly better
* Indicates largely linear relationships after preprocessing
* Log transformation improved model performance

---

## 🧠 Conclusion

* Smoking is the most significant factor affecting insurance charges
* Log transformation helps in handling skewed data
* Linear models can perform well when relationships are mostly linear
* Model can be used to estimate costs for new customers

---

## 🚀 Future Improvements

* Hyperparameter tuning for Random Forest
* Try advanced models like XGBoost
* Deploy as a web application
* Add more real-world features

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

# ✈️ Airline Passenger Satisfaction Prediction

## 📌 Project Overview

This project was developed as the **Final Project** for the **Start2Impact University – Machine Learning** course.

The objective is to predict whether an airline passenger is **satisfied** or **dissatisfied** based on demographic information, travel details, and service quality ratings. The project follows a complete Machine Learning workflow, including data preparation, exploratory analysis, feature engineering, model training, hyperparameter tuning, and model evaluation.

---

## 📂 Dataset

**Dataset:** Airline Passenger Satisfaction

The project uses separate **training** and **test** datasets containing information about airline passengers.

The dataset includes features such as:

- Customer Type
- Gender
- Age
- Type of Travel
- Class
- Flight Distance
- Inflight Wi-Fi Service
- Seat Comfort
- Online Boarding
- Food and Drink
- Check-in Service
- Cleanliness
- Departure/Arrival Delay
- Other service quality indicators

**Target Variable**

- `satisfaction`
  - Satisfied
  - Neutral or Dissatisfied

---

## 📊 Exploratory Data Analysis (EDA)

The exploratory analysis includes:

- Dataset overview
- Missing values analysis
- Statistical summaries
- Target variable distribution
- Numerical feature distributions
- Categorical feature analysis
- Correlation analysis
- Data visualization

The EDA provides insights into passenger characteristics and identifies the most influential variables before model training.

---

## ⚙️ Data Preprocessing

The preprocessing workflow includes:

- Removal of unnecessary columns
- Handling missing values
- Encoding categorical variables
- Feature scaling using **StandardScaler**
- Train/Test Split
- Scikit-learn Pipeline

These steps ensure consistent preprocessing while preventing data leakage.

---

## 🤖 Machine Learning Models

Several supervised Machine Learning algorithms are trained and compared to identify the best-performing classifier.

The project includes:

- Decision Tree
- Random Forest
- Hyperparameter Optimization using **GridSearchCV**

The best model is selected based on its predictive performance.

---

## 📈 Model Evaluation

The models are evaluated using several classification metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC Curve
- AUC Score
- Confusion Matrix
- Feature Importance

These metrics provide a comprehensive evaluation of model performance.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📁 Project Structure

```
├── LeonardoBrembillaProgettoFinale.ipynb
├── README.md
├── requirements.txt
├── test.csv
└── train.csv

```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/airline-passenger-satisfaction.git
```

2. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open the notebook

```bash
jupyter notebook LeonardoBrembillaProgettoFinale.ipynb
```

or run it directly using **Google Colab**.

---

## 🎯 Learning Objectives

This project demonstrates the ability to:

- Perform Exploratory Data Analysis (EDA)
- Clean and preprocess real-world datasets
- Handle missing values and categorical variables
- Build Machine Learning pipelines
- Train and compare multiple classification models
- Optimize hyperparameters using GridSearchCV
- Evaluate models with multiple performance metrics
- Interpret Feature Importance
- Apply Machine Learning best practices

---

## 👨‍💻 Author

**Leonardo Brembilla**

Data Scientist

GitHub: https://github.com/leonardobrembilla

LinkedIn: https://www.linkedin.com/in/leonardobrembilla

---

## 📄 License

This project was created for educational purposes as part of the Start2Impact University Machine Learning course.

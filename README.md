#  Movie Rating Prediction with Python

##  Project Overview

This project aims to predict movie ratings using Machine Learning techniques. The model analyzes various movie attributes such as genre, director, actors, duration, votes, and release year to estimate the IMDb rating of a movie.

The project demonstrates the complete Machine Learning workflow including data preprocessing, exploratory data analysis, feature engineering, model building, and performance evaluation.

---

##  Objective

To develop a machine learning model capable of predicting movie ratings based on historical movie data and various movie-related features.

---

##  Dataset

**Dataset Name:** IMDb India Movies Dataset

**Source:** Kaggle

Dataset Link:
https://www.kaggle.com/datasets/adrianmcmahon/imdb-india-movies

### Features Used

* Genre
* Director
* Actor 1
* Actor 2
* Actor 3
* Duration
* Votes
* Year

### Target Variable

* Rating

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

##  Project Workflow

### 1. Data Collection

* Imported IMDb India Movies dataset from Kaggle.

### 2. Data Preprocessing

* Removed missing values.
* Converted Duration into numeric format.
* Converted Votes into numeric format.
* Extracted Year values and converted them into numeric format.

### 3. Exploratory Data Analysis (EDA)

* Rating Distribution Analysis
* Votes vs Rating Visualization
* Dataset Inspection and Cleaning

### 4. Feature Engineering

* Encoded categorical features using One-Hot Encoding.

### 5. Model Building

* Random Forest Regressor

### 6. Model Evaluation

The model was evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## 📈 Results

### Model Performance

| Metric   | Value |
| -------- | ----- |
| MAE      | 0.81  |
| R² Score | 0.34  |

The model achieved reasonable performance in predicting movie ratings using available movie information.

---

## Future Improvements

* Use XGBoost and CatBoost for improved accuracy.
* Include additional features such as budget, revenue, and language.
* Perform hyperparameter tuning.
* Deploy the model as a web application.

---

##  Sample Output

Predicted movie ratings are generated using the trained Random Forest Regression model.

Example:

Movie Features:

* Genre: Drama
* Director: Example Director
* Duration: 120 minutes
* Year: 2020

Predicted Rating:
7.5 / 10

---

## Learning Outcomes

Through this project, I learned:

* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Machine Learning Regression Techniques
* Model Evaluation and Performance Analysis
* End-to-End Machine Learning Workflow

---

##  Internship Project

This project was completed as part of the **CodSoft Data Science Internship Program**.

---

##  Author

**Pallavi Nagre**

Data Science Intern – CodSoft

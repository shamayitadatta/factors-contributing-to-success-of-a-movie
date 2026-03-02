# 🎬 Movie Success Analysis

### A Data-Driven Approach to Identifying Factors Behind Box Office Performance

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![ML](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![EDA](https://img.shields.io/badge/Data%20Analysis-Pandas%20%7C%20Seaborn-green)
![Status](https://img.shields.io/badge/Project-Active-brightgreen)

---

## 📌 Table of Contents

* [📖 Introduction](#-introduction)
* [🎯 Problem Statement](#-problem-statement)
* [📊 Dataset](#-dataset)
* [⚙️ Methodology](#-methodology)
* [📈 Exploratory Data Analysis](#-exploratory-data-analysis)
* [🤖 Model Development](#-model-development)
* [📊 Results](#-results)
* [🗂️ Project Structure](#️-project-structure)
* [🚀 Installation & Usage](#-installation--usage)
* [📌 Future Work](#-future-work)
* [🤝 Contributing](#-contributing)
* [📜 License](#-license)

---

## 📖 Introduction

The movie industry generates billions in global revenue annually, yet predicting a movie’s success remains complex. This project applies **data analytics and machine learning techniques** to identify the key factors that contribute to a movie’s commercial success.

The objective is to transform raw movie data into actionable insights and predictive intelligence.

---

## 🎯 Problem Statement

What factors significantly influence the success of a movie?

We aim to analyze:

* 💰 Budget vs Revenue relationship
* ⭐ Ratings impact
* 🎭 Genre performance
* 🎬 Director & Cast influence
* 📅 Release timing effect
* 🌍 Language & market reach

---

## 📊 Dataset

The dataset includes structured movie-level data such as:

| Feature          | Description           |
| ---------------- | --------------------- |
| Title            | Movie Name            |
| Budget           | Production Budget     |
| Revenue          | Box Office Collection |
| Genre            | Primary Category      |
| IMDb Rating      | User Rating           |
| Director         | Movie Director        |
| Cast             | Lead Actors           |
| Release Date     | Launch Date           |
| Popularity Score | Engagement Metric     |

> Dataset Source: Kaggle / IMDb / TMDB (update accordingly)

---

## ⚙️ Methodology

### 1️⃣ Data Preprocessing

* Missing value treatment
* Duplicate removal
* Outlier detection
* Feature encoding (One-hot encoding)
* Feature scaling

### 2️⃣ Feature Engineering

* ROI (Return on Investment) calculation
* Success label creation (Hit/Flop classification)
* Aggregated genre statistics

### 3️⃣ Exploratory Data Analysis

* Correlation heatmaps
* Distribution analysis
* Budget vs Revenue scatter plots
* Genre revenue comparison

### 4️⃣ Model Development

We experimented with:

* Linear Regression
* Random Forest Regressor
* Logistic Regression (Hit/Flop Classification)
* Gradient Boosting

---

## 📈 Exploratory Data Analysis

Key EDA findings include:

* Strong positive correlation between **budget and revenue**
* Certain genres consistently outperform others
* Movies released during holiday seasons show higher revenue spikes
* Higher IMDb ratings moderately correlate with box office performance

---

## 🤖 Model Development

### Regression Metrics

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)

### Classification Metrics

* Accuracy
* Precision
* Recall
* F1 Score

---

## 📊 Results

| Model               | Performance                  |
| ------------------- | ---------------------------- |
| Linear Regression   | Moderate fit                 |
| Random Forest       | High predictive power        |
| Logistic Regression | Good classification accuracy |

> Random Forest showed the best performance in predicting revenue.

---

## 🗂️ Project Structure

```
Movie-Success-Analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── eda_analysis.ipynb
│
├── src/
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── train_model.py
│   └── evaluate.py
│
├── models/
│   └── saved_model.pkl
│
├── reports/
│   └── visualizations/
│
├── requirements.txt
└── README.md
```

---

## 🚀 Installation & Usage

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/movie-success-analysis.git
cd movie-success-analysis
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run Notebook

```bash
jupyter notebook
```

---

## 📌 Future Work

* Integrate TMDB API for real-time movie data
* Apply Sentiment Analysis on reviews
* Deploy model using Streamlit
* Add Deep Learning models
* Time-series revenue forecasting

---

## 📊 Business Impact

* Helps production houses optimize budgets
* Assists investors in risk assessment
* Enables data-driven movie marketing strategies
* Supports OTT platforms in content acquisition decisions

---

## 🤝 Contributing

Contributions are welcome.
Fork the repository, create a feature branch, and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.

---

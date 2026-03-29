# 🌧️ Rain Tomorrow Prediction — Logistic Regression

A machine learning project that predicts whether it will rain tomorrow in Albury, Australia, using Logistic Regression and other classification algorithms.

---

## 📌 Project Overview

This project applies **Logistic Regression** to a binary classification problem — predicting rain based on daily weather observations. The notebook covers full data preprocessing, exploratory data analysis, model training, evaluation, and comparison with other algorithms.

---

## 📂 Dataset

- **Source:** Weather observations from Albury, Australia
- **Size:** 3,011 records, 13 features
- **Target Variable:** `RainTomorrow` (0 = No Rain, 1 = Rain)
- **Download:** [weatherAlbury.csv](https://github.com/FahadAlghofaili/DSAI_unit4_Classification_Mini_Project/blob/main/weatherAlbury.csv)

| Feature | Description |
|---|---|
| MinTemp / MaxTemp | Min & Max temperature (°C) |
| Rainfall | Amount of rainfall (mm) |
| Humidity9am / Humidity3pm | Humidity at 9am and 3pm (%) |
| Pressure9am / Pressure3pm | Atmospheric pressure (hPa) |
| Temp9am / Temp3pm | Temperature at 9am and 3pm (°C) |
| RainToday | Did it rain today? (0/1) |

---

## 🔍 Key Findings

- **Humidity3pm** was the strongest predictor of rain with a correlation of **0.468**
- **Pressure3pm** had the strongest negative correlation at **-0.304**
- The dataset has a class imbalance: **79.5% No Rain** vs **20.5% Rain**

---

## 📊 Model Results

| Model | Accuracy | F1 Score |
|---|---|---|
| Logistic Regression (default) | 87.6% | 0.7712 |
| Logistic Regression (newton-cg) | 87.77% | 0.7914 |
| SVC | 79.90% | 0.4441 |
| KNN | 86.6% | 0.7578 |
| Random Forest | **87.6%** | **0.7862** |

---

## 📁 Project Structure

```
DSAI_unit4_Classification_Mini_Project/
│
├── Logistic_Regression_Rain_Tomorrow_Prediction.ipynb  # Main notebook
├── weatherAlbury.csv                                   # Dataset
└── README.md
```

---

## ⚙️ Requirements

```
pandas
numpy
seaborn
matplotlib
scikit-learn
```

Install all dependencies with:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn
```

---

## 🚀 How to Run

1. Clone the repository
```bash
git clone https://github.com/FahadAlghofaili/DSAI_unit4_Classification_Mini_Project.git
```

2. Open the notebook
```bash
jupyter notebook Logistic_Regression_Rain_Tomorrow_Prediction.ipynb
```

3. Run all cells

---

## 👤 Author
Fahad Alghofaili
Mohamed Alsomali
Mansour Alhenaki 

**Fahad Alghofaili** — DSAI Unit 4 Classification Mini Project

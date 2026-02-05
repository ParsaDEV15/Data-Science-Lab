# 🧠 Data-Science-Lab

This repository is a **professional portfolio** containing selected **Machine Learning, Deep Learning, and Data Analysis projects**.  
Each project demonstrates applied problem-solving, model development, and evaluation on real-world datasets.

---

## 📂 Projects Overview

### 🔹 NewsShield: Fake News Detection with Deep Learning
**Category:** Deep Learning (NLP)

A deep learning–based system for detecting fake news articles from textual data.

**Key Highlights:**
- Text preprocessing using nltk and regex  
- Deep neural network with **pytorch** for classification  
- Model evaluation using **F1-Macro** 

**Final Result:**
- **F1-Macro:** 97%

📓 **Notebook**
```
NewsShield\fake_news_detector_dl.ipynb
```

---

### 🔹 ChurnSense: Customer Churn Prediction with Machine Learning
**Category:** Machine Learning (Classification)

A machine learning model designed to predict customer churn based on behavioral and demographic data.

**Key Highlights:**
- Data preprocessing and feature engineering  
- Using **SVM** machine learning model for churn prediction  
- Model evaluation using **F1-Macro** and **ROC-AUC**

**Final Result:**
- **F1-Macro:** 71%
- **ROC-AUC:** 75%


📓 **Notebook**
```
ChurnSense\churnsense_customer_churn_ml.ipynb
```

---

### 🚨 FraudGuard: Transaction Fraud Detection
**Category:** Data Science / Machine Learning

A machine learning model focused on detecting fraudulent transactions using data analysis and predictive techniques.

**Key Highlights:**
- Data preprocessing and exploratory analysis
- Handling class imbalance in fraud datasets
- Using **Logistic Regression** for fraud detection
- **Decision threshold tuning** to control the trade-off between precision and recall
- Model evaluation using **F1-Score**

**Final Result:**
- Fraud-class F1 Score: 76%

📓 **Notebook**
```
FraudGuard\credit_card_fraud_detection_ml.ipynb
```

---

### ⚡ PowerNova: Wind & Solar Energy Production Analysis
**Category:** Data Science / Deep Learning / Energy Analytics

A data science and deep learning project focused on analyzing and modeling **wind and solar energy production** over time using real-world energy data.

**Research Questions:**
1. Which energy source (wind or solar) produced more total energy over the observed period?
2. During which season was the highest amount of energy produced overall?
3. Which month recorded the highest energy production, and does this differ between wind and solar?
4. Are there any anomalies or unusual spikes/drops in energy production?

**Key Highlights:**
- Seasonal and monthly trend analysis for wind and solar energy
- Detection of anomalies and unusual production patterns
- Training a **Deep Learning model using Keras** for energy production prediction
- Model evaluation using regression-based performance metrics

**Final Result:**
- Mean Absolute Error: ~2790.64

📓 **Notebook**
```
PowerNova\wind_solar_energy_analysis.ipynb
```

---

### 💼 HiringMarket: Data Scientist Job Market Analysis (2025)
**Category:** Data Science / Analytics / Labor Market

A data science project focused on analyzing the **2025 data science job market** using salary, company, and job-posting data to understand hiring trends and compensation patterns across global markets.

**Research Questions:**
1. How do salaries vary across different **seniority levels**?
2. Is there a relationship between **company size or revenue** and salary offerings?
3. What are the **top skills** requested across all job postings?
4. How does **location** correlate with salary ranges?
5. Which **industries** are hiring the most data scientists?
6. Does **company ownership type** affect hiring patterns?

**Key Highlights:**
- Data cleaning and preprocessing of job and salary data
- Salary analysis by seniority, company size, and location
- Skill frequency analysis across job postings
- Industry and ownership-type hiring trend analysis
- Visual exploration of salary and hiring distributions

📓 **Notebook**
```
HiringMarket\2025_ds_job_posts_analysis.ipynb
```

---

### 🩺 HealthHorizons: Global Life Expectancy Analysis & Prediction
**Category:** Data Science / Machine Learning (Regression)

A data science project focused on analyzing the key **health, demographic, and lifestyle factors** that influence life expectancy across countries, combined with a predictive regression model.

**Research Questions:**
1. What is the impact of **immunization coverage** on life expectancy?
2. How do **infant and adult mortality rates** affect life expectancy?
3. Does life expectancy correlate positively or negatively with **lifestyle factors** such as diet, exercise, smoking, and alcohol consumption?
4. Do **densely populated countries** tend to have lower life expectancy?
5. Which selected predictors have the **strongest influence** on life expectancy?

**Key Highlights:**
- Data preprocessing and feature selection
- Training a **Random Forest Regression** model for life expectancy prediction
- Model evaluation using **RMSE** and **R² Score**
- Model interpretability using **SHAP values** to identify influential predictors

**Final Result:**
- **RMSE:** 1.66  
- **R² Score:** 0.97

---

## 🛠 Technologies Used

- Python  
- NumPy, Pandas  
- Scikit-learn  
- TensorFlow / Keras  
- PyTorch  
- Shap
- Matplotlib, Seaborn, plotly  
- Jupyter Notebook

---


⭐ If you find this repository useful, feel free to give it a star.

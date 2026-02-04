# 🔥 Employee Burnout Rate Prediction

> Using Machine Learning to identify and predict employee burnout factors within organizations

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
![Status](https://img.shields.io/badge/status-Active-success)

---

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Key Results](#key-results)
- [Technical Stack](#technical-stack)
- [Project Structure](#project-structure)
- [Installation & Usage](#installation--usage)
- [Key Insights](#key-insights)
- [Skills Demonstrated](#skills-demonstrated)

---

## 📊 Project Overview

This project applies machine learning techniques to predict employee burnout by analyzing organizational and personal factors. The goal is to identify early warning signs of burnout and help HR teams implement preventative measures.

**Key Objective:** Build a predictive model to classify employees at risk of burnout based on their work patterns and engagement metrics.

---

## 🎯 Problem Statement

Employee burnout is a significant challenge impacting productivity, retention, and organizational health. This project addresses:
- Early identification of at-risk employees
- Understanding key factors contributing to burnout
- Enabling data-driven HR interventions

---

## 📈 Dataset

- **Records:** 22,750
- **Features:** 8 (after preprocessing)
- **Target Variable:** Burn Rate (continuous, range: 0.0 - 1.0)
- **Data Quality:** Handled missing values using mean imputation; Encoded categorical variables (Gender, Company Type, WFH Setup); Converted dates to days working

**Key Features Include:**
- Employee ID & Date of Joining
- Gender & Company Type (Service/Product)
- WFH Setup Availability
- Designation (0.0-5.0)
- Resource Allocation (1.0-10.0)
- Mental Fatigue Score (0.0-10.0)
- Days Working (derived feature)

---

## 🔧 Methodology

1. **Data Exploration & Cleaning**
   - Handled missing values & outliers
   - Performed EDA with visualizations

2. **Feature Engineering**
   - Created relevant features
   - Performed feature scaling & encoding

3. **Model Development**
   - Trained multiple algorithms
   - Hyperparameter tuning & cross-validation

4. **Evaluation**
   - Model comparison & performance metrics
   - Feature importance analysis

---

## 🎁 Key Results

| Model | MSE | R² Score |
|-------|----------|----------|
| Random Forest Regressor | 0.0057 | 0.8401 |

**Top Predictive Factors:**
-  **Mental Fatigue Score** - Strong indicator of burnout risk
-  **Resource Allocation** - Inadequate resources increase burnout
-  **Designation Level** - Role hierarchy affects burnout likelihood

---

## Visualizations & EDA

### Key Findings

![Burn Rate Distribution by Designation](/Employee-Burnout-Rate/burnratebydesignation.png)
![Mental Fatigue Score Impact](/Employee-Burnout-Rate/mentalfatiguescorebyburnrate.png)
![Corelation Heatmap](/mployee-Burnout-Rates/heatmap.png)
![Pairplot Analysis](/Employee-Burnout-Rate/pairplot.png)
![Gender-based Fatigue Comparison](/Employee-Burnout-Rate/gender.png)
![Model Performance](/Employee-Burnout-Rate/score.png)


---

## Technical Stack

- **Language:** Python 3.8+
- **Data Analysis:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Notebook:** Jupyter/IPython
- **Version Control:** Git

---

## 📁 Project Structure

```
Employee-Burnout-Rate/
├── README.md                          # Project documentation
├── Side Project Burnout Rate.ipynb   # Main analysis & modeling
├── train.csv                          # Training dataset
```

---

## 🚀 Installation & Usage

### Prerequisites
- Python 3.8 or higher
- pip or conda

### Setup

```bash
# Clone the repository
git clone https://github.com/[your-username]/Employee-Burnout-Rate.git
cd Employee-Burnout-Rate

# Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn jupyter

# Launch Jupyter Notebook
jupyter notebook "Side Project Burnout Rate.ipynb"
```

---

## 💡 Key Insights

1. **Mental Fatigue Impact:** Higher mental fatigue scores directly correlate with significantly increased burnout rates, suggesting mental health support is critical.
2. **Resource Scarcity Effect:** Employees lacking adequate resources show marked increases in predicted burnout, indicating need for workload balancing.
3. **Preventative Intervention:** Early identification of high-risk employees enables HR teams to implement targeted wellness programs before burnout occurs.

## 💼 Real-Life Use Cases

1. **Personalized Resource Allocation:** Ensuring that employees receive adequate resources based on their workload and project demands.
2. **Mental Health Support:** Providing mental health resources, especially for employees with high mental fatigue indicators.
3. **Flexible Scheduling:** Adjusting schedules or work-from-home options to help mitigate burnout risk.

These applications demonstrate the potential for data-driven models to positively impact workplace dynamics, fostering a healthier work environment.


---

## 🎓 Skills Demonstrated

✅ **Data Science & Analytics**
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Data Cleaning & Preprocessing

✅ **Machine Learning**
- Supervised Learning (Classification)
- Model Evaluation & Selection
- Hyperparameter Tuning
- Feature Importance Analysis

✅ **Tools & Technologies**
- Python Programming
- Data Visualization
- Jupyter Notebooks
- Version Control (Git)

---

## 📧 Contact & Connect

- **LinkedIn:** linkedin.com/in/mohammedsaifshaikh
- **GitHub:** github.com/1MohammedSaif
- **Email:** ms.sk.3609@gmail.com

---

**⭐ If you found this project helpful, please consider starring it on GitHub!**

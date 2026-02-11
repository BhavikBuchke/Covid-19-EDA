# 🧪 COVID-19 Clinical Trials Data Analysis

*A Data Cleaning & Exploratory Data Analysis Project*

## 📌 Project Overview

This project analyzes a global COVID-19 clinical trials dataset to uncover patterns in research activity, enrollment distribution, trial phases, intervention types, and geographic participation.

The primary goal was to demonstrate strong data cleaning, feature engineering, and exploratory data analysis (EDA) skills using real-world, messy healthcare data.

This project reflects the kind of structured analytical workflow expected in entry-level Data Science and Data Analyst roles.

---

## 🎯 Key Objectives

* Clean and preprocess real-world clinical data
* Handle missing values and inconsistencies
* Perform feature engineering for deeper insights
* Conduct exploratory data analysis (EDA)
* Extract meaningful insights from structured healthcare data

---

## 🛠 Tech Stack

* **Python**
* **Pandas** – Data manipulation & cleaning
* **NumPy** – Numerical operations
* **Matplotlib & Seaborn** – Data visualization
* **KaggleHub** – Dataset retrieval

---

## 🔄 Project Workflow

### 1️⃣ Data Acquisition

Dataset downloaded from Kaggle using KaggleHub.

### 2️⃣ Data Cleaning

* Removed irrelevant columns
* Handled missing values (median imputation & categorical filling)
* Dropped highly sparse columns
* Converted date columns to datetime format
* Removed invalid duration values

### 3️⃣ Feature Engineering

* Extracted country information from text fields
* Calculated trial duration (Completion Date – Start Date)
* Simplified complex phase labels into categories
* Extracted intervention types

### 4️⃣ Exploratory Data Analysis

Key analyses performed:

* Enrollment distribution (log-scale visualization)
* Monthly clinical trial trends
* Top 10 countries conducting trials
* Trial status distribution
* Duration analysis
* Intervention type distribution
* Phase category distribution

---

## 📊 Key Insights

* Clinical trial enrollments are highly skewed — most trials are small-scale.
* Research activity surged during early pandemic waves.
* A small number of countries dominate global trial participation.
* Phase 2 and Phase 3 trials are most common, reflecting large-scale treatment validation efforts.
* Drug-based interventions dominate over other modalities.

---

## 💡 Skills Demonstrated

This project highlights:

✔ Data cleaning & preprocessing
✔ Missing value treatment strategies
✔ Feature engineering from raw text fields
✔ Time-series aggregation
✔ Data visualization & interpretation
✔ Analytical storytelling
✔ Structured project documentation

---

## 📁 Repository Structure

```
├── covid_trials_analysis.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
```

Then open the notebook:

```bash
jupyter notebook covid_trials_analysis.ipynb
```

---

## 📌 Why This Project Matters

Healthcare datasets are often messy, incomplete, and text-heavy.
This project demonstrates the ability to:

* Work with real-world structured datasets
* Transform raw data into business insights
* Apply systematic EDA workflow
* Communicate findings clearly

These are foundational skills required in entry-level Data Science and Data Analyst roles.

---

## 👤 About Me

I am an MCA student with a strong interest in Data Science, Analytics, and Machine Learning. I enjoy working with real-world datasets and converting raw data into actionable insights.

I am actively seeking entry-level Data Science / Data Analyst opportunities.

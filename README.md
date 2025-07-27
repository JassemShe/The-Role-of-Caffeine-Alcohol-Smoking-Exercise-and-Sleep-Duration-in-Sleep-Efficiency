# The-Role-of-Caffeine-Alcohol-Smoking-Exercise-and-Sleep-Duration-in-Sleep-Efficiency
# 💤 Sleep Efficiency Analysis

This project investigates behavioral and physiological factors that influence **sleep efficiency**. Using real-world data, it examines how variables such as caffeine and alcohol consumption, smoking, exercise, and sleep duration affect sleep quality, with a focused analysis on adults aged 20–59.

---

## 🧠 Project Highlights

- 🧪 **Statistical Testing**: Linear regression, correlation analysis, t-tests, and hypothesis testing.
- 📊 **Exploratory Data Analysis**: Insightful visualizations and pattern recognition using Matplotlib/Seaborn.
- 🧹 **Data Cleaning**: Informed imputation strategies, feature engineering, type validation, and consistency checks.
- 🎯 **Critical Thinking**: Judicious decisions on data inclusion/exclusion and nuanced interpretation of counterintuitive findings.
- 💡 **Real-World Insight**: Balanced interpretation of results with domain understanding and limitations.

---

## 🛠️ Methodology Overview

### 1. 🧼 Data Cleaning & Preparation
- **Missing Values**:
  - `Awakenings`: Removed missing records due to observed bias in sleep efficiency.
  - `Caffeine`, `Alcohol`, `Exercise`: Imputed missing values after comparing relevant distributions (e.g., REM sleep %, awakening patterns).
- **Data Type Fixes**:
  - Converted `bedtime` and `wakeup_time` from string to datetime.
- **Validation**:
  - Checked sleep stage sums ≈ 100%.
  - Removed unreliable columns (e.g., Deep/Light sleep %) based on domain standards.

### 2. 🔧 Feature Engineering
- Added:
  - `age_group`, `efficiency_level`, `rem_sleep_assessment`, `caffeine_level`, `alcohol_level`, etc.
- Standardized naming (snake_case) and optimized memory using categorical types.

### 3. 📊 Exploratory Data Analysis (EDA)
- Focused on **Adults (20–59)** due to their 89% representation in the dataset.
- Analyzed correlations, distributions, and behaviors across sleep metrics.
- Conducted comparative weekday/weekend and monthly analyses.

### 4. 📈 Statistical Modeling
- Built an OLS linear regression model to predict sleep efficiency using:
  - `caffeine`, `alcohol`, `smoking_status`, `exercise_score`, and `sleep_duration`.
- Conducted t-tests (e.g., smoking vs. non-smoking) and Pearson correlation checks.

---

## 🔍 Key Findings

| Factor              | Effect on Sleep Efficiency           | Notes                                                                 |
|---------------------|--------------------------------------|-----------------------------------------------------------------------|
| **Awakenings**      | Strong negative (-0.57)              | More awakenings = poorer sleep efficiency                             |
| **Alcohol**         | Strong negative (-0.43)              | Higher consumption correlates with worse sleep efficiency             |
| **Smoking**         | Significant negative impact          | Confirmed by t-test (p < 0.001)                                       |
| **Exercise**        | Moderate positive                    | More frequent exercise linked to better sleep efficiency              |
| **Caffeine**        | Weak positive                        | Moderate intake had highest average sleep efficiency (unexpected)     |
| **Sleep Duration**  | No clear correlation (~0.002)        | Likely due to limited variability (mostly 7–9 hours)                  |
| **Weekday vs Weekend** | No significant differences         | Sleep patterns remained consistent across days                        |

---

## ⚠️ Limitations & Future Work

This analysis offers strong insights, but several constraints should be noted:

- 📍 **Population Bias**: The dataset only includes adults aged 20–59 from Morocco.
- 🧪 **Measurement Uncertainty**: The methodology for calculating sleep efficiency is not documented.
- 📉 **Limited Factor Variability**: Distributions (e.g., sleep duration, caffeine) lacked diversity.
- ❓ **Unexpected Results**: Known relationships (e.g., caffeine → poor sleep) were not reflected, warranting further investigation.
- 🧪 **Future Studies Needed**: A broader dataset, spanning multiple age groups, geographies, and with validated measurement tools, would offer deeper insights.

---







# 💤 Behavioral Factors Affecting Sleep Efficiency

This project investigates how behavioral factors—caffeine, alcohol, smoking, exercise, and sleep duration—impact sleep efficiency using a dataset collected from adult participants in Morocco. Through statistical modeling and critical interpretation, the analysis identifies key lifestyle influences on sleep quality.

---

## 📊 Key Findings

The regression model explains nearly **29.6%** of the variance in sleep efficiency (Adjusted R² = 0.287), using the five behavioral predictors.

### ☕ Caffeine Intake
Caffeine shows a **small but statistically significant positive effect** on sleep efficiency (β = +0.0235, p = 0.045).  
This result may reflect confounding lifestyle factors, suggesting the importance of cautious interpretation.

### 🍷 Alcohol Use
Alcohol consumption is **strongly associated with reduced sleep efficiency** (β = −0.1002, p < 0.001), confirming its negative impact on sleep quality.

### 🚬 Smoking Status
Smoking significantly **lowers sleep efficiency** (β = −0.0896, p < 0.001).  
This is reinforced by an independent **t-test** showing a significant difference between smokers and non-smokers (t = -7.222, p < 0.001).

### 🏃 Exercise Frequency
Exercise frequency is a **positive predictor** of sleep efficiency (β = +0.0348, p = 0.001), supporting the benefit of physical activity on sleep.

### 🛌 Sleep Duration
Surprisingly, sleep duration is **not a significant predictor** (β = +0.0041, p = 0.547) and shows negligible correlation with efficiency (r = 0.002, p = 0.970).

---

## 💡 Analytical Thinking & Critical Reasoning

### 🔎 Used Multivariate Modeling Over Simple Correlation
Instead of analyzing variables in isolation, I applied a **multiple regression model** to understand how behaviors interact and jointly affect sleep.  
→ *Demonstrates statistical depth and modeling intuition.*

### 🧠 Interpreted Unexpected Results with Caution
Caffeine showed a surprising positive impact. I **didn’t accept it blindly** but discussed how it might reflect healthier routines or unobserved variables.  
→ *Exhibits critical thinking and domain reasoning.*

### ✅ Verified Findings with T-Test
To **cross-validate** the impact of smoking, I performed a t-test alongside the regression. Both methods confirmed the result.  
→ *Shows rigor and analytical reliability.*

### ⚠️ Transparent About Limitations
I addressed limitations such as **age range**, **geographic scope**, and **measurement ambiguity**.  
→ *Reflects scientific integrity and awareness of generalizability.*

### 🔄 Acknowledged Deviations from Known Research
The lack of a relationship between sleep duration and efficiency **contradicts expectations**. I flagged this for future investigation instead of dismissing it.  
→ *Indicates humility, openness, and evidence-based reasoning.*

---

## ✅ Recommendations

- **Individuals:** Limit alcohol use, avoid smoking, and engage in regular physical activity to support sleep efficiency.
- **Healthcare Providers:** Incorporate behavioral assessments in sleep evaluations and advise on lifestyle changes.
- **Public Health Officials:** Design policies and interventions promoting smoking cessation, reduced alcohol use, and exercise habits to improve community sleep health.

---

## 🔮 Limitations & Future Work

- Data is limited to Moroccan adults aged 20–59.
- The measurement methodology of sleep efficiency was not described.
- Cultural and lifestyle specificity may limit broader application.
- Some results (e.g., caffeine and sleep duration) may be affected by data constraints or skewed variable distributions.

**Future research** should:
- Use larger and more diverse datasets across multiple countries
- Include detailed documentation of measurement tools
- Explore interaction effects and temporal patterns



# 💤 Behavioral Factors Affecting Sleep Efficiency

This project investigates how behavioral factors—caffeine, alcohol, smoking, exercise, and sleep duration—impact sleep efficiency using a dataset collected from adult participants in Morocco. Through statistical modeling and critical interpretation, the analysis identifies key lifestyle influences on sleep quality.

---

## 📊 Key Findings

The regression model explains nearly **29.6%** of the variance in sleep efficiency (Adjusted R² = 0.287), using the five behavioral predictors.

### ☕ Caffeine Intake
Caffeine shows a **small but statistically significant positive effect** on sleep efficiency (β = +0.0235, p = 0.045).  

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

### 🔎 Applied Multivariate Modeling for Deeper Insights  
Rather than relying on isolated variable analysis, a **multiple linear regression model** was implemented to examine the **combined influence** of behavioral factors on sleep efficiency. This allowed for a more comprehensive understanding of how predictors interact.

### 🧠 Interpreted Unexpected Findings with Nuance  
Caffeine intake exhibited a **positive association** with sleep efficiency, contrary to prior literature. Rather than assuming causality, this result was **interpreted with caution**

### ✅ Employed Cross-Validation to Reinforce Results  
To **support the regression finding** that smoking negatively impacts sleep efficiency, a **two-sample t-test** was conducted. Both analyses independently yielded significant results, reinforcing the conclusion and enhancing robustness.

### ⚠️ Explicitly Acknowledged Dataset Limitations  
Key limitations—such as the **restricted age range** (20–59), **geographic specificity** (Moroccan population), and the **lack of transparency regarding measurement tools**—were explicitly identified. These factors were recognized as potentially affecting the **generalizability and reliability** of findings.

### 🔄 Flagged Deviations from Established Literature  
The **absence of a significant relationship** between sleep duration and efficiency was noted, despite prior evidence suggesting otherwise. This deviation was **flagged for future research**, highlighting the need for further validation with broader and more diverse datasets.


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



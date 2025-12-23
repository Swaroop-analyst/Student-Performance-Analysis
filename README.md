# 🎓 Student Performance Analysis — CRISP-DM (EDA Portfolio Project)

## 📌 Project Overview
This project follows the **CRISP-DM (Cross-Industry Standard Process for Data Mining)** framework to conduct a **pure exploratory data analysis (EDA)** on student academic performance data.  
The goal is to understand **factors influencing exam performance** and derive **actionable insights** for educators, institutions, and policymakers.

> ⚠️ **Note**: This project is intentionally limited to **EDA only**.  
> No machine learning or predictive modeling is performed.

---

## 1️⃣ Business Understanding

### Business Problem
Educational institutions often struggle to identify the underlying factors affecting student performance.  
Understanding how demographics, parental background, and preparation activities influence exam scores can support better academic interventions.

### Business Objectives
- Analyze patterns in student exam scores
- Understand the impact of gender, parental education, and test preparation
- Provide insights to improve academic support strategies

### Business Success Criteria
- Clear identification of performance drivers
- Insights that are interpretable and actionable
- Honest, reproducible analysis

---

## 2️⃣ Data Understanding

### Dataset Description
The dataset contains student-level information including:
- Gender
- Race / ethnicity
- Parental level of education
- Lunch type (proxy for socio-economic status)
- Test preparation course completion
- Scores in math, reading, and writing

### Initial Data Exploration
- Dataset structure and dimensions
- Data type validation
- Missing value checks
- Summary statistics for numerical features

### Key Observations
- Score distributions vary significantly across subjects
- Reading and writing scores show strong correlation
- Math scores exhibit higher variance compared to language subjects

---

## 3️⃣ Data Preparation

### Preparation Steps
- Column validation and renaming (where required)
- Encoding categorical variables for analytical grouping
- Creation of aggregate metrics (e.g., average score)
- Outlier inspection

### Outcome
A clean, analysis-ready dataset suitable for:
- Academic performance analysis
- Policy and curriculum evaluation
- Future predictive modeling (optional extension)

---

## 4️⃣ Modeling (Not Implemented)

> 🚫 **No Modeling Performed**
This project deliberately excludes machine learning and statistical modeling.

---

## 5️⃣ Evaluation & Insights

### Gender-Based Performance
- Female students tend to outperform in reading and writing
- Male students show slightly higher dispersion in math scores

### Test Preparation Impact
- Students who completed test preparation courses consistently score higher across all subjects
- The gap is most pronounced in math performance

### Parental Education Influence
- Higher parental education levels are associated with improved student performance
- Stronger effect observed in language subjects

### Socio-Economic Indicator (Lunch Type)
- Students with standard lunch plans perform better on average
- Indicates potential socio-economic influence on academic outcomes

---

## 6️⃣ Deployment & Business Recommendations

### Practical Applications
- Targeted academic support for students without test preparation
- Early identification of at-risk students based on background indicators
- Data-driven curriculum planning

### Institutional Impact
- Improved student outcomes
- More effective resource allocation
- Evidence-based educational policies

---

## 🧰 Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📁 Repository Structure
```
Student-Performance-Analysis/
├── notebooks/
│   └── Student performance in exams.ipynb
├── README.md
└── requirements.txt
```

---

## 🎯 Why This Project Is Valuable
✔ Strict CRISP-DM alignment  
✔ EDA-focused and honest representation  
✔ Strong business and policy relevance  
✔ Ideal for analytics and business analyst roles  

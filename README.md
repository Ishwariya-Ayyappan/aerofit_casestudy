# 🏃‍♂️ Aerofit Treadmill Customer Analysis: EDA & Probability Assessment with Python

This project presents a detailed exploratory data analysis (EDA) and probability assessment of Aerofit’s treadmill customers using Python and pandas.  
We uncover customer profiles, product preferences, and actionable business recommendations to help Aerofit better target its marketing and sales strategies.

---

## 📊 Project Overview

- **Dataset:** 180 customers who purchased a treadmill from Aerofit stores over three months.
- **Features:** Product type, Age, Gender, Education, Marital Status, Weekly Usage, Fitness, Income, and Expected Weekly Mileage.
- **Goal:** Profile customers for each treadmill model, analyze key demographic and behavioral factors, and compute marginal and conditional probabilities to guide strategic decisions.

---

## 📈 Key Insights

- **Product Preferences:**  
  - KP281 is the most popular model (44%), followed by KP481 (33%) and KP781 (22%).
- **Demographics:**  
  - 58% of buyers are male; 59% are partnered.
  - Most customers are aged 18–33, with education levels above 13 years.
- **Usage Patterns:**  
  - Median weekly usage: 3–4 times; median mileage: 94 miles.
  - Income and mileage show high variability and outliers.
- **Customer Segments:**  
  - KP281: Younger, lower income, moderate fitness.
  - KP481: Middle income, moderate to high usage.
  - KP781: Higher income, advanced fitness, predominantly male.

---

## 🧮 Probability Analysis

- **Marginal Probabilities:**  
  - 44% purchased KP281, 33% KP481, 22% KP781.
  - 58% are male; 42% female.
  - 59% partnered; 41% single.
- **Conditional Probabilities:**  
  - Product preference varies significantly by gender, age, income, and fitness level.
  - KP781 has a strong male skew and is favored by higher-income, high-fitness customers.

---

## 📝 Methodology

- **Data Cleaning:** Checked for missing values and duplicates (none found).
- **Statistical Summary:** Assessed central tendency and dispersion for all numerical features.
- **Outlier Detection:** Identified outliers in income and weekly mileage.
- **Univariate & Bivariate Analysis:** Visualized distributions and relationships by product, gender, marital status, and other features.
- **Probability Computation:** Calculated marginal and conditional probabilities to inform marketing strategy.

---

## 📂 Data Dictionary

| Column         | Description                                        |
|----------------|----------------------------------------------------|
| Product        | Treadmill model (KP281, KP481, KP781)              |
| Age            | Age of customer (years)                            |
| Gender         | Male/Female                                        |
| Education      | Years of education                                 |
| MaritalStatus  | Single/Partnered                                   |
| Usage          | Planned weekly usage (times per week)              |
| Fitness        | Self-rated fitness (1–5 scale)                     |
| Income         | Annual income (USD)                                |
| Miles          | Expected weekly mileage (miles)                    |

---

## 💡 Recommendations

- **Targeted Marketing:**  
  - Promote KP781 to female customers to address gender imbalance.
  - Highlight affordable payment plans for KP281/KP481 to attract budget-conscious buyers.
- **Product Positioning:**  
  - KP281: Young adults, entry-level fitness.
  - KP481: Middle-income, regular users.
  - KP781: High-income, advanced fitness, currently male-dominated.
- **App Integration:**  
  - Offer app-based progress tracking and personalized workout plans.
- **Customer Profiling:**  
  - Use demographic insights to personalize recommendations and campaigns.

---

> **Data-driven profiling empowers smarter product recommendations and targeted growth.**


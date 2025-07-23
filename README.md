# Cutomer_coupon_analysis

## Overview
This project analyzes customer behavior using a dataset from the UCI Machine Learning Repository. The goal is to explore which types of drivers are most likely to accept different types of driving coupons. The dataset includes driving scenarios, passenger information, and five different coupon categories: bar, coffee house, carry out, less expensive restaurants, and expensive restaurants.

## Objective
To determine the characteristics of drivers who accept versus reject specific coupon offers using descriptive statistics, visualizations, and probability-based reasoning.

---

## 📊 Key Analyses Performed

### 1. Proportion of Accepted Bar Coupons
We calculated the acceptance rate of bar coupons across the entire dataset.

### 2. Behavioral Insights
We explored how behavior such as frequency of bar visits, age group, passenger type, and occupation affect coupon acceptance. This included:
- Comparing high bar-goers vs. low bar-goers
- Comparing older vs. younger drivers
- Analyzing the effect of passengers (child or not)
- Filtering out specific occupations

### 3. Layered Logical Comparisons
We built on earlier analyses by applying compound filters using logical `and` / `or` operations to group drivers by nuanced traits and compare acceptance rates.

### 4. Coffee Coupon Group (Independent Investigation)
We performed a separate analysis for coffee coupon acceptors, using similar logic to the bar coupon analysis. This included comparisons by age, income, and visit frequency.

---

## 📈 Visualizations
The project uses:
- Histograms and bar plots for categorical comparisons
- Matplotlib and Seaborn for visual clarity
- Clean labels and scaling for readability

---

## ✅ Findings

**Bar Coupons:**
- Drivers who visit bars more than once a month have noticeably higher acceptance rates.
- Age and occupation also influence bar coupon acceptance, with younger, social drivers showing greater responsiveness.

**Coffee Coupons:**
- Frequent coffee drinkers and those with higher income are more likely to accept coffee coupons.
- The presence of passengers and time of day also showed some correlation.

**Overall Insight:**
Drivers who exhibit higher frequency behavior (more visits to bars/coffee houses), and who are not constrained by age or social factors (e.g., passengers, occupation), tend to be more likely to accept coupons.

---

## 🔍 Next Steps
- Further explore multivariate relationships using logistic regression
- Use clustering techniques to segment coupon-accepting profiles
- Deploy findings into a real-world recommendation model for targeted couponing

---

## 📁 Files Included
- `coupon_analysis.ipynb`: Main analysis and visualizations
- `README.md`: Summary of the project
- (Optional) `data.csv`: Dataset used in the notebook

---

## 🖥 GitHub Repository
This project is part of the UC Berkeley Machine Learning course portfolio. The full notebook and outputs are publicly accessible at:

➡️ **[GitHub Repository Link]**

---


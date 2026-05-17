# Large-Scale A/B Testing & Experimentation Analysis

**Comprehensive statistical analysis** of a large-scale A/B test to evaluate the impact of a new product variant on conversion rate and revenue.

![Python](https://img.shields.io/badge/Python-3776AB.svg?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458.svg?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243.svg?style=flat&logo=numpy&logoColor=white)
![Statsmodels](https://img.shields.io/badge/Statsmodels-000000.svg?style=flat)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11577B.svg?style=flat&logo=matplotlib&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?style=flat&logo=jupyter&logoColor=white)

## 📋 Project Overview

Analyzed a real e-commerce A/B experiment (892K sessions, 887K unique users).

## 🎯 Key Results

- **Conversion Rate**: +0.02 p.p. (0.48% → 0.50%)
- **Bayesian Probability**: 88.85% that B is better
- **Revenue Uplift** (Bootstrap 10k): **+$0.0166** (97.8% prob.)

## 📈 Treatment Effect Dynamics

**Daily Treatment Effect (B - A)**

<img src="visualizations/daily_treatment_effect.png" width="750">

**Effect by Day of Week**

<img src="visualizations/weekday_effect.png" width="650">

## 💡 Recommendation

**Launch Variant B** — positive revenue effect outweighs statistical uncertainty.

## 🛠️ Stack
Python • pandas • statsmodels • Matplotlib • Jupyter

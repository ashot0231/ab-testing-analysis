📊 A/B Testing Analysis: Conversion Rate Experiment

📌 Project Overview

This project analyzes an A/B test designed to evaluate the impact of a product change on user conversion rates. The goal is to determine whether variant B leads to a statistically significant improvement over variant A.

📂 Dataset

The dataset contains user-level experiment data, including:

unique user visits (visit_id)
assigned variant (A/B)
conversion outcome (0/1)

Data was cleaned by removing duplicate user entries to ensure unbiased analysis.

🧪 Methodology

The analysis follows a structured experimentation framework:

1. Data Cleaning & Exploration
Removed duplicate visit_id entries
Checked distribution of users across variants
Computed baseline conversion rates for A and B
2. Statistical Testing (Frequentist Approach)
Conducted a two-sample Z-test for proportions
Formulated hypotheses:
H₀: pA = pB
H₁: pA ≠ pB
Evaluated statistical significance of conversion difference
3. Power Analysis
Calculated statistical power using Normal approximation
Evaluated ability to detect Minimum Detectable Effect (MDE = 0.1%)
Ensured experiment reliability and sample adequacy
4. Bayesian A/B Testing
Applied Beta-Binomial model:
Non-informative prior (α=1, β=1)
Estimated posterior distributions for both variants
Computed:
P(B > A), probability that variant B is better
📈 Key Analyses Performed
Conversion rate comparison (A vs B)
Hypothesis testing (Z-test)
Power analysis (experiment reliability check)
Bayesian probability estimation
Confidence intervals for conversion rates
🛠️ Tools & Technologies
Python
Pandas, NumPy
Statsmodels
Matplotlib
Bayesian inference (Beta distribution)
📊 Key Insights
Statistical testing used to evaluate significance of observed differences
Bayesian analysis provided probabilistic interpretation of variant performance
Power analysis confirmed whether experiment size is sufficient for detection
🎯 Conclusion

This project demonstrates a full A/B testing workflow, including:

data cleaning
frequentist statistical testing
Bayesian analysis
experiment validation via power analysis

It provides a structured approach to data-driven decision making in product analytics.

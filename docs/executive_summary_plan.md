# Executive Summary: Data-Driven Strategy for Increasing Employee Retention at Salifort Motors

## The Problem / The Hypothesis
Salifort Motors is experiencing elevated employee turnover, particularly within support, accounting, and HR departments. This attrition is costly—disrupting operations and inflating recruitment and training expenses. Traditional HR metrics have proven insufficient to anticipate departures. We hypothesize that a predictive, data-driven approach can surface underlying patterns and proactively identify at-risk employees.

## The Solution
We developed a machine learning–based predictive model using internal HR and survey data to assess employee attrition risk. By combining statistical modeling with interpretability techniques, we isolated key drivers of turnover and translated these into actionable insights for HR interventions.

## Details / Key Insights

### Analytical Approach
- Combined HR records and employee satisfaction data for model input.
- Engineered features reflecting workload, tenure, compensation, and promotion history.
- Trained and validated a logistic regression model.

### Model Findings
- The final logistic regression model achieved an **AUC of 0.83** and **recall of 0.80** on leaver prediction.
- Key predictors of attrition included:
  - **Low salary** and **long tenure** → higher risk
  - **Recent promotions**, **higher satisfaction**, and **more project involvement** → lower risk

### Observational Insights
- Employees who eventually left worked longer hours, had higher performance scores, and were less likely to be promoted.
- Retention was stronger in R&D and management roles; weakest in HR, accounting, and support.
- Work accidents had a minor but notable positive correlation with promotion rates.

## Next Steps & Recommendations
- Deploy pilot retention strategies tailored to high-risk profiles, especially in vulnerable departments.
- Prioritize interventions addressing compensation equity, promotion frequency, and job satisfaction.
- Integrate the attrition risk model into HR dashboards to enable ongoing, real-time monitoring.
- Evaluate pilot outcomes over a 3–6 month period, refining strategies based on feedback and new data.

This data-driven approach positions HR as a proactive strategic partner, with measurable gains in retention and workforce stability.

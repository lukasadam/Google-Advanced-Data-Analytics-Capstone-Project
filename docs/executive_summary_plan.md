# Executive Summary: Data-Driven Strategy for Increasing Employee Retention at Salifort Motors

## The Problem / The Hypothesis

Salifort Motors is experiencing elevated employee turnover. This attrition disrupts operations and increases recruitment and training costs. Traditional HR metrics have proven insufficient to anticipate departures. We hypothesize that a predictive, data-driven approach can surface underlying patterns and proactively identify at-risk employees.

## The Solution

We developed a machine learning–based predictive model using internal HRIS data to assess employee attrition risk. The modeling process prioritized both interpretability and predictive performance—starting with a logistic regression model for insight generation, and advancing to a tuned ensemble model for operational accuracy. The resulting outputs support targeted HR interventions aimed at reducing turnover.

## Details / Key Insights

### Analytical Approach

- **Data Source**: Solely used Salifort Motors’ HRIS dataset, encompassing employee demographics, compensation, workload, promotions, and performance.
- **Initial Modeling**: Built a logistic regression model to identify interpretable predictors of attrition. This model served as a baseline and provided strong insight into causal drivers.
- **Model Enhancement**: To improve predictive power, we implemented an ensemble model selection framework (including Random Forest, Gradient Boosting, SVC, XGBoost, and CatBoost classifiers). We used **Hyperopt**, a Bayesian optimization library, to automatically tune hyperparameters via cross-validation.

### Model Performance

- The logistic regression model achieved **precision of 0.9936** and **recall of 0.9962** for identifying employees at risk of leaving.
- Ensemble models further improved accuracy, robustness, and generalization—enhancing suitability for production deployment.

### Exploratory Findings & Key Drivers

Employees who left the company showed consistent and distinct patterns:

- **Workload & Performance**:
  - Higher average monthly hours, more projects, and stronger evaluation scores—indicating potential overuse of high performers.

- **Career Progression**:
  - Less likely to be promoted in the last 5 years; more likely to be in lower salary bands.

- **Job Satisfaction & Tenure**:
  - Significantly lower satisfaction levels and longer average tenure—suggesting latent disengagement over time.

- **Departmental Distribution**:
  - Turnover rates were broadly consistent across departments, with only **slightly elevated** attrition in support, accounting, and HR.

- **Unexpected Correlation**:
  - A minor but statistically significant finding showed employees who had experienced a work accident were **slightly more likely to be promoted**, warranting further exploration.

### Inferred Attrition Factors

1. **Stalled Advancement**: Long tenure without promotion created perceptions of stagnation and prompted exits.
2. **Burnout Risk**: High performers with increased workloads were more prone to attrition—likely due to stress or imbalance.
3. **Compensation Gaps**: Lower salaries among leavers suggest that pay dissatisfaction played a role.
4. **Disengagement**: Persistent low satisfaction scores indicate a disconnect from organizational culture or job meaning.

### Key Predictors Identified

- **Increased Risk**: Low salary, long tenure, lack of recent promotions, and low satisfaction.
- **Decreased Risk**: Recent promotions, higher satisfaction, and more project involvement.

## Next Steps & Recommendations

1. **Design and Launch Employee Retention Programs**
   - Develop targeted initiatives to address root causes of attrition:
     - **Career Advancement & Compensation Equity**: Conduct a salary audit and establish clearer criteria for performance-based raises & promotions. Create fast-track promotion pathways and expand lateral mobility options.
     - **Mental Health & Burnout Prevention**: Offer flexible scheduling, mental health resources, and workload balancing tools.
     - **Employee Engagement**: Launch engagement campaigns focused on recognition, inclusion, and feedback responsiveness.

2. **Operationalize the Attrition Risk Model**
   - Integrate the predictive model into HR dashboards and employee management systems.
   - Automate monthly updates of attrition risk scores to flag high-risk individuals for proactive support.
   - Provide actionable toolkits for people managers based on program strategies.

3. **Evaluate Intervention Impact**
   - Define success metrics such as retention rates, promotion velocity, employee satisfaction, and internal transfers.
   - Use control groups and time-based comparisons to assess effectiveness of retention programs.

4. **Close Data Gaps and Enhance Inputs**
   - Supplement HRIS data with qualitative inputs like exit interviews, engagement surveys, and 360-degree feedback.
   - Periodically reassess model features to reflect evolving organizational realities.

5. **Ensure Ethical and Transparent Implementation**
   - Communicate goals, benefits, and safeguards of predictive modeling to internal stakeholders.
   - Focus on support-driven use of risk scores to prevent misuse or perceived surveillance.
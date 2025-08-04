# Project Proposal: Data-Driven Strategy for Increasing Employee Retention at Salifort Motors

## Objective
Generate actionable strategies to improve employee retention at Salifort Motors, supported by a predictive model that identifies employees at risk of leaving based on their department, workload, and other relevant factors.

## Background
Salifort Motors faces a high rate of employee turnover, which affects operational continuity and increases costs in recruitment, training, and development. Leadership seeks to better understand why employees leave and to implement targeted retention strategies. A predictive model, informed by employee data and survey insights, can highlight at-risk individuals and reveal systemic issues contributing to attrition.

## Scope
- Analyze available employee and survey data to identify turnover trends.
- Build a predictive model using variables such as department, number of projects, average monthly hours, and other relevant data.
- Extract key insights to explain turnover behavior.
- Deliver a set of tailored recommendations for improving employee retention based on model findings.

## Methodology
1. **Data Assessment & Preparation**:
   - Clean and consolidate HR dataset.
   - Explore patterns in turnover behavior across job roles, departments, and workloads.

2. **Feature Engineering**:
   - Construct predictive features from variables such as:
     - Department
     - Number of projects
     - Average monthly hours
     - Tenure
     - Satisfaction level

3. **Model Development**:
   - Train predictive models (logistic regression, decision trees, random forest, XGBoost).
   - Evaluate performance using accuracy, precision, recall, and AUC.

4. **Insights & Recommendation Design**:
   - Identify the most significant predictors of turnover.
   - Collaborate with HR to map findings to retention strategies.
   - Prioritize interventions by feasibility and impact.

5. **Executive Communication**:
   - Prepare a high-level summary with recommendations.
   - Deliver technical insights and modeling documentation.

## Data Sources
- HRIS dataset

## Timeline

<pre><code>```mermaid gantt title Project Timeline dateFormat YYYY-MM-DD axisFormat Week %W section Phases Data Collection & EDA :done, dc, 2025-08-04, 14d Feature Engineering :fe, 2025-08-18, 7d Model Development :md, 2025-08-25, 14d Insight Extraction :ie, 2025-09-08, 7d Recommendation Design :rd, 2025-09-15, 7d Final Presentation :fp, 2025-09-22, 7d ``` </code></pre>

## Deliverables
- Predictive model identifying employees at risk of turnover
- List of most impactful turnover drivers
- A set of strategic and tactical recommendations for improving retention
- Executive summary and technical appendix

## Risks
- Missing or incomplete employee data
- Non-representative survey sample
- Misalignment between model insights and organizational priorities

## Business Impact
- Reduced costs from lower turnover rates
- Improved employee engagement and morale
- Enhanced ability to proactively address workforce issues

## Success Criteria
- Predictive model with AUC > 0.75
- Identification of top 5 drivers of turnover
- Presentation of at least 3 actionable recommendations
- Leadership approval of at least 1 pilot intervention within 3 months

## Team & Roles
- **Data Analyst**: Data cleaning, modeling, and insights extraction
- **HR Representative**: Data validation and implementation planning
- **Project Lead**: Coordination, quality assurance, stakeholder engagement

---

## Project Milestones and PACE Assignments

| Milestone                                | Task Description                                                                 | PACE Step      |
|------------------------------------------|----------------------------------------------------------------------------------|----------------|
| M1. Data Integration                     | Combine survey and HR data for unified analysis                                 | Prepare        |
| M2. Exploratory Data Analysis            | Detect turnover trends and data quality issues                                  | Prepare        |
| M3. Feature Engineering                  | Create variables from workload, department, hours, etc.                         | Prepare        |
| M4. Model Training                       | Train and tune predictive models                                                | Analyze        |
| M5. Model Evaluation                     | Assess model performance and robustness                                         | Analyze        |
| M6. Driver Analysis                      | Identify key variables influencing turnover                                     | Communicate    |
| M7. Retention Strategy Design            | Develop actionable recommendations based on insights                            | Communicate    |
| M8. Reporting & Executive Review         | Present findings and recommendations to leadership                              | Execute        |

# Google Advanced Data Analytics Capstone Project

<img src="images/certificate.png" alt="Google Certificate" width="200" align="right">

This repository contains the final capstone project for the **Google Advanced Data Analytics Professional Certificate**. The project follows the PACE framework (Plan, Analyze, Construct, Execute) to solve a real-world business challenge using a complete data analytics pipeline.

---

## 🌀 PACE Framework Overview

### 🔹 Plan
- `docs/project_proposal.md`: Problem statement, stakeholder analysis, and objectives  
- `docs/executive_summary_plan.md`: Business understanding and goals  

### 🔹 Analyze
- `notebooks/1_data_cleaning.ipynb`: Data preprocessing and cleaning  
- `notebooks/2_exploratory_analysis.ipynb`: EDA and statistical insights  
- `notebooks/3_feature_engineering.ipynb`: Transformation and feature selection  

### 🔹 Construct
- `notebooks/4_model_building.ipynb`: Machine learning model development  
- `models/`: Saved model files (e.g., `.pkl`, `.joblib`) and training logs  
- `docs/model_report.md`: Evaluation metrics and model selection rationale  

### 🔹 Execute
- `docs/executive_summary_final.md`: Final presentation of findings and recommendations  
- `notebooks/5_final_dashboard_or_visuals.ipynb`: Visualizations and key insights  
- `docs/business_recommendation.md`: Actionable recommendations for stakeholders  

---

## 🗂️ Project Structure

```
Google_Advanced_Data_Analytics_Capstone_Project/
│
├── data/ # Raw and cleaned datasets
│ ├── raw/
│ └── processed/
│
├── docs/ # Project proposal, execute summary, general instructions
│
├── notebooks/ # Jupyter Notebooks for analysis
│
├── models/ # Trained models and logs
│
├── images/ # Visuals and certificate
│ └── certificate.png
│
├── README.md # This file
└── requirements.txt # Python dependencies
```
---

## Highlights

## **Capstone project: Data-Driven Strategy for Increasing Employee Retention at Salifort Motors**

### 📈 Objective

This capstone project is an opportunity for you to analyze a dataset and build predictive models that can provide insights to the Human Resources (HR) department of a large consulting firm.

Upon completion, you will have two artifacts that you would be able to present to future employers. One is a brief one-page summary of this project that you would present to external stakeholders as the data professional in Salifort Motors. The other is a complete code notebook provided here. Please consider your prior course work and select one way to achieve this given project question. Either use a regression model or machine learning model to predict whether or not an employee will leave the company. The exemplar following this actiivty shows both approaches, but you only need to do one.

In your deliverables, you will include the model evaluation (and interpretation if applicable), a data visualization(s) of your choice that is directly related to the question you ask, ethical considerations, and the resources you used to troubleshoot and find answers or solutions.

### Understand the business scenario and problem

The HR department at Salifort Motors wants to take some initiatives to improve employee satisfaction levels at the company. They collected data from employees, but now they don’t know what to do with it. They refer to you as a data analytics professional and ask you to provide data-driven suggestions based on your understanding of the data. They have the following question: what’s likely to make the employee leave the company?

Your goals in this project are to analyze the data collected by the HR department and to build a model that predicts whether or not an employee will leave the company.

If you can predict employees likely to quit, it might be possible to identify factors that contribute to their leaving. Because it is time-consuming and expensive to find, interview, and hire new employees, increasing employee retention will be beneficial to the company.

### Familiarize yourself with the HR dataset

The dataset that you'll be using in this lab contains 15,000 rows and 10 columns for the variables listed below. 

**Note:** you don't need to download any data to complete this lab. For more information about the data, refer to its source on [Kaggle](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv).

Variable  |Description |
-----|-----|
satisfaction_level|Employee-reported job satisfaction level [0&ndash;1]|
last_evaluation|Score of employee's last performance review [0&ndash;1]|
number_project|Number of projects employee contributes to|
average_monthly_hours|Average number of hours employee worked per month|
time_spend_company|How long the employee has been with the company (years)
Work_accident|Whether or not the employee experienced an accident while at work
left|Whether or not the employee left the company
promotion_last_5years|Whether or not the employee was promoted in the last 5 years
Department|The employee's department
salary|The employee's salary (U.S. dollars)

### Reflect on these questions as you complete the plan stage.

*  Who are your stakeholders for this project?
- What are you trying to solve or accomplish?
- What are your initial observations when you explore the data?
- What resources do you find yourself using as you complete this stage? (Make sure to include the links.)
- Do you have any ethical considerations in this stage?
---


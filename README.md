
# AI Job Market & Salary Trends 2025

A complete data science project that analyzes global AI and machine learning job trends, salaries, skills, company insights, and remote work patterns using a comprehensive dataset of over 15,000 job postings collected from January 2024 to May 2025.

---

## 📁 Project Structure

This repository is organized into multiple Jupyter Notebooks, each focusing on a specific phase of the data science pipeline:

| Notebook File | Description |
|---------------|-------------|
| `AI_Job_Market_01_Data_Loading_Preparation.ipynb` | Loads and explores the raw dataset for structure and initial insights. |
| `AI_Job_Market_02_Exploratory_Data_Analysis.ipynb` | Performs visual EDA on salaries, experience levels, skills, and more. |
| `AI_Job_Market_03_Data_Cleaning_Feature_Engineering.ipynb` | Cleans the data and creates new features like `job_posting_duration` and `remote_friendly`. |
| `AI_Job_Market_04_Geographic_Visualizations.ipynb` | Analyzes trends and distributions across countries. |
| `AI_Job_Market_05_Salary_Prediction_Modeling.ipynb` | Builds a regression model to predict salaries from job and company features. |
| `AI_Job_Market_06_Skill_Demand_Analysis.ipynb` | Identifies the most in-demand skills and their frequency. |
| `AI_Job_Market_07_Company_Insights_and_Benefits.ipynb` | Analyzes company size, benefits scores, and employment types. |
| `AI_Job_Market_08_Time_Series_and_Trend_Analysis.ipynb` | Analyzes job posting trends over time. |
| `AI_Job_Market_09_Salary_Prediction_With_Testing.ipynb` | Adds evaluation (R², MSE), comparison of predicted vs actual salaries, and feature importance. |
| `AI_Job_Market_10_End_to_End_Salary_Pipeline.ipynb` | Implements a complete ML pipeline using `ColumnTransformer`, `Pipeline`, and optional `GridSearchCV`. |

---

## 📊 Dataset Overview

- **Source**: [Global AI Job Market & Salary Trends 2025 - Kaggle Dataset](https://www.kaggle.com/datasets/bismasajjad/global-ai-job-market-and-salary-trends-2025)
- **Author**: [Bisma Sajjad](https://www.kaggle.com/bismasajjad)
- **Size**: ~15,000 job listings from 50+ countries
- **Key Fields**: `salary_usd`, `job_title`, `experience_level`, `remote_ratio`, `company_size`, `required_skills`, `benefits_score`, etc.
- **Date Range**: January 2024 – May 2025

---

## 💡 Key Use Cases

- **Salary Prediction** using ML models (Random Forest, Linear Regression)
- **Top Skills Identification** based on frequency and job category
- **Remote Work & Geographic Trends** visualizations
- **Company Insights** via benefits scoring and job types
- **Time Series Analysis** of hiring patterns

---

## 🧰 Requirements

Install required libraries via pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 📌 How to Use

1. Clone this repository or download the notebooks.
2. Run notebooks sequentially from 01 to 10.
3. Optionally, plug in your own data using the same schema.
4. Extend the project with new models, SHAP explanations, or dashboards!

---

## 📜 License

This project is licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).  
Original dataset licensed under [CC BY 4.0] by the dataset creator on Kaggle.

---

## 🙌 Acknowledgments

- Data Source: [Global AI Job Market & Salary Trends 2025 on Kaggle](https://www.kaggle.com/datasets/bismasajjad/global-ai-job-market-and-salary-trends-2025)
- Author: Bisma Sajjad
- This project is intended for educational and research purposes only.

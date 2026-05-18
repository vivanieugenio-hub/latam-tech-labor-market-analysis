# LATAM Tech Labor Market Analysis 2024
![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue)
![Pandas](https://img.shields.io/badge/Pandas-EDA-black)
![Looker Studio](https://img.shields.io/badge/Looker-Studio-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Dashboard Preview](images/dashboard_overview.png)
Data analysis and interactive dashboard exploring salary trends, remote work adoption, AI usage and technology preferences among developers in Latin America.

---

## Project Overview

This project analyzes data from the Stack Overflow Developer Survey 2024 to identify key labor market trends across LATAM countries.

The analysis focuses on:

- Salary distribution across countries
- Salary differences by seniority
- Remote work adoption
- AI tool usage
- Most used technologies
- Workforce trends in the regional tech ecosystem

The dashboard was designed to simulate real-world business intelligence reporting workflows and labor market analysis.

---

## Business Value

This analysis can support:
- Hiring strategy evaluation
- Compensation benchmarking
- Remote work policy analysis
- Technology trend monitoring
- Workforce planning across LATAM markets

--- 

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- Looker Studio
- GitHub

---

## Dataset

Source:
Stack Overflow Developer Survey 2024

https://survey.stackoverflow.co/2024/

Due to GitHub file size limitations, the original raw dataset is not included in this repository.

The repository contains processed datasets used for data cleaning, exploratory analysis and dashboard development.

---

## Methodology

- Data cleaning and preprocessing using Python and Pandas
- Filtering LATAM respondents from the Stack Overflow Developer Survey 2024
- Exploratory Data Analysis (EDA) on salary, seniority and remote work variables
- Dashboard development and storytelling using Looker Studio

---

## Key Insights

- In LATAM, salary progression in the tech sector is strongly linked to seniority. Developers with more than 10 years of experience earn nearly 3x more than junior profiles with less than 2 years in the industry. Senior salaries frequently exceed USD 45K–50K annually, while junior compensation often remains below USD 15K. Brazil and Chile concentrate the highest median salary ranges in the region (~USD 30K–40K), while Argentina and Colombia tend to show lower compensation levels.

- Remote and hybrid work models now dominate the regional tech ecosystem, representing more than half of the employment arrangements observed in the dataset. Senior developers show the highest participation in fully remote roles, while junior profiles remain more concentrated in hybrid and onsite positions. This suggests that access to international remote opportunities continues to favor experienced talent.

- Technology adoption patterns reveal a strong convergence between software engineering and data-oriented workflows. JavaScript, Python and SQL consistently appear as the most widely used technologies across the region, reflecting sustained demand for versatile multi-stack profiles. The strong presence of SQL and Python also highlights the growing importance of data-related skills beyond traditional software development roles.

- AI adoption appears significantly stronger among experienced developers, indicating faster integration of AI-assisted workflows within senior technical roles. Higher AI usage among senior professionals may reflect greater access to organizational resources, workflow autonomy and experimentation opportunities. The growing penetration of AI tools suggests that familiarity with AI-assisted development is rapidly becoming a baseline expectation across the regional tech workforce.

---

## Interactive Dashboard

[View Dashboard Here](https://datastudio.google.com/reporting/edb97cbc-affb-474e-a0f2-77ff2e6f34ad)

---

## Dashboard Features

- Dynamic country filtering
- Seniority segmentation
- Salary benchmarking
- AI adoption analysis
- Technology usage trends
- Remote work distribution analysis

---

## Dashboard Preview

### Market Overview

![Dashboard Overview](images/dashboard_overview.png)

---

### Salary & Experience Analysis

![Salary Analysis](images/salary_analysis.png)

---

### AI & Technology Trends

![AI Trends](images/ai_trends.png)

---

## Project Structure

```bash
latam-tech-labor-market-analysis/
│
├── data/
├── notebooks/
├── images/
├── README.md
└── requirements.txt
```
---

## Workflow

Raw Survey Data

↓

Data Cleaning & Preprocessing (Python/Pandas)

↓

Exploratory Data Analysis

↓

Feature Engineering

↓

Interactive Dashboard Development (Looker Studio)

↓

Market Insights & Storytelling

---

## Future Improvements

- Add salary distribution histograms
- Incorporate role-specific salary analysis
- Explore correlations between AI usage and compensation
- Include country-level technology specialization analysis
- Build SQL version of the analysis pipeline

--- 

## Author

Eugenio Vivani

LinkedIn:
https://www.linkedin.com/in/eugenio-vivani/

GitHub:
https://github.com/vivanieugenio-hub

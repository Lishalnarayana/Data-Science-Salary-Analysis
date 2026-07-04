# 📊 Data Science Salary Analysis

## Project Overview

This project analyzes global data science salaries from 2020–2022 to identify the factors that influence compensation across different experience levels, job roles, company sizes, work arrangements, and geographic locations.

Using Python, the project performs data cleaning, exploratory data analysis (EDA), data visualization, and develops a Linear Regression model to analyze salary trends and predict salaries based on job-related features.

---

## Dataset

- **Dataset:** Data Science Salaries (2020–2022)
- **Records:** 607 salary records
- **Features:** Experience level, employment type, job title, salary, company size, remote work ratio, company location, employee residence, and more.

---

## Business Questions

This project explores the following questions:

1. Does experience level influence salary?
2. Do larger companies pay higher salaries?
3. Does remote work affect salary?
4. Which data science job roles have the highest average salary?
5. How did salaries change between 2020 and 2022?
6. Can machine learning accurately predict salaries based on job-related features?

---

## Machine Learning

A **Linear Regression** model was developed as a baseline regression model to predict salaries using job-related features.

The workflow includes:

- Data preprocessing
- Feature encoding
- Train-test split
- Model training
- Model evaluation using regression metrics

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Structure

```
Data-Science-Salary-Analysis/
│
├── salary_analysis.ipynb
├── ds_salaries.csv
├── requirements.txt
├── README.md
└── .gitignore
```

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/Lishalnarayana/Data-Science-Salary-Analysis.git
```

2. Navigate to the project directory

```bash
cd Data-Science-Salary-Analysis
```

3. Install the required dependencies

```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook

```bash
jupyter notebook
```

5. Open

```
salary_analysis.ipynb
```

---

## Key Insights

- Executive and Senior professionals earn significantly higher average salaries than Entry-level and Mid-level professionals.
- Larger companies generally offer higher average compensation than small and medium-sized companies.
- Remote work provides competitive salaries across many data science roles.
- Specialized positions such as Machine Learning Engineer and Data Scientist consistently rank among the highest-paying roles.
- Average salaries increased steadily between 2020 and 2022.
- Experience level is one of the strongest predictors of salary.

---

## Project Results

The analysis demonstrates a clear relationship between professional experience and salary. As experience increases, average annual compensation also increases, with Executive-level professionals earning the highest salaries.

### Average Annual Salary by Experience Level (2020–2022)

<img width="951" height="569" alt="Average Salary by Experience Level" src="https://github.com/user-attachments/assets/4aebe9aa-bbaa-4e5b-af13-34549004613c" />

The visualization highlights a consistent upward trend in salary across career stages, emphasizing the impact of professional experience on compensation within the data science industry.

---

## Future Improvements

- Evaluate additional machine learning models such as Random Forest and XGBoost.
- Include more recent salary datasets to analyze long-term trends.
- Develop an interactive dashboard using Streamlit or Tableau.
- Perform geographic salary analysis using interactive maps.
- Deploy the project as a web application for interactive exploration.

---

## Author

**Lisha Lakshmi Narayana**

M.S. in Computer Science  
Case Western Reserve University

GitHub: [Lisha Lakshmi Narayana](https://github.com/Lishalnarayana)

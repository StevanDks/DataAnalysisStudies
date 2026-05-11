# Data Analysis Studies

A collection of data analysis and statistics projects developed in Python using Jupyter Notebooks, covering exploratory data analysis, data visualization, and hypothesis testing.

---

## Projects

### 1. Student Dropout Analysis (`student_dropout_analysis.ipynb`)
Exploratory analysis of a dataset with 700 students from secondary school, investigating factors that contribute to school dropout.

**Topics covered:**
- Data cleaning and organization
- Correlation heatmap between variables
- Relationship between parental education level and dropout rate
- Impact of previous failures on grades
- Data visualization with Matplotlib and Seaborn

**Dataset:** Student dropout data from Kaggle (700 rows, 35 columns)

---

### 2. Heart Attack Risk Analysis (`heart_attack_risk_analysis.ipynb`)
Data visualization exercise using a heart attack risk dataset, exploring relationships between demographic and clinical variables.

**Topics covered:**
- Bar charts comparing heart attack risk by gender
- Pie charts for risk distribution
- Age distribution by gender
- Outlier removal and scatter plots (age vs cholesterol)
- Blood pressure analysis by chest pain type and gender

---

### 3. Hypothesis Testing (`hypothesis_testing.ipynb`)
Statistical hypothesis testing using Seaborn datasets, applying one-sample and two-sample t-tests.

**Tests performed:**

| Dataset | Test | Hypothesis | Result |
|---------|------|------------|--------|
| Taxis | One-sample t-test | Mean tip = $2 | Fail to reject H₀ |
| Taxis | Two-sample t-test | Credit card tips = Cash tips | Reject H₀ |
| Flights | One-sample t-test | Mean passengers = 300 | Fail to reject H₀ |
| Flights | Two-sample t-test | Passengers 1949 = 1950 | Fail to reject H₀ |

---

## Tech Stack

- **Python 3.11**
- **Pandas** — data manipulation
- **NumPy** — numerical computing
- **Matplotlib** — data visualization
- **Seaborn** — statistical data visualization
- **SciPy** — statistical hypothesis testing
- **Jupyter Notebook** — interactive development

---

## Project Structure

```
DataAnalysis-Studies/
├── student_dropout_analysis.ipynb
├── student dropout.csv
├── heart_attack_risk_analysis.ipynb
└── hypothesis_testing.ipynb
```

---

## License

This project is licensed under the [MIT License](LICENSE).
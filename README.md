Open in colab to view interactive plots

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1S3TsNtdBD-Dok4O6JAsbXT50_y-0b25V?usp=sharing)
Project Overview
This project provides a deep-dive exploratory data analysis (EDA) of the COVID-19 pandemic. By synthesizing three distinct datasets—global country-level statistics, time-series growth data, and specific US mortality figures—this study transforms raw, often inconsistent data into actionable insights. The analysis focuses on understanding the virus's trajectory, the efficiency of global testing, and the demographic risk factors associated with mortality.

Project Summary
Datasets Used: Country-level statistics, time-series growth data, and US mortality figures categorized by age and condition.

Key Techniques: Data cleaning (handling missing values), feature engineering (CFR calculation), and interactive data visualization.

Cleaning Process: Columns with >90% null values—specifically NewCases, NewDeaths, and NewRecovered—were removed to prevent skewed trend analysis.

Key Insights
1. The Disparity of Global Impact
The analysis reveals a massive disparity in case volumes. While the pandemic was global, a few nations—specifically the USA, Brazil, and India—bore a disproportionate share of the total case burden.

2. Testing Volume vs. Positivity
There is a strong positive correlation between testing volume and total cases. However, vertical dispersion in the data suggests that countries with lower testing volumes relative to cases were likely under-testing, capturing only the most severe outcomes.

3. Age as a Primary Risk Factor
US mortality data confirms that age is the most significant risk factor. Deaths from respiratory diseases like influenza and pneumonia spike drastically in the 65+ age groups, while remaining minimal in the 0–34 demographics.

4. Regional Resilience
While Asia saw high case volumes, the Americas and Europe accounted for a larger slice of total mortality. This underscores the impact of aging populations and comorbidity rates in Western nations compared to younger demographics in Africa.

Technologies Used
Python: Core programming language.

Pandas & NumPy: Data manipulation and cleaning.

Plotly Express: Creating interactive bar charts, scatter plots, and choropleth maps.

Matplotlib & Seaborn: Static data visualization.

Actionable Recommendations
Precision-Targeted Protection: Future public health measures should focus on high-risk age groups and those with pre-existing conditions to minimize economic disruption.

Diagnostic Infrastructure: Investment in rapid testing is as critical as hospital bed capacity for pandemic management.

Data Standardization: A unified global reporting standard is necessary to address the missing data issues encountered in real-time reporting.

How to Use
Ensure you have the following CSV files: covid.csv, covid_grouped.csv, and coviddeath.csv.

Install the required libraries:

Bash
pip install pandas numpy matplotlib seaborn plotly
Run the Jupyter Notebook cells to generate interactive visualizations and view the full statistical analysis.

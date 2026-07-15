
# 🛒 Superstore Sales Analysis

---

## Context
* **Source:** [Kaggle - Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
* **Dataset:** `Dataset/Sample - Superstore.csv` (Contains 9,994 transactional records across 4 years of retail operations).

## Objective
The goal of this project is to perform an in-depth exploratory data analysis (EDA) and business intelligence audit on a Superstore dataset. By examining sales, profit, discounts, and regional/category performance, the analysis identifies key drivers of profitability, uncovers hidden operational inefficiencies (such as logistics costs and discount traps), and provides actionable business recommendations to optimize strategy, inventory, and marketing efforts.

## Notebook Structure & Workflow
The analysis follows a logical BI progression, moving from macro-overviews to targeted forensic deep dives:

1. **Data Loading & Inspection:** Import, inspect structure, handle missing values, and understand key variables.
2. **Data Cleaning & Feature Engineering:** Convert dates, create new metrics (e.g., Profit Margin %, Shipping Days, Discount Levels).
3. **Univariate Analysis:** Explore numerical distributions (Sales, Profit, Discount) and categorical frequencies (Segments, Regions, Categories).
4. **Bivariate Analysis & Correlations:** Identify relationships between numerical features (e.g., the inverse correlation between Discount and Profit).
5. **Product-Centric Analysis:** Deep dive into Category and Sub-Category performance using styled tables and Sunburst charts.
6. **Geographic Analysis:** Interactive choropleth mapping to identify "Red States" (high sales, negative profit) like Texas and Ohio.
7. **Customer & Logistics Impact:** Analyze segment behavior and uncover the hidden margin cost of expedited shipping modes.
8. **Temporal & Seasonality Analysis:** Track monthly trends, investigate the "Black Friday" margin compression (Nov vs. Dec), and solve the Jan 2015 loss anomaly.
9. **Profitability Deep Dive:** Visualize the "20% Discount Trap" using boxplots to prove discounts >20% guarantee losses.
10. **Strategic Recommendations:** Summarize forensic insights into concrete, actionable business actions.

## Key Insights & Takeaways
* **The 20% Discount Trap:** Discounts above 20% do not drive higher purchase volumes; they simply erode margins. Discounts >50% are mathematically guaranteed to lose money.
* **The Furniture Bleed:** The Furniture category generates significant top-line revenue but destroys value. Sub-categories like *Tables* and *Bookcases* operate at a net loss due to aggressive discounting.
* **Geographic Red Zones:** High-sales states like **Texas, Ohio, and Pennsylvania** actually generate net losses, pointing to localized discount abuse or high logistical costs.
* **The November Paradox:** November has the highest sales volume of the year, but lower profits than September or December because Black Friday discounts compress margins.
* **Logistical Inefficiency:** Expedited shipping (First Class/Same Day) disproportionately eats into profit margins compared to Standard Class.

## Tech Stack & Libraries

* **Language:** ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

* **Data Manipulation:** ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)

* **Visualization:** ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat) ![Seaborn](https://img.shields.io/badge/Seaborn-5B8DB8?style=flat) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)

* **Environment:** ![Jupyter Notebook](https://img.shields.io/badge/Jupyter_Notebook-F37626?style=flat&logo=jupyter&logoColor=white) ![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white)

---

*To explore the detailed code, feel free to download the notebook file on this repo, download the pdf file, or check out my [Kaggle](https://www.kaggle.com/code/maximendacleu/superstore-sales-analysis).*

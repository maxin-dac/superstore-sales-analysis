# Superstore Sales Analysis

## Context
* **Source:** [Kaggle - Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
* **Dataset:** `Sample - Superstore.csv`

## Objective
The goal of this project is to perform an in-depth exploratory data analysis (EDA) and profitability analysis on a US Superstore dataset. By examining sales, profit, discounts, and regional/category performance, this analysis identifies the key drivers of profitability and provides actionable business recommendations to optimize strategy, pricing, and inventory management.

---

## Quick Insights & Key KPIs
Before diving into the code, here are the high-level findings uncovered during the analysis:

| KPI | Value | Business Impact |
| :--- | :---: | :--- |
| **Global Profit Margin** | **12.47%** | Healthy overall, but highly compressed by specific sub-categories. |
| **Loss-making Transactions** | **18.7%** | Nearly **1 in 5 transactions** runs at a net loss, heavily driven by aggressive discount policies. |
| **Median Order Value** | **$54.49** | Highly skewed distribution with rare, high-value transactions (up to $22,638). |

> **The Profit Killer:** High discounts (especially those above 20% in specific categories like *Furniture* and *Office Supplies*) do not drive sustainable volume; instead, they severely damage the bottom line.

---

## Tech Stack & Libraries

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/Jupyter_Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />
  <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle" />
</p>

* **Visualization:** `Matplotlib` & `Seaborn`.

---

## Notebook Structure & Workflow

The analysis is structured logically to transition from raw data to strategic insights:

*   **1. Data Loading & Exploration:** 
    *   Inspected data structure, schema, and missing values.
*   **2. Data Cleaning & Feature Engineering:** 
    *   Handled datetime conversions.
    *   Engineered crucial metrics such as `Profit Margin (%)`, `Order Year`, and `Order Month`.
*   **3. Univariate & Bivariate Analysis:** 
    *   Analyzed distributions of numerical variables (`Sales`, `Profit`, `Discount`, `Quantity`).
    *   Mapped categorical variables to find frequency distributions.
*   **4. Profitability Deep Dive:** 
    *   Segmented performance by Product Category/Sub-Category, Geography (Regions & States), and Time (seasonality & monthly trends).
*   **5. Top & Bottom Performers:** 
    *   Identified the "Top 10" profit-generating products and the "Flop 10" loss-makers.
*   **6. Visualizations & Synthesis:** 
    *   Created correlation heatmaps, distribution plots, and granular bar charts.
*   **7. Strategic Recommendations:** 
    *   Translated data findings into concrete business actions.

---

## Key Takeaways
*   **Product Performance:** Furniture represents a high volume of sales but suffers from extremely low margins due to high shipping costs and steep discounts.
*   **Discount Strategy:** Discounts exceeding 20% consistently result in negative margins across almost all product sub-categories.
*   **Geography:** Specific states and regions perform significantly better, suggesting that resource allocation and marketing spend should be geographically targeted.

---

## How to Explore this Project
To explore the detailed code, visualizations, and findings:
*   **Notebook File:** Download and run the `.ipynb` file directly from this repository.
*   **PDF File:** Download the PDF file, ready to be read.
*   **Kaggle:** Check out the interactive notebook and upvote it on [Kaggle](https://www.kaggle.com/code/maximendacleu/superstore-sales-analysis).

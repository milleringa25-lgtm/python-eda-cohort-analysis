# E-commerce Customer Cohort Analysis

## Project Description
This project is dedicated to a detailed study of online store customer behavior using **Exploratory Data Analysis (EDA)** and **Cohort Analysis** methods. The primary objective of the research is to evaluate the effectiveness of marketing acquisition channels, calculate customer retention metrics (Retention Rate), analyze the dynamics of new cohort formation throughout the year, and identify key patterns in total revenue generation.

---

## Tech Stack
The project is implemented in **Python** within the Jupyter Notebook environment, utilizing the following libraries:
* **pandas** — for raw data cleaning, transformation, filtering, and aggregation.
* **numpy** — for fast mathematical and matrix computations.
* **matplotlib** & **seaborn** — for building informative visualizations, distribution plots, and heatmaps.
* **openpyxl** — for reading source data from Excel formats (.xlsx).

---

# HTML Report

The project includes an exported static HTML report featuring interactive charts and detailed summary sections. 

If GitHub Pages is enabled for this repository, you can view the live report here:
## **[Click here to open the notebook directly in Google Colab]([https://milleringa25-lgtm.github.io/python-eda-cohort-analysis/)])**

---

## Results Obtained
During the dataset analysis, the following steps were completed, resulting in the corresponding analytical artifacts:
1. **Data Preprocessing Stage:** Conducted an initial analysis of the data structure, filled missing values, verified and corrected anomalies, and converted time metrics into the required formats.
2. **Segmentation and Profiling:** Users were grouped into cohorts based on the time of their first purchase. The dynamics of customer acquisition were evaluated across months and traffic sources.
3. **Retention Matrix Construction:** Created a classic interaction heatmap (*Cohort Month × Month Elapsed*), where color intensity represents the customer Retention Rate at each stage of their lifecycle.

---

## Key Insights
Based on the results of the study, the following strategic insights and recommendations were formulated:

* **New Customer Acquisition Dynamics:** The largest cohort of 2025 was formed in July, counting **452 new customers**. However, starting from August, acquisition volumes dropped significantly (down to 175–192 customers per month). This directly indicates a noticeable decline in the effectiveness of current marketing campaigns during late summer and autumn.
* **Early Churn Problem:** The retention rate of acquired customers shows a sharp decline as early as **months 1–2** of the cohort's lifespan. This trend highlights a high vulnerability of the product or service specifically at the early stage of user interaction.
* **Quality of Early Cohorts:** Early cohorts (specifically **January and February**) demonstrate the highest long-term retention and the best performance in terms of cumulative revenue. This indicates higher quality and loyalty among users acquired at the beginning of the year.
* **Acquisition Channel Effectiveness:** Among all traffic sources, **Instagram** and **Facebook** clearly stand out in terms of user volume. This confirms that social media networks provide a significantly higher level of new audience engagement compared to paid tools like *Google Ads* (although the latter also consistently ranks in the top three).

### Recommendations:
1. **Focus on Retention:** It is essential to scale marketing activities aimed at retaining customers during months 1–2 after their first purchase.
2. **Budget Optimization:** It is recommended to scale advertising in organic or lower-cost acquisition channels, such as **Email Marketing** and **Referral Programs**, which demonstrate high efficiency in attracting a targeted and loyal audience.

## Project Structure

```text
python-eda-cohort-analysis/
├── data/
│   └── client_base.xlsx                 # Dataset used for the analysis
├── docs/
│   └── index.html                       # Exported interactive HTML report
├── notebooks/
│   └── retention_cohort_analysis_colab.ipynb  # Full analysis workflow (Google Colab)
├── README.md                            # Project overview and documentation
└── requirements.txt                     # List of Python dependencies
```


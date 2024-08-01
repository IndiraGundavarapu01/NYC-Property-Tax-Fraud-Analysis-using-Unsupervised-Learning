### 1. Project Title
**New York Property Tax Fraud Analysis**

### 2. Executive Summary
**Objective:** The primary goal of this project is to analyze the New York Property Tax dataset to identify potential instances of fraud. This involves understanding which rows correspond to fraudulent activity and which do not, utilizing data representing NYC property assessments for calculating property tax and granting eligible properties exemptions or abatements.

**Context:** The analysis was conducted using various data science tools and platforms, including Python for data cleaning and transformation, and various analytical libraries for data analysis.

### 3. Business Problem
**Problem Identification:** The specific business challenge addressed in this project is the detection of fraudulent property tax claims in New York City. Identifying fraud is crucial for ensuring the integrity of the tax system and for the fair distribution of tax burdens and exemptions.

**Business Impact:** Fraudulent property tax claims can lead to significant revenue losses for the city, impacting the funding available for public services. Additionally, undetected fraud can undermine public trust in the tax system and lead to unfair advantages for dishonest property owners.

### 4. Methodology
**Data Cleaning & Transformation:** 
- The dataset consists of 1,070,994 rows and 32 fields, covering the 2010/11 period.
- Data cleaning involved handling missing values, transforming categorical fields, and scaling numeric fields using logarithmic scales to manage wide value ranges.

**Analysis Techniques:**
- Descriptive statistics to understand the distribution and summary metrics of each field.
- Visualization techniques to identify patterns and anomalies.
- Regression analysis and clustering to detect outliers and potential fraudulent activities.

### 5. Skills
**Tools, Languages, & Software:**
- Python for data analysis and visualization.
- Libraries used include Pandas for data manipulation, Matplotlib, and Seaborn for visualization, and Scikit-learn for statistical analysis.

### 6. Results & Business Recommendation
**Business Impact:** 
- The findings helped identify several anomalies in property tax data that could indicate fraudulent activity.
- The analysis provided metrics on the extent of fraud, such as the proportion of properties with suspiciously high exemptions or discrepancies between declared and market values.

**Insights:**
- Certain boroughs showed higher instances of anomalies, particularly in areas with high property values.
- Visualizations revealed patterns of fraud, such as clusters of properties with unusually high exemptions.
- Detailed field analysis, such as lot width and depth, building class, and exemption codes, highlighted specific areas prone to fraud.

### 7. Next Steps
**Future Work:**
- Extend the analysis to include more recent data for a comprehensive temporal analysis.
- Develop a predictive model to automate fraud detection in real-time.
- Collaborate with city officials to refine the detection criteria and validate findings with on-the-ground inspections.
- Implement a system for continuous monitoring and updating of the fraud detection model as new data becomes available.

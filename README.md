# NYC-Property-Tax-Fraud-Analysis-using-Unsupervised-Learning
# Summary
The city of New York suspects property tax fraud in the properties. To address this, an algorithm is developed to analyze the data and detect potential anomalies using the NY property dataset of 32 records and about a million rows.
The focus would be identifying instances where property values don't match their corresponding characteristics, suggesting underpayment of taxes through misrepresentation. By checking these unusual or suspicious patterns in dollar values and comparing the property values with their corresponding characteristics, detects the anomalies that can be used to alert the city to potential cases of tax fraud. In the process, we used an average of metrics generated from two algorithms and ranked them in descending order to understand which property tax has a higher chance of fraud because of their strangeness. This approach can save the city significant time and resources in manually reviewing records and help to identify and prevent tax fraud.

## Data Description
Dataset Name : New York Property Valuation and Assessment Data, 
Dataset Provider: Department of Finance(DOF),
Dataset Owner: NYC OpenData,
Dataset Source: https://data.cityofnewyork.us/Housing-Development/Property-Valuation-and-Assessment-Data/rgy2-tti8
![image](https://github.com/IndiraGundavarapu01/NYC-Property-Tax-Fraud-Analysis-using-Unsupervised-Learning/assets/113149175/a2c4565d-290e-4e7f-b389-c0c7c649d1fe)

## Methodology

The methodology used in this data science project follows the following steps:

1. **Data Collection**: The dataset used in this project was obtained from the NYC OpenData website. It contains information about land and building details such as lot and building size, lot and building front, lot and building depth, land and building value etc. The data was collected over a period of one year in 2010 and comprises 1070994 samples with 32 fields.

2. **Data Exploration and Preprocessing**: Exploratory data analysis was conducted to gain insights into the dataset. Visualizations and summary statistics were used to understand the distribution of variables and identify potential patterns or correlations. Data cleaning techniques such as Exclusions and Imputation were applied to handle missing values and outliers, ensuring the dataset's quality for further analysis.

3. **Feature Selection and Engineering**: Feature selection techniques, such as Principal Component Analysis and domain knowledge, were utilized to identify the most relevant variables for the analysis. Additionally, feature engineering was performed to create new variables, such as land area, building area and total acreage.

4. **Algorithm Building**: Two anomaly detection algorithms were used : 1. Minkowski Distance 2. Autoencoder. Scores generated from these are zscaled, averaged and sorted to get the final score.  

5. **Results Interpretation**: The sorted records are the records with high to low strangeness based on the scores.This shows which variables have unusual values. In order to aid with the search of understanding the variables, a heatmap is generated which shows which variables are too large or too small individually and also for the groupings of TAXCLASS and ZIPCODE. The unusual cases are then studied individually and to understand which of the records need further investigation.

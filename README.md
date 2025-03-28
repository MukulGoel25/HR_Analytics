# HR_Analytics

**Overview**

This project performs HR analytics using a dataset containing employee information. The analysis includes data cleaning, exploratory data analysis (EDA), and visualization of salary distributions, department compositions, and gender-based salary comparisons.

**Dataset**

The dataset used in this analysis is HRDataset_v14.csv, which includes attributes such as:

Employee demographics (Sex, Department, etc.)

Salary details

Other HR-related metrics

**Libraries Used**

The following Python libraries were used in this project:

Pandas

NumPy

Matplotlib

Seaborn


**Data Processing**


**Steps performed:**

Data Loading: Read the dataset into a Pandas DataFrame.


**Data Cleaning:**

Checking for missing values and filling them with appropriate values.

Identifying and removing duplicate records.

Standardizing column values (e.g., correcting inconsistent department and gender entries).


**Exploratory Data Analysis (EDA):**

Identifying top 10 highest and lowest salary earners.

Conducted Multivariable analysis and developed 10+ visualizations.

Visualizing salary distributions using bar charts.

Identifying salary outliers in each department using box plots.

Analyzing salary distribution by gender.

Comparing the number of male and female employees across departments.

Several charts and plots are generated to analyze HR trends:

Bar charts: Compare the highest and lowest salaries.

Box plots: Identify salary outliers in different departments.

Stacked bar plots: Compare male and female distribution across departments.


**How to Run the Project**

**Clone the repository:**

git clone https://github.com/MukulGoel25/HR-Analytics.git
cd HR-Analytics



**Install the required libraries:**

pip install pandas numpy matplotlib seaborn

Run the Jupyter Notebook:

jupyter notebook HR_Analytics.ipynb

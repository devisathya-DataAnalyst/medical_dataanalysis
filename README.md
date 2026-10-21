🏥 Medical Database Analysis Using Excel
📌 Project Overview

This project focuses on Medical Database Analysis using Microsoft Excel to explore health-related data, identify patterns, and analyze relationships between medical indicators and a progression score.

The dataset includes Body Mass Index (BMI), blood pressure, glucose, insulin, cholesterol, physical activity, and progression score. Excel tools such as formulas, sorting, filtering, charts, PivotTables, and conditional formatting can be used to summarize and visualize the data.

🎯 Project Objectives
Analyze health-related indicators using Microsoft Excel.
Identify patterns and trends in the medical dataset.
Examine relationships between health variables and progression scores.
Create charts and dashboards for data visualization.
Summarize findings to support exploratory data analysis.
🛠️ Tools and Technologies
Microsoft Excel
Excel formulas and functions
PivotTables and PivotCharts
Conditional Formatting
Data Cleaning and Validation
Charts and Interactive Dashboards
📊 Dataset Description

The dataset contains the following columns:

Column Name	Description
BMI	Body Mass Index
Blood_Pressure	Blood pressure measurement
Glucose	Glucose measurement
Insulin	Insulin measurement
Cholesterol	Cholesterol measurement
Physical_Activity	Physical activity value
Progression_Score	Numerical outcome or progression measure

Note: The measurement units, physical activity scale, and definition of Progression_Score should be documented before drawing medical conclusions.

📋 Sample Dataset
BMI	Blood_Pressure	Glucose	Insulin	Cholesterol	Physical_Activity	Progression_Score
40.6744	134	77	174	200	10	73.8242
38.3915	66	160	83	276	0	80.2207
23.9364	133	156	46	203	10	63.8982

The table above shows three sample records from the dataset.

🔍 Data Analysis Process
1. Data Cleaning
Check for missing values and duplicate records.
Identify invalid or inconsistent values.
Ensure that numerical columns use the correct data types.
Verify measurement units and column definitions.
2. Exploratory Data Analysis
Calculate the mean, median, minimum, and maximum of each numerical column.
Examine the distribution of BMI, glucose, insulin, and cholesterol.
Compare progression scores across different data ranges.
Identify potential outliers for further investigation.
3. Excel Functions Used
Function	Purpose
AVERAGE()	Calculate the average value
MEDIAN()	Calculate the median
MIN()	Find the minimum value
MAX()	Find the maximum value
COUNT()	Count numerical entries
COUNTBLANK()	Identify missing entries
CORREL()	Examine linear correlation between two variables
STDEV.S()	Calculate sample standard deviation
IF()	Apply conditional logic
4. Data Visualization

Create the following charts in Excel:

Scatter Plot: Explore the relationship between BMI and Progression_Score.
Column Chart: Compare average progression scores across groups.
Histogram: Examine the distribution of BMI or glucose values.
Correlation Heatmap: Visualize correlations between numerical variables.
Dashboard: Display key statistics and charts in one interactive worksheet.
📈 Key Questions to Explore
What are the average BMI, glucose, insulin, and cholesterol values?
How much variation exists in the progression score?
Are BMI and Progression_Score linearly correlated?
Which variables have the strongest correlations with Progression_Score?
Are there unusual or missing values that require further review?
What patterns can be observed in the available health indicators?
📊 Expected Outcomes
A cleaned and organized medical dataset.
Descriptive statistical summaries.
Visual representations of health-related variables.
Correlation analysis between numerical features.
An Excel dashboard summarizing the main findings.

Actual findings should be reported after analyzing the complete dataset; they should not be inferred from the three sample records alone.

📁 Project Structure
Medical-Database-Analysis/
│
├── README.md
├── medical_data.xlsx
├── cleaned_medical_data.xlsx
└── dashboard_screenshots/
    └── medical_dashboard.png


This is a suggested folder structure. Include only the files that exist in your repository.

🚀 How to Use
Download or clone this repository.
Open medical_data.xlsx in Microsoft Excel.
Inspect and clean the dataset.
Use Excel formulas to calculate descriptive statistics.
Create PivotTables, charts, and correlation analysis.
Build a dashboard to summarize the results.
Save the final analysis and document the key findings.
🔮 Future Improvements
Add more medical records for broader analysis.
Build an interactive Excel dashboard with slicers.
Automate data cleaning using Power Query.
Compare additional variables using statistical analysis.
Extend the project using Python or SQL for larger datasets.
⚠️ Disclaimer

This project is intended for educational and exploratory data analysis purposes only. The dataset does not, by itself, establish medical diagnoses or causal relationships. Verify variable definitions, measurement units, and data quality before interpreting results.

Do not upload identifiable patient information or confidential medical records to a public repository.

👨‍💻 Author

Your Name

GitHub: @YOUR-USERNAME

⭐ If you find this project useful, consider giving the repository a star!

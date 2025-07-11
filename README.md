COVID-19-Exploratory-Data-Analysis-EDA-Project

Author:Janardhan 
Tools Used: Python (Pandas, Seaborn, Matplotlib), Power BI  
Dataset Source:[Kaggle COVID-19 Global Dataset](https://www.kaggle.com/)  
Project Type: Exploratory Data Analysis (EDA)

Project Objective
To analyze the global spread of COVID-19, identify trends, and extract meaningful insights from the dataset using Python.

Skills & Libraries Used
Python Libraries:
 - pandas – For data loading, cleaning, transformation, and grouping operations
 - numpy – For numerical operations and creating calculated fields
 - seaborn – For clean and aesthetic visualizations (line plots, boxplots, violin plots)
 - matplotlib – For plotting time-series and bar charts for comparative analysis
Data Analysis & Manipulation
 - Date parsing & conversion – Converted date strings to datetime objects using pd.to_datetime() for accurate time-based analysis
 - Grouping & aggregation – Used groupby() to analyze trends over time per country
 - Feature engineering – Created new columns like Deaths_Recovered_Total to validate data integrity
 - Outlier detection – Used boxplots and histograms to identify data anomalies or inconsistencies
 - Data validation – Checked for logical errors (e.g., Confirmed < Deaths + Recovered) and handled them appropriately


Key EDA Insights

- Detected and handled missing values and duplicates
- Identified 49,050 invalid rows, where `Confirmed < Deaths + Recovered`
- Grouped data by `Country/Region` and `Date` for daily trend analysis
- Created visualizations for:
   - Top 5 countries' trends (US, India, Brazil, Russia, South Africa)
   - India and China timeline breakdowns
   - One-day analysis (e.g., 2020-01-22)

Sample Visuals
-  Line charts of country trends  
-  Bar chart of top countries by confirmed cases  
-  Violin/Box plots for regional comparisons

Why This Project Matters
This project demonstrates my ability to:
- Clean and validate real-world datasets
- Derive insights through EDA
- Visualize patterns using Python & BI tools
- Tell a compelling data story

Connect with Me
LinkedIn - [LinkedIn](www.linkedin.com/in/janardhan-46b045259)

⭐ Feel free to fork, use, or connect with me for collaboration!



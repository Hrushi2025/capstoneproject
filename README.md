#📊 911 Calls Data Analysis — Capstone Project
This capstone project focuses on performing an exploratory data analysis (EDA) of 911 emergency calls data using Python and key data science libraries. The analysis extracts valuable insights from the dataset by visualizing emergency call reasons, time-based patterns, and geographic trends.
capstoneProject1.py — Main Python script performing the complete EDA process.
911.csv — Dataset containing records of 911 calls (must be available in the working directory).
🔍 Key Features & Analyses
Data Cleaning & Inspection
Loaded the dataset using pandas.
Checked missing values, data types, and top-level statistics.
Feature Engineering
Extracted reason for the 911 call from the title column.
Created new time-based columns: Hours, Month, Day of Week, and Date.
Visualizations (via Seaborn & Matplotlib)
Count plots for:
Emergency reasons (EMS, Traffic, Fire).
Call frequency by Day of Week and Month.
Line plots to observe:
Total call trends over time.
Traffic-specific trends over time.
Heatmaps:
Calls by Day of Week vs. Hour.
Grouping & Aggregation
Analyzed top ZIP codes and townships for call volumes.
Explored monthly and daily patterns by grouping and counting entries.
▶️ How to Run
Place 911.csv in the same directory as capstoneProject1.py.
Open a Jupyter notebook or run the script in any Python environment.
The output will display visualizations and processed data for further interpretation.
📌 Insights Gained
EMS calls are the most frequent type.
Peak hours and days for emergency calls reveal patterns that can aid resource allocation.
Visualization of calls helps spot trends and potential anomalies geographically or temporally.
✍️ Author
Hrushikesh Kanhaiya Pardeshi
Capstone Project — Data Science / Python EDA



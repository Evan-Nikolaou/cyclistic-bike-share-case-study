Google Data Analytics Capstone Project

Author: Evangelos Nikolaou
Tools: SQL, BigQuery, Python, Kaggle, Google Sheets

This project analyzes 12 months of Divvy bike-share data to understand the behavioral differences between annual members and casual riders, and provides data-driven recommendations to help Cyclistic convert more casual riders into annual members.

1. Business Question

How do annual members and casual riders use Cyclistic bikes differently?
Cyclistic aims to increase long-term revenue by converting more casual riders into annual members. Understanding usage patterns is key to designing effective marketing strategies.

2. Repository Contents
cyclistic-bike-share-case-study/
│
├── cyclistic_case_study.ipynb       # Kaggle notebook (analysis + visuals)
├── Cyclistic case study.docx        # Full written report
│
├── data/                            #  summary CSVs used in Kaggle
│   ├── rides_by_user_type.csv
│   ├── avg_ride_length_by_user_type.csv
│   ├── rides_by_weekday.csv
│   ├── avg_length_by_weekday.csv
│   ├── seasonality_monthly.csv
│   └── bike_type_usage.csv
│
├── images/                          # Visualization outputs

3. Methods & Tools Used
- Data Storage & Processing

Google BigQuery (6+ million rows)

SQL for cleaning, joining, and aggregation

-Visualization

Python (Pandas, Matplotlib)

Google Sheets (exploratory charts)

- Development

Kaggle Notebook for reproducible workflow

GitHub for version control and portfolio presentation

4. Key Findings

Members ride far more frequently, especially on weekdays -> commuter patterns
Casual riders take significantly longer trips, often 2–3× longer
Casual usage peaks on weekends -> leisure usage
Electric bikes are preferred by casual riders, while members use classic bikes
Seasonality is strong for casual riders, but members ride consistently year-round

5. Recommendations

Weekend promotion campaigns targeted at leisure riders
Highlight cost-savings on electric bikes for frequent casuals
Employer partnerships and commuter-focused membership messaging

6. Kaggle Notebook

View the complete analysis here:## 🔗 6. Kaggle Notebook  
View the complete analysis here:  
👉 [Cyclistic Kaggle Notebook](https://www.kaggle.com/code/evnikthegreek/cyclistic-bike-share-case-study-member-vs-casual)


7. Acknowledgements

This analysis uses publicly available Divvy/Cyclistic trip data provided by
Motivate International Inc.
Licensed under the Divvy Data License Agreement.

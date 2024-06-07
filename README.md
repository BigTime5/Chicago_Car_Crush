CHICAGO TRAFFIC CRASHES
README
Project Objective
The primary objective of this project is to enhance road safety by predicting the severity of motor vehicle crashes based on injury outcomes. Given the alarming increase in traffic fatalities and pedestrian deaths, our analysis and modeling aim to support ongoing safety efforts by identifying key risk factors and high-risk areas, ultimately guiding the development of effective safety interventions and policies.

Data Understanding
Overview of Dataset Columns
The dataset includes various factors influencing motor vehicle crashes, ranging from temporal and spatial dimensions to environmental and infrastructural conditions. This comprehensive view allows for a multi-faceted analysis to identify key risk factors and high-risk areas, which are essential for developing effective safety interventions and policies.

Data Processing
Step 1: Data Review
Review: Conduct a thorough examination of the existing crash dataset to identify any issues, ambiguities, inconsistencies, or areas for improvement. This includes examining the structure, content, and quality of the data.
Step 2: Continuous Improvement
Based on the data review, implement the following improvements to enhance the dataset's quality and usability:

Data Cleaning: Address missing values, duplicate records, and outliers.
Standardization: Ensure consistent formatting of data fields (e.g., date, time, location).
Data Validation: Verify data integrity and accuracy.
Data Enrichment: Add additional relevant data fields to enhance the dataset's value, if possible.
Data Normalization: Normalize data values where necessary (e.g., converting units, standardizing categorical values).
Quality Assurance: Implement data quality checks and validation rules.
Visualization and Exploratory Data Analysis (EDA)
To gain insights and answer key questions about the data, we conducted the following analyses:

Time of Day Analysis: Determine at what time of day crashes are most frequent.
Location Analysis: Identify locations with the highest number of crashes.
Weather Condition Analysis: Analyze how different weather conditions affect the frequency of crashes.
Seasonal Analysis: Examine during which months or seasons crashes occur most frequently.
Contributory Causes: Identify the primary contributory causes of crashes.
Day of Week Analysis: Analyze crash distribution across the days of the week and determine which day experiences the most crashes.
Fatality Analysis: Determine which types of crashes result in the highest fatalities.
Dangerous Contributory Causes: Identify the contributory cause posing the greatest danger.
Traffic Control Measures: Assess whether the presence of traffic control measures reduces the likelihood of crashes.
Predictive Modeling
Target Variable: Severity of Crash
We explored both binary and ternary classification models to predict the severity of crashes, using the MOST_SEVERE_INJURY column in the Crashes dataset to represent the target variable. Given the severe class imbalance, our focus was on improving recall to minimize false negatives.

Binary Classification:

Class 0: No Injury
Class 1: Injury
Ternary Classification:

Class 0: No Injury
Class 1: Non-Incapacitating Injuries
Class 2: Incapacitating or Fatal Injuries
Priority Metric: Recall
Our primary metric was recall, as the most damaging false predictions are false negatives (predicting no injury when there was actually an injury).

Recommendations and Future Work
Based on our analysis and modeling, we provide the following recommendations:

Enhance Data Collection: Improve data collection methods to capture more detailed and accurate crash information.
Implement Safety Interventions: Use the identified high-risk factors and areas to guide the implementation of targeted safety interventions.
Regular Monitoring and Updating: Continuously monitor crash data and update models to reflect the latest trends and patterns.
Public Awareness Campaigns: Conduct public awareness campaigns focusing on the identified primary contributory causes of crashes.
In the future, further analysis can explore additional predictive features and more sophisticated modeling techniques to improve prediction accuracy and support road safety initiatives more effectively.

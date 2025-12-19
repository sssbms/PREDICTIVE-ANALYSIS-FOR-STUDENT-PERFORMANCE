# PREDICTIVE-ANALYSIS-FOR-STUDENT-PERFORMANCE
This project applies the Big Data Analytics Lifecycle to predict student academic performance in Mathematics and Portuguese language subjects. Using a dataset from Kaggle, the project explores demographic, socio-economic, and behavioral factors to identify at-risk students

# Big Data Analytics Lifecycle

# 1. Business Case Evaluation

The team evaluated the strategic importance of academic forecasting. The analysis focused on how predictive modeling could improve graduation rates while addressing risks related to data privacy and algorithmic bias.

# 2. Identification of Data

Data was sourced from the Student Performance Dataset on Kaggle. The scope included two distinct datasets: Mathematics (395 records) and Portuguese Language (649 records), encompassing 33 features ranging from demographics to alcohol consumption.

# 3. Data Filtering

Data quality was ensured by removing duplicate records and applying strict range-based filters. The analysis was restricted to students aged 15–22 and validated entries for absences and grade scales (0–20).

# 4. Data Extraction

Categorical variables were converted into factor types to facilitate machine learning. New features were engineered, including pass_G3 (to indicate passing status) and alc_total (to aggregate weekday and weekend alcohol consumption).

# 5. Data Aggregation

The data was summarized by grouping students based on school, sex, and study time. An inner join was performed between the two datasets to identify and analyze students enrolled in both subjects.

# 6. Data Analysis

The team implemented the XGBoost algorithm for predictive modeling.

The Math model achieved an accuracy of 83.54%.

The Portuguese model achieved an accuracy of 90.70%.

Statistical analysis confirmed that prior grades (G1 and G2) served as the strongest predictors for final outcomes.

# 7. Visualization of Data (Dashboards)

Interactive dashboards were developed to communicate findings visually. These included:

KPI Cards: Displayed average, minimum, and maximum scores.

Behavioral Charts: Illustrated how factors like internet access and alcohol consumption affected grades.

Demographic Distributions: Mapped performance against parents' education levels and occupations.

# 8. Final Analysis Result

The project successfully transformed raw data into actionable insights. The results proved that academic history and study habits were critical indicators, enabling the institution to transition from a reactive approach to a preventive student-support model.

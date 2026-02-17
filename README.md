Airline Passenger Satisfaction Analysis
Project Overview
This project aims to analyze and predict passenger satisfaction levels for an airline using a dataset of over 100,000 passenger records. By leveraging machine learning classification techniques, the project identifies key service factors that contribute to a positive travel experience, helping airlines make data-driven decisions to improve service quality.

Dataset Description
The analysis is based on the Skynest dataset, which captures a variety of passenger metrics:
•	Target Variable: Satisfaction (Satisfied vs. Neutral/Dissatisfied).
•	Passenger Profile: Age, Gender, Customer Type, and Type of Travel.
•	Travel Details: Flight Distance, Class (Business/Eco), and Delay metrics.
•	Service Ratings: 1–5 scale ratings for features such as Inflight wifi, Seat comfort, On-board service, and Cleanliness.

Technical Stack
•	Language: Python 
•	Libraries: Pandas, Scikit-learn, NumPy, Matplotlib, Seaborn 
•	Tools: Jupyter Notebook 

Machine Learning Workflow
1.	Data Cleaning & Preprocessing: Managed missing values and performed exploratory data analysis (EDA) using Python to understand feature distributions.
2.	Feature Engineering: Encoded categorical variables and scaled numerical data for model readiness.
3.	Model Selection: Implemented and compared multiple classification models:
o	Logistic Regression: Used for baseline statistical analysis.
o	Random Forest: Utilized for its ability to handle non-linear relationships and provide feature importance.
4.	Evaluation: The Random Forest model achieved a final prediction accuracy of 87%.

Key Insights
•	Service Drivers: Identified the most critical factors influencing passenger satisfaction (e.g., Inflight Entertainment, Seat Comfort).
•	Predictive Power: The model successfully classifies passenger sentiment with high reliability, allowing for targeted service improvements.

How to Run
1.	Clone this repository.
2.	Ensure you have the required libraries installed:
Bash
pip install pandas scikit-learn matplotlib seaborn
3.	Open Airline_Satisfaction_Analysis.ipynb in Jupyter Notebook or VS Code.

EDA:
Correlation Matrix

Distribution of Passenger satisfaction
 
Visualizations of Results:
Comparison of Model Accuracy
 

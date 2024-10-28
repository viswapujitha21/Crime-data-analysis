**Overview**

This project focuses on analyzing NYPD shooting incidents data to identify trends, hotspots, and demographic patterns related to crime in New York City from 2006 to 2019. The project involved data cleaning, exploratory data analysis (EDA), and applying machine learning models to predict patterns in crime data.

**Project Objectives**

Data Cleaning: Removed duplicates, handled missing values, and prepared categorical data for analysis.

EDA: Examined trends in shooting incidents by borough, time, demographic factors, and identified high-risk neighborhoods.

Modeling: Applied machine learning algorithms to classify and predict patterns in crime, enhancing insights on crime-prone areas and peak times.

**Dataset Description**

The dataset includes information on shooting incidents, such as:

Incident details: Date, time, location (borough and precinct)

Demographics: Age, sex, race of perpetrators and victims

Geographic coordinates for mapping crime hotspots

**Hypotheses Tested**

Crime Trends: Analyzed borough-wise crime distribution and time-based patterns.

Demographics: Investigated victim and perpetrator demographics (age, sex, race) to identify high-risk groups.

Time Analysis: Identified peak hours and days for shootings.

Location Analysis: Mapped precincts with high crime rates and identified dangerous locations in NYC.

**Models and Outcomes**

We implemented various machine learning models to analyze and predict crime patterns:

Logistic Regression: Achieved 62% accuracy in predicting perpetrator demographics based on incident details.

Random Forest: Used to predict neighborhood safety, achieving 78% accuracy with AUC 0.86.

Decision Tree Classifier: Classified perpetrator age groups with an 80% accuracy and AUC 0.87.

K-Nearest Neighbors (KNN): Classified crime-prone locations with 88% accuracy and AUC 0.97.

K-Means Clustering: Grouped crime hotspots, identifying prime locations for increased policing efforts.

**Key Findings**

High Crime Locations: Brooklyn recorded the most shootings, with peak incidents during late nights and weekends.

Demographic Patterns: Black males were the most common victims and perpetrators across boroughs.

Temporal Trends: Crime rates were higher from 9 PM to 5 AM, with spikes on weekends.

Annual Trends: Significant decreases in shootings were observed post-2012.

**Tools Used**

Data Processing: Python, Jupyter Notebooks, Pandas

Visualization: Matplotlib, Seaborn

Machine Learning: Scikit-learn for model training and evaluation

**Conclusion**

This analysis provides valuable insights into crime patterns in NYC, including vulnerable areas and demographic trends. These findings can assist law enforcement in focusing resources on high-risk areas and peak times, ultimately helping to enhance public safety in New York City.

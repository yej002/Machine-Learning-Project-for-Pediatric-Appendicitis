# Machine Learning Project for Pediatric Appendicitis
Dataset: https://archive.ics.uci.edu/dataset/938/regensburg+pediatric+appendicitis

### Intro:
The Regensburg Pediatric Appendicitis dataset was collected at Children's Hospital St. Hedwig in Regensburg, Germany, from 2016 to 2021, involving pediatric patients suspected of appendicitis. The data, which includes ultrasound images and tabular data such as laboratory tests, physical examinations, and expert ultrasonographic findings, were manually extracted and encompass three target variables: diagnosis, management, and severity. To use this dataset, one would need to access it via the UCI Machine Learning Repository, possibly requiring data cleaning steps such as handling missing values and standardizing formats for analysis (UCI Machine Learning Repository).

### Goal:
The goal of this assignment is to apply the knowledge of machine learning that I have acquired from the course CS5100 Fundamentals of Artificial Intelligence on a real-world dataset. 

### Outcome:
In Jupiter Notebook, I demonstrated my learnings in the following:
- Data Exploring & Data Cleaning
  - define my own imputation rules for missing data
  - define preprocessor to clean and process the data for the machine learning models
- Model Training & Cross-Validation Testing
  - models include Random Forest, Decision Tree, K Nearest Neighbors, Support Vector Machines
- Multiple Learning Models Comparison
  - a comparison of training accuracy and validation accuracy between models
- Tuning & Extraction
  - applied hyperparameter tuning on the Random Forest model
- Visualizations
  - a bar chart for model performance comparison
  - a bar chart for the top 10 important features in pediatric appendicitis prediction
  - a pie chart for the top 5 important features in pediatric appendicitis prediction

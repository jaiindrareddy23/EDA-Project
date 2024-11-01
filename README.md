# EDA-Project
Exploratory and Predictive Analysis of Traffic Violations in the USA Using Python and Spark
Project Overview
This project delves into the exploratory data analysis (EDA) and predictive analysis of traffic violations across the United States. Using PySpark for handling and processing large datasets, the project aims to uncover patterns and trends in traffic violations, and build predictive models to forecast future violations based on key variables such as time, location, driver demographics, and infraction type. By combining data analysis and machine learning techniques, the project provides insights that could help in understanding and potentially reducing traffic violations.

Goals
Exploratory Data Analysis (EDA):

Visualize and explore data trends across regions, time frames, and violation types.
Identify correlations between factors like driver demographics, vehicle information, and violation categories.
Highlight temporal patterns (such as peak violation times or seasonal trends).
Predictive Modeling:

Use classification and regression models to predict the likelihood and type of future violations.
Test model accuracy and evaluate performance metrics such as precision, recall, and F1 score.
Technologies Used
Python & PySpark: Data preprocessing, manipulation, and analysis.
Pandas: For data cleaning and initial data exploration.
Matplotlib & Seaborn: Visualization of data insights.
Machine Learning Libraries (Scikit-Learn, PySpark MLlib): Building, training, and evaluating predictive models.
Data Source
The dataset used contains records of traffic violations from various regions in the United States. The data includes attributes like date, time, driver information, vehicle details, and the type of infraction.

Key Features
Data Cleaning: Handling missing values, feature engineering, and preprocessing for Spark compatibility.
Visualization: Detailed graphs and charts to display insights on traffic violations.
Model Training: Predictive models like Decision Trees, Logistic Regression, and Random Forests to analyze violation patterns.
Model Evaluation: Assessing model performance and optimizing for better predictions.
Project Structure
data/: Contains sample data or links to the data source.
notebooks/: Jupyter notebooks with step-by-step EDA and model development.
src/: Python scripts for data processing, model building, and evaluation.
README.md: Overview, setup instructions, and project details.

How to Run:
Install Dependencies: Ensure Python, Spark, and all libraries in requirements.txt are installed.
Data Preparation: Download the dataset and place it in the data/ folder.
Run Notebooks: Start with EDA, then proceed to model building and prediction.

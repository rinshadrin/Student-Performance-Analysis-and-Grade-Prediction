# Student Performance Analysis and Grade Prediction

## Project Overview

This project analyzes student academic performance using data science and machine learning techniques. The goal is to identify factors that influence student grades and build predictive models to classify or predict student performance.

The project includes data cleaning, exploratory data analysis, feature engineering, visualization, and machine learning model development.

## Dataset

Dataset: student_performance.csv

The dataset contains various academic, behavioral, and demographic factors affecting student performance.

### Features

* StudyHours
* Attendance
* Resources
* Extracurricular
* Motivation
* Internet
* Gender
* Age
* LearningStyle
* OnlineCourses
* Discussions
* AssignmentCompletion
* EduTech
* StressLevel
* FinalGrade

## Objectives

* Analyze factors affecting academic performance
* Explore relationships between student attributes and grades
* Identify important performance indicators
* Build machine learning models for prediction
* Generate educational insights through data analysis

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Jupyter Notebook

## Project Workflow

### Data Collection

* Imported student performance dataset
* Examined dataset structure and attributes

### Data Cleaning

* Checked missing values
* Removed duplicates
* Handled inconsistent data
* Encoded categorical variables

### Exploratory Data Analysis

* Student performance distribution
* Attendance analysis
* Study habits analysis
* Stress level analysis
* Learning style comparison
* Correlation analysis

### Data Visualization

* Histograms
* Count Plots
* Bar Charts
* Pie Charts
* Correlation Heatmaps
* Box Plots

### Machine Learning Models

* Logistic Regression
* Random Forest Classifier
* XGBoost Classifier

### Model Evaluation

* Accuracy Score
* Classification Metrics
* Confusion Matrix
* Feature Importance Analysis

## Key Findings

* Attendance significantly impacts academic performance.
* Assignment completion contributes to higher grades.
* Motivation levels influence student success.
* Stress levels affect overall performance.
* Random Forest achieved strong predictive performance.

## Project Structure

Student-Performance-Analysis/

├── studence perfomance.ipynb

├── student_performance.csv

├── README.md

## How to Run

### Clone Repository

git clone https://github.com/rinshadrin/Student-Performance-Analysis.git

### Move to Project Directory

cd Student-Performance-Analysis

### Install Dependencies

pip install pandas numpy matplotlib seaborn scikit-learn xgboost

### Launch Jupyter Notebook

jupyter notebook

### Open Notebook

studence perfomance.ipynb

## Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 28.43%   |
| Random Forest       | 90.34%   |
| XGBoost             | 85.85%   |

## Business and Educational Applications

* Student Performance Monitoring
* Early Risk Detection
* Academic Planning
* Educational Decision Support
* Personalized Learning Strategies

## Future Improvements

* Deep Learning Models
* Student Recommendation System
* Real Time Academic Dashboard
* Automated Performance Monitoring

## Author

Muhammed Rinshad

Data Science & AI Graduate

GitHub: https://github.com/rinshadrin

LinkedIn: https://www.linkedin.com/in/muhammed-rinshad

## License

This project is created for educational, academic, and portfolio purposes.

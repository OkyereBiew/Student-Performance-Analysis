# 📊 Student Performance Data Analysis (Beginner Project)

## 📁 Dataset Overview
This project uses a dataset containing academic performance records of 1,000 students. The data includes:
  **Source:** [https://www.kaggle.com/datasets/sonukumari47/students-performance-in-exams]
- **Math, Reading, and Writing scores**
- **Gender**
- **Parental level of education**
- **Lunch type**
- **Test preparation course**

## 🎯 Objective
To explore how student performance varies based on demographic and educational support factors such as:
- Gender
- Parental education level
- Lunch type
- Completion of test preparation course

## 🧰 Tools & Libraries
- `pandas` for data manipulation
- `matplotlib.pyplot` and `seaborn` for data visualization

## 📊 Analysis Workflow

### 1. Data Loading & Cleaning
- Loaded the dataset using `pandas`
- Checked for null values and data types

### 2. Exploratory Data Analysis (EDA)
- **Distribution Analysis**:
  - Histograms of math, reading, and writing scores
- **Gender Comparison**:
  - Compared mean scores for males and females across all subjects
- **Parental Education**:
  - Analyzed average student scores based on parents' education level
- **Lunch Type**:
  - Compared performance between students with standard vs. free/reduced lunch
- **Test Preparation**:
  - Assessed how completing a test preparation course impacts scores

### 3. Feature Engineering
- Created a new column: `average_score` = mean of math, reading, and writing scores

### 4. Visualizations
- Count plots for categorical variables
- Bar plots for average scores across different groups
- Boxplots to show score distributions by gender and parental education

## ✅ Key Findings
- **Gender Patterns**: 
  - Males score higher in math; females outperform in reading and writing
- **Test Preparation Works**: 
  - Students who completed a test prep course scored higher on average
- **Parental Education Matters**: 
  - Higher parental education is linked to better student performance
- **Lunch Type Effect**: 
  - Standard lunch students scored better than those on free/reduced lunch

## 📌 Conclusion
This beginner-friendly data analysis project demonstrates how demographic and support variables affect student performance. It offers hands-on experience with real-world data and fundamental analysis techniques in Python.

## 📁 File Structure

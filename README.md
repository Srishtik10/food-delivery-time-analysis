# Food Delivery Time Analysis

## Project Overview

This project analyzes food delivery data to understand the factors that influence delivery time. The project includes exploratory data analysis, statistical analysis, data preprocessing, visualization, and a Logistic Regression model for classifying delivery times.

## Dataset

The dataset contains 1,000 food delivery records with the following attributes:

- Order ID
- Distance (km)
- Weather
- Traffic Level
- Time of Day
- Vehicle Type
- Preparation Time (min)
- Courier Experience (years)
- Delivery Time (min)

## Project Workflow

### 1. Import Libraries
Imported the required Python libraries for data analysis, visualization, statistical analysis, preprocessing, and machine learning.

### 2. Load Dataset
Loaded the Food Delivery Times dataset using Pandas.

### 3. Basic Dataset Inspection
Performed initial inspection using:
- Dataset shape
- First and last records
- Dataset information
- Descriptive statistics

### 4. Data Cleaning & Missing Values
Identified missing values and examined the data for further preprocessing.

### 5. Categorical Variables & Unique Values
Explored the unique values of:
- Weather
- Traffic Level
- Time of Day
- Vehicle Type

### 6. Univariate Analysis
Analyzed individual variables using visualizations such as histograms and distribution plots.

### 7. Outlier Detection & Removal
Used:
- Z-score method
- IQR method

to identify and analyze potential outliers in delivery time.

### 8. Skewness, Kurtosis & Distribution Analysis
Analyzed the distribution of delivery time using skewness, kurtosis, KDE plots, and distribution visualization.

### 9. Numeric Feature Analysis
Analyzed numeric variables such as:
- Distance
- Preparation Time

using statistical summaries and visualizations.

### 10. Bivariate Analysis
Examined relationships between variables, including:
- Distance and Delivery Time
- Preparation Time and Delivery Time
- Traffic Level and Time of Day
- Vehicle Type and Weather

Pearson correlation and Chi-square analysis were also used where appropriate.

### 11. Categorical Encoding
Converted categorical variables into numerical features using one-hot encoding.

### 12. Feature Scaling
Applied Min-Max scaling to selected numerical features.

### 13. Defining Features and Target
Defined the independent variables and delivery time as the target variable.

### 14. Train-Test Split
Split the dataset into training and testing sets using an 80:20 ratio.

### 15. Binary Classification Setup
Converted delivery time into a binary classification problem based on the median delivery time.

- 0 → Delivery time at or below the median
- 1 → Delivery time above the median

### 16. Logistic Regression
Applied Logistic Regression to classify food delivery times into the two categories and evaluated the model using test accuracy.
Acuuracy is 0.94

## Dashboard

A dashboard was also created to visualize key insights from the food delivery dataset.

The dashboard focuses on understanding delivery performance and the factors affecting delivery time.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Tableau

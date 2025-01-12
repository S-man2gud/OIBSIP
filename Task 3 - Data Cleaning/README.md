# Task 3 - Data Cleaning: NYC Airbnb Dataset 🏠
## Project Description
This project focuses on cleaning and preparing the NYC Airbnb 2019 dataset for analysis. The dataset contains listings with features such as price, room_type, neighbourhood, and reviews. Data cleaning is an essential step to ensure accuracy, reliability, and meaningful insights.

By addressing common data quality issues like missing values, duplicates, and outliers, this project demonstrates the steps needed to prepare raw data for effective analysis or machine learning applications.

## Key Steps in Data Cleaning
### 1. Handling Missing Values
- Problem: Missing entries in columns like name, host_name, reviews_per_month, and last_review.
- Solution:
  - Filled missing name and host_name with "Unknown."
  - Replaced missing reviews_per_month with 0.
  - Converted last_review to datetime format, retaining missing entries as NaT.
### 2. Removing Duplicate Rows
- Problem: Duplicate rows distort analysis by repeating data points.
- Solution: Identified and removed duplicate rows.
### 3. Outlier Removal
- Problem: Extreme values in price (e.g., $10,000) and minimum_nights (e.g., 1,000 days).
- Solution:
  - Removed rows where price > 1000.
  - Removed rows where minimum_nights >= 365.
### 4. Standardizing Text Data
- Problem: Inconsistent formatting in categorical columns (e.g., mixed casing, extra spaces).
- Solution: Converted text to lowercase and stripped extra spaces in columns like name, host_name, and neighbourhood.
### 5. Dropping Unnecessary Columns
- Problem: Redundant columns like id.
- Solution: Dropped the id column to simplify the dataset.

## Tools and Libraries
- Python: Used for data cleaning.
- Pandas: Core library for data manipulation.
- Matplotlib/Seaborn: For data visualization during exploratory analysis.

## How to Use
1. Clone this repository:
git clone https://github.com/your-username/nyc-airbnb-data-cleaning.git

2. Navigate to the project directory:
cd nyc-airbnb-data-cleaning

3. Install necessary Python libraries:
pip install pandas

4. Run the cleaning script:
python clean_data.py

5. The cleaned dataset will be saved as Cleaned_AB_NYC_2019.csv in the project directory.

## Project Outcomes
- Reduced missing values and improved data completeness.
- Removed duplicates and outliers, ensuring data integrity.
- Standardized text data for consistency.
- Created a clean, analysis-ready dataset.

## Future Work
- Perform exploratory data analysis (EDA) to uncover insights.
- Use the cleaned dataset for machine learning or visualization projects.

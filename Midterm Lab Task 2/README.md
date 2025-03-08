# Midterm Lab Task 2 - Data Cleaning and Preparation using Power Query
This portfolio contains the steps I followed for cleaning, transforming, and reshaping job posting data using Power Query Editor in Excel.

# Part 1: Data Cleaning and Transformation Steps

## 1. Data Import and Initial Cleaning
- Loading the Data: The raw data is loaded from a CSV file.
- Cleaning Salary Estimate: We remove unwanted characters from the Salary Estimate column (text after the opening parenthesis) to clean the data.
- Creating Min and Max Salary Columns: Using the extracted salary values, two new columns Min Sal and Max Sal are created to represent the salary range for each job.

## 2. Role Classification
- Grouping Job Titles: A new column called "Role Type" is created to classify the job titles into five categories:
- Data Scientist
- Data Analyst
- Data Engineer
- Machine Learning Engineer
- Other (for non-classifiable roles)

## 3. Location Data Cleanup
- Standardizing Locations: Custom formulas are used to standardize location names and abbreviations. For example, "New Jersey" is replaced with ", NJ", "California" with ", CA", and so on.
- Splitting Location: The location column is split into two parts: one for the location and another for the state abbreviation.

## 4. Handling Negative Values
- Cleaning Negative Values: We remove or filter out invalid negative values from columns like Competitors, Revenue, and Industry.

## 5. Handling Company Size
- Splitting Company Size: The Size column is split into two parts: MinCompanySize and MaxCompanySize.

## 6. Final Cleanup
- Cleaning Company Names: We remove the word "Rates" from company names.
- Removing Unnecessary Columns: Any non-useful columns (like description columns) are removed.

## Screenshots

- Before Cleaning

![image alt](https://github.com/CarlosA012/EDM-Portfolio/blob/5528199dcd6c8022b6bd97167e4a797b7e081f6f/Midterm%20Lab%20Task%202/images/raw%20data.png)

- After Cleaning

![image alt](https://github.com/CarlosA012/EDM-Portfolio/blob/50d70db1f0974bb826213bbf4b78e7f66858d6c0/Midterm%20Lab%20Task%202/images/Unclean%20DS%20Jobs.png)

![image alt](https://github.com/CarlosA012/EDM-Portfolio/blob/5a4647d1557285a89768a75115f450f32e3dadd1/Midterm%20Lab%20Task%202/images/Unclean%20DS%20Jobs%202.png)

![image alt]()

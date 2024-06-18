## Project Part 2: Inspect and Analyze Data

### Overview

The end-of-course project in Course 2 focuses on understanding the data needed for the project. Following the project proposal developed in Course 1, this phase involves analyzing the data provided by the New York City Taxi and Limousine Commission (TLC).

### Objectives

1. Ensure the dataset is ready to answer questions and yield insights.
2. Prepare the data for visualizations.
3. Ready the data for future hypothesis testing and statistical methods.

### Steps and Tasks

#### Part 1: Understand the Situation

- **Task:** Prepare to understand and organize the provided taxi cab dataset and information.
- **Approach:** Utilize knowledge from senior team members and domain experts to gain a comprehensive understanding of the data.

#### Part 2: Understand the Data

- **Task 2a:** Build DataFrame
  - **Description:** Create a pandas DataFrame for data learning, exploratory data analysis (EDA), and statistical activities.
  - **Steps:**
    1. Import necessary libraries (`pandas`, `numpy`).
    2. Load the dataset into a DataFrame.

- **Task 2b:** Inspect the Data
  - **Description:** Examine summary information about the DataFrame.
  - **Steps:**
    1. View the first 10 rows of the DataFrame.
    2. Use `.info()` to check column data types and identify potential null values.
    3. Use `.describe()` to view statistical information about the numeric columns.
  - **Questions:**
    1. What do you notice about the different variables from the `.info()` output?
    2. What stands out in the distributions of each variable from the `.describe()` output?

- **Task 2c:** Investigate the Variables
  - **Description:** Sort and interpret data for specific variables (`trip_distance` and `total_amount`).
  - **Steps:**
    1. Sort `trip_distance` from maximum to minimum and check if the values seem normal.
    2. Sort `total_amount` and identify any unusual values.
    3. Compare the resulting rows for both sorts.
  - **Questions:**
    1. Do the sorted values for `trip_distance` seem normal?
    2. Are there any unusual values in `total_amount`?
    3. Are the resulting rows similar for both sorts? Why or why not?

#### Part 3: Understand the Variables

- **Task:** Use insights from the summary data to guide deeper investigation into specific variables.

### Summary of Findings

- **Data Types:** The dataset includes numeric, string, and timestamp objects.
- **Null Values:** Initial inspection shows no null values, but further investigation may be needed to verify.
- **Outliers and Anomalies:**
  - Some `trip_distance` values are zero despite having assigned fares.
  - Unusually high `total_amount` values (e.g., $1200).
  - Negative values in `fare_amount`, `extra`, `mta_tax`, and `improvement_surcharge`.

### Conclusion

This part of the project focused on preparing and inspecting the dataset to ensure it is ready for analysis. The next steps involve a deeper investigation of specific variables and preparation for visualizations and statistical testing.


### Executive Summary:
![Executive Summary](Course%202%20Automatidata%20Executive%20Summary.png)

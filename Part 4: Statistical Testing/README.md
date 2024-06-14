## Project Part 4: Statistical Testing

### Overview

In Course 4, the focus is on applying statistical methods to analyze data, with the goal of uncovering insights and making data-driven decisions. This project involves conducting statistical testing to determine the relationship between taxi fare amounts and payment types for the New York City Taxi & Limousine Commission (TLC).

### Objectives

- Analyze the relationship between fare amount and payment type.
- Conduct an A/B test to determine if the payment method affects the fare amount.
- Apply descriptive statistics and hypothesis testing to derive insights.

### Project Tasks

#### Part 1: Imports and Data Loading

- **Objective:** Prepare the dataset for analysis.
- **Tasks:**
  - Import necessary libraries (e.g., `pandas`, `numpy`, `scipy`).
  - Load the dataset into a DataFrame for further analysis.

#### Part 2: Exploratory Data Analysis (EDA) and Hypothesis Testing

- **Objective:** Use descriptive statistics and visualizations to understand the dataset.
- **Tasks:**
  - Compute descriptive statistics to summarize the data.
  - Formulate null and alternative hypotheses.
  - Conduct an A/B test to compare fare amounts between different payment types.

#### Part 3: Communicate Insights with Stakeholders

- **Objective:** Present findings and business insights derived from the data analysis.
- **Tasks:**
  - Summarize key insights from the A/B test.
  - Provide business recommendations based on the analysis results.

### Key Insights and Recommendations

- **Business Insight:** Customers paying by credit card tend to have higher fare amounts compared to those paying by cash.
- **Recommendation:** Encourage the use of credit card payments to potentially increase revenue for taxi drivers.

### PACE Framework

The project follows the PACE (Plan, Analyze, Construct, Execute) framework to ensure a structured approach to problem-solving.

#### Plan

- **Research Question:** Is there a significant difference in fare amounts between credit card and cash payments?
- **Hypotheses:**
  - Null Hypothesis (H0): There is no difference in the average fare amount between credit card and cash payments.
  - Alternative Hypothesis (HA): There is a difference in the average fare amount between credit card and cash payments.

#### Analyze and Construct

- **Data Exploration:** Use descriptive statistics to understand the distribution of fare amounts and payment types.
- **Hypothesis Testing:** Conduct a two-sample t-test to compare fare amounts between credit card and cash payments.

#### Execute

- **Communicate Insights:** Present the results of the hypothesis test and provide actionable business recommendations.

### Conclusion

The statistical analysis demonstrated a significant difference in fare amounts between credit card and cash payments, suggesting that payment type impacts fare amount. Based on this finding, encouraging credit card payments could be a strategic approach to increase revenue for taxi drivers.

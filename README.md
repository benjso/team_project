# Team Project: Data Science and Machine Learning Foundations Certificate
This project is a collaborative effort for the Data Science and Machine Learning Foundations certificate program. Our team explored the landscape of data developer salaries and employment attributes using the 2024 data developer salaries dataset.

## Project Approach

### Project Setup:

We established a project repository on GitHub "https://github.com/benjso/team_project" with a connected project plan. "https://github.com/users/benjso/projects/1"
We used the project board to organize tasks and assign them to team members.

### Data Exploration:

Each team member proposed potential datasets.

We initially explored datasets using Excel. For larger datasets, we employed Python code to extract the first 1,000 rows for preliminary analysis. Raw data can be found in the data/raw folder.

### Data Selection and Acquisition:

We chose the 2024 data developer salaries dataset due to its rich information on job titles, experience levels, salaries, and more.

This dataset allows exploration of salary trends, employment patterns, and geographical variations in data developer roles.

### Data Cleaning and Enrichment:

We addressed the large number of job titles (155) by creating functional and seniority categories for data grouping.

To investigate the impact of location on salaries, a new column was added to indicate whether employee and company locations matched.

Many countries were present, so we grouped them into regions for better analysis.

Python code was implemented to remove 1% of outliers within the data.

Processed data resides in the data/processed folder.

The processed data was also exported to an SQL file (data/processed.sql) for future use and readability.

### Model Building and Analysis:

We employed the sm.OLS method to explore the relationship between salary and various predictors.

We rejected the null hypothesis, confirming a relationship between salary (USD) and the predictors.

Focusing on key relationships, we identified experience level and data year as highly correlated with salary. These variables were chosen for model building.

Four separate linear regression models were created for each distinct experience level. Charts were generated to compare mean salary differences between 2023 and 2024.

We limited our analysis to 2023 and 2024 data due to the scarcity of data points in previous years (2020-2022).

## Team Rules of Engagement

* Maintain clear communication and collaboration throughout the project.
* Divide tasks fairly and ensure timely completion.
* Utilize version control (Git) effectively to track changes and maintain code history.
* Conduct code reviews to ensure quality and maintainability.
* Respect deadlines and milestones set for the project.

This README provides an overview of our project's approach, data handling, and initial analysis. Further details and code can be found within the repository.
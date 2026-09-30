# IBM-Data-Analyst-Capstone
Capstone project for IBM's Data Analyst Professional Course with Coursera
# Data Visualization with Python

Completed as the final project of IBM's Data Analyst Professional Certificate on Coursera, this project simulates a real-world analytics engagement for a global IT and business consulting firm. As a Data Analyst, I analyzed data from multiple sources to identify emerging technology tends, in-demand technical skills, and evolving workforce needs. The project involved data collection, data cleaning, exploratory and statistical analysis, visualization, and insight generation to support data-driven workforce planning, hiring, and future skill development. 

### Task 1

The first task focuses on collecting data on in-demand technology skills from job postings, blogs, and developer surveys using web scraping and APIs. Data from CSV files, Excel spreadsheets, and databases is integrated into a unified dataset for analysis and visualization. 

### Task 2

Once we've collected enough data we will take the collected data and prepare it for analysis by using data wrangling techniques like finding duplicates, removing duplicates, finding missing values, and inputting missing values.

In the second task of this project, following data collection, the datasets are transformed and prepared for analysis through a structured data-wrangling and preprocessing workflow. This includes identifying and removing duplicate records, detecting and evaluating missing values, and applying appropriate imputation techniques to address incomplete data. 

The second task focuses on preparing the collected data for analysis through data wrangling, including removing duplicates, identifying missing values, and applying appropriate imputation techniques. 

### Task 3

Now that the data is ready we will apply statistical techniques to analyze the data and identify insights and trends like: What are the top programming languages that are in demand? What are the top database skills that are in demand? What are the most popular IDEs? And Demographic data like gender and age distribution of developers.

With the data cleaned and prepared, the next phase applies statistical analysis and exploratory data analysis (EDA) to uncover meaningful patterns, trends, and relationships within the dataset. The analysis examines key aspects of the technology landscape, including the most in-demand programming languages, database technologies, and development environments (IDEs). It also explores developer demographics, such as age and gender distributions, to provide additional context around the workforce represented in the data. These findings help transform raw datasets into actionable insights that can inform technology trends and workforce skill requirements. 

### Task 4

In the fourth task, we'll focus on choosing appropriate visualizations based on the data we want to present using charts, plots, and histograms to help reveal our findings and trends. We are going to access the Data from an SQL database and pull only the data we need into Dataframes.

In the fourth phase, SQL queries are used to extract and aggregate relevant data from a database, which is then loaded into Python DataFrames for analysis. Appropriate charts, plots, and histograms are created to visualize key trends, distributions, and relationships, transforming analytical results into clear, data-driven insights.

### Task 5

For task 5, we will employ Cognos/Google Looker Studio to create interactive dashboards to help analyze and present the data dynamically.

In the fifth phase, IBM Cognos Google Looker Studio are  used to develop interactive dashboards that enable dynamic data exploration and communicate key findings through intuitive, stakeholder-focused visualizations.

### Task 6

For the final task, we will use our storytelling skills to provide a narrative and present the findings of our analysis.

in the final phase, data storytelling are used to translate analytical findings into a clear, compelling narrative. Key insights and trends are presented in a structured format to communicate results effectively and support data-driven decision-making.

## Data Description

Stack Overflow, a popular website for developers, conducted an online survey of software professionals across the world. The survey data was later open sourced by Stack Overflow. The actual data set has around 90,000 responses. 
The dataset we are going to use comes from the following source: https://stackoverflow.blog/2019/04/09/the-2019-stack-overflow-developer-survey-results-are-in/ under a ODbL: Open Database License. We will be given a subset of the original data set in this capstone project. We will explore, analyze, and visualize this dataset and present our analysis.
Note: This randomized subset contains around 1/10th of the original data set. Any conclusions we draw after analyzing this subset may not reflect the real world scenario.

This project uses data from Stack Overflow's 2019 Developer Survey, a global survey of software professionals that collected approximately 90,000 responses. The dataset was open-sourced by Stack Overflow under the Odbl (Open Database License).

For this capstone, we work with a randomized subset containing approximately 10% of the original dataset. The data is explored, cleaned, analyzed, and visualized to identify trends in developer technologies, skills and demographics.

Dataset Source: [`Stack Overflow 2019 Developer Survey Results`](https://stackoverflow.blog/2019/04/09/the-2019-stack-overflow-developer-survey-results-are-in/)

Dataset Limitation: Because this project uses a randomized subset of the full survey data, findings may not represent the broader developer population or real-world technology trends. 

## Tools
- Python:
- Pandas: for data management
- Numpy: for mathematical operations
- seaborn: for data visualization
- matplotlib: additional plotting tool
- folium: for geospatial data visualization such as choropleth maps or heat maps
- plotly: interactive plotting tool
- Google Looker Studio: for dashboards
- IBM Cognos Analytics: for dashboards

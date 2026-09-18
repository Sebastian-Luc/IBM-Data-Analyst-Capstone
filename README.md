# IBM-Data-Analyst-Capstone
Capstone project for IBM's Data Analyst Professional Course with Coursera
# Data Visualization with Python
This is the Capstone Project for Course 9, _IBM Data Analyst Capstone Project_. Part of IBM's Data Analyst Professional Certificate from Coursera. We will take on the role of a Data Analyst with a global IT and Business services firm. In this role, we will be analyzing several datasets to help identify trends for emerging technologies. We have recently been hired as a Data Analyst by a global IT and business consulting services firm that is known for its expertise in IT solutions and its team of highly experienced IT consultants. To keep pace with changing technologies and reman competitive, our organization regularly analyzes data to help identify future skill requirements. As a Data Analyst, we will be assisting with this initiative and have been tasked with collecting data from various sources and identifying trends for this year's report on emerging skills.

Completed as the final project of IBM's Data Analyst Professional Certificate on Coursera, this project simulates a real-world data analytics engagement for a global IT and business consulting services firm.

As a Data Analyst, I analyzed data from multiple sources to identify emerging technology trends, in-demand technical skills, and evolving workforce requirements. The analysis was designed to help the organization better understand changes in the technology landscape and make data-driven decisions regarding future skill development and hiring needs.

The project involved data collection, data wrangling and cleaning, exploratory data analysis, statistical analysis, data visualization, and insight generation. By transforming raw datasets into actionable insights, the project demonstrates how data analytics can support strategic workforce planning and help organizations remain competitive in a rapidly evolving technology industry.

### Task 1

Our first task is to collect data for the technology skills that are most in demand from various sources including job postings, blog posts, and surveys. We will begin by scraping internet websites and accessing APIs to collect data in various formats like .csv, excel sheets, and databases.

In the first task of this project focuses on building a comprehensive dataset of the most in-demand technology skills across the industry. Data is collected from multiple sources including job postings, technology blogs, and developer surveys using web scraping techniques and APIs. The project integrates data from a variety of formats, including CSV files, Excel spreadsheets, and databases, creating a unified foundation for downstream data cleaning, analysis and visualization. 

### Task 2

Once we've collected enough data we will take the collected data and prepare it for analysis by using data wrangling techniques like finding duplicates, removing duplicates, finding missing values, and inputting missing values.

In the second task of this project, following data collection, the datasets are transformed and prepared for analysis through a structured data-wrangling and preprocessing workflow. This includes identifying and removing duplicate records, detecting and evaluating missing values, and applying appropriate imputation techniques to address incomplete data. 

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

This project uses data from Stack Overflow's 2019 Developer Survey, a global survey of software professionals that collected approximately 90,000 responses. The dataset was open-sourced by Stack Overflow under the 


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

# Census-Data-Standardization-and-Analysis-Pipeline

# TECHNOLOGIES:
Python, MongoDB , MySQL, Streamlit

# PROBLEM STATEMENT:
The task is to clean, process, and analyze census data from a given source, including data renaming, missing data handling, state/UT name standardization, new state/UT formation handling, data storage, database connection, and querying. The goal is to ensure uniformity, accuracy, and accessibility of the census data for further analysis and visualization.
Census Data Standardization and Analysis Pipeline

# IMPORT NECESSARY LIBRARIES
To import necessary libraries to run the below tasks
Python : Pandas, docx2txt
Mango db: pymongo
Mysql : flask_sqlalchemy, mysql-connector-python, ,ysql
Streamlit : Streamlit

# TASK: 
Install and import the necessary libraries and import the input data census_2011

# Task 1: Rename the Column names 
As per the task rename the necessary columns accordingly

# Task 2: Rename State/UT Names Task 
Rename the names in the Column State/UT according to the given task

# Task 3: New State/UT formation Task 
For the States/UT there are a few changes in the district for States Telangana and Ladakh. Add those district for telangana from the given doc file. For Ladakh simply store it in a variable and assign those Distrcts

# Task 4: Find and process Missing Data Task 
Finding the percentage of missing data. Using formula's and other columns fill the missing data and find how much percentage of Data is filled

# Task 5: Save Data to MongoDB Task 
After all the data transformation is done the data is stored in MangoDB

# Task 6: Database connection and data upload 
Data should be fetched from the mongoDB and to be uploaded to a relational database using python code 

# Task 7: Run Query on the database and show output on streamlit
Using mysql run the given task indivually and display the output on streamlit

# RESULTS: 
Understanding how to clean, process, and analyze data and use the necessary tools and libraries to display the output

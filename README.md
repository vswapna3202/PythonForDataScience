## Python for Data Science

Welcome to the `pythonfordatascience` repository! This repository contains a collection of exercises and projects focusing on using Python and pandas for data science tasks, including data cleaning and exploratory data analysis (EDA) done as part of codecademy course Python for Data Science.

## Exercises

### Exercise 1: [Exercise001 - 1](./exercises/Exercise001/laptop_repairs_notebook_001.ipynb)
- Description: This exercise imports and does analysis on repairs dataset.
- Dataset: [repair dataset](./exercises/Exercise001/repair.csv).
- Topics Covered: Importing dataset, count of all unique countries using pandas method, sorting them in ascending order, displaying datatypes of the dataset, finding earliest year repaired using pandas method.

### Exercise 1: [Exercise001 - 2](./exercises/Exercise001/laptop_repairs_notebook_002.ipynb)
- Description: This exercise imports and does analysis on laptops dataset.
- Dataset: [laptops dataset](./exercises/Exercise001/laptops.csv).
- Topics Covered: Importing dataset, summarize the ages of laptops bought in for repair, determine most common problems needing repair, investigate the most common outcomes.

### Exercise 2: [Exercise002](./exercises/Exercise002/notebook.ipynb)
- Description: Analyze Electric Vehicle Stations in Python.
- Dataset: [stations dataset](./exercises/Exercise002/stations.csv).
- Topics Covered: Explore and analyse a US Department of energy dataset of alternate fuel stations, including electric vehicle charging stations. Analysis includes different types of fuels, locations and other station properties. Uses Boolean masks to filter dataset down to public-access electric vehicle charging stations. Analysis of different types of ownership of stations to determine which station has most stations and a mini-analysis of the west coast alone.

### Exercise 3: [Exercise003](./exercises/Exercise003/notebook.ipynb)
- Description: Analyzes National Park information.
- Dataset: [nationalparks dataset](./exercises/Exercise003/nationalparks.csv)
- Topics covered: Imports dataset and works on renaming columns, dropping columns, calculates average daily visits for 2021, converts datatype from object to categorical

### Exercise004: [Exercise004](./exercises/Exercise004/notebook.ipynb)
- Description: Analyzes Wage Data with Python across different industries and occupations.
- Dataset: [wages dataset](./exercises/Exercise004/wages.csv)
- Topics covered: Uses string methods to clean data and prepare for analysis. Uses pandas calculations to compute annual wages and compare each occupation to its industry wage average. Uses sorting and filtering to understand which occupation are highest earners.

### Exercise005: [Exercise005](./exercises/Exercise005/notebook.ipynb)
- Dataset: [results dataset](./exercises/Exercise005/results.csv)
- Topics covered: Counts the number of unique home and away teams, computes tournament statistics like number of games played, sum of total goals, maximum and minimum win margins, provides analysis for 2022 FIFA World Cup

### Exercise006: [Exercise006](./exercises/Exercise006/notebook.ipynb)
- Dataset: [csat dataset](./exercises/Exercise006/csat.csv)
- Topics covered: Explore and analyse the csat dataset. Provides statistical information, summarises negative ratings, calculates negative ratings by quarter

## Projects

### Project 1: [Electric Vehicle Analysis](./projects/Project001/electric_vehicle_analysis.ipynb)
- Description: This project Provides an analysis of Electric Vehicle Population data using Python and Pandas .
- Dataset: [electric vehicle dataset](./projects/Project001/Electric_Vehicle_Population_Data.csv).
- Topics Covered: Does Data cleaning like dropping columns which are not relevant to the analysis, converts datatype of column to categorical, performs exploratory analysis on Electric Vehicle Population by identifying vehicles which uses Clean Alternative Fuel and electric vehicles with range greater than 200 was identified and also states with highest counts of Battery Electric Vehicles and Plug-in Electric Vehicles and their details displayed.

### Project 2: [Ad Effectiveness Python Project](./projects/Project002/notebook.ipynb)
- Description: Compare Ad Effectiveness Using A/B Tests with Python Project
- Dataset: [Users Dataset](./projects/Project002/users.csv)
           [Devices Dataset](./projects/Project002/devices.csv)
           [Ads Dataset](./projects/Project002/advertisements.csv)
- Topics covered: Analyzes effectiveness of two different ad campaigns. Analysis involves if version B which is the new advertisement introduced is outperforming version A which is the existing advertisement. Multiple datasets are merged using python and pandas, analyses done on whether the effectiveness of ads vary across social media platforms and whether target of mobile, PC or tablets needs to increase in future.

### Project 3:[High-Speed Railways](./projects/Project003/notebook.ipynb)
- Description: Analyzing High-Speed Railway Delays Project
- Dataset: [Multiple Datasets](./projects/Project003/datasets/)
- Topics covered: This project uses python to analyze a real-world dataset on high-speed railway operations. Uses List comprehensions to load and concatenate daily railway operation datasets, use if/else control flow to clean and prep data, analyzes the impact of holidas, distance and weather on railway delays

### Project 4: [Internet Usage](./projects/Project004/notebook.ipynb)
- Description: Analyze Internet Use with Python
- Dataset: [internet dataset](./projects/Project004/internet.csv)
- Topics covered: This project analyses the data on internet usage from our World in Data(via the World Bank and International Telecommunications Union). Custom methods are written to answer questions like 
    how long does it take for internet to reach the majority of people in different countries, regions, and income brackets?
    how much does internet usage accelerate over the years?
    how did the growth of the internet compare across the 2000s and 2010s?

## Contributing
Contributions to this repository are welcome! If you have exercises or projects related to Python and pandas for data science that you would like to share, feel free to submit a pull request.

## License
This repository is licensed under the [MIT License](LICENSE).

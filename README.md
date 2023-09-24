# Chicago-Educational-Outcomes-Data-Analysis
Enhancing Educational Outcomes in Chicago: Data Analysis of Socioeconomic Factors, Crime, and School Performance.

## Overview

This project focuses on analyzing datasets related to educational outcomes for children and young people in Chicago. The goal is to identify factors that impact school enrollment, safety, health, and environment ratings of schools within the city. We utilize data from the Chicago Data Portal, including socioeconomic indicators, school performance, and crime data, to gain insights and answer critical questions.

## Technologies

This project was developed using the following technologies and tools:

- **Python**: Used for data analysis, including querying the database and data manipulation.
- **SQLite**: The database management system used to store and query the datasets.
- **Jupyter Notebook**: Used for interactive data exploration and analysis.
- **Pandas**: A Python library for data manipulation and analysis.
- **Matplotlib and Seaborn**: Libraries for data visualization and plotting.


## Datasets

This project utilizes three datasets from the Chicago Data Portal:

1. **Chicago Socioeconomic Indicators**
   - Contains socioeconomic indicators and a hardship index by Chicago community area for the years 2008-2012.
   - Key indicators include housing crowding, poverty rates, unemployment rates, and per capita income.

2. **Chicago Public Schools**
   - Provides school-level performance data used to create CPS School Report Cards for the 2011-2012 school year.
   - Includes information on safety scores, attendance rates, teacher quality, and more.

3. **Chicago Crime Data**
   - Reflects reported incidents of crime (excluding murders) in Chicago from 2001 to present.
   - This dataset is a subset of the full dataset, containing approximately 500 rows for the purpose of this assignment.

## Assignment Objectives

The main objectives of this assignment are:
- Load the provided datasets into a database.
- Write and execute SQL queries to answer specific questions.
- Present query results and findings effectively.
- Gain insights into the factors affecting educational outcomes in Chicago.

## Project Structure

The project repository is structured as follows:

- **data-sets/**: This directory contains the three CSV files mentioned in the assignment.
- **results/**: Contains screenshots of the query results, providing evidence of successful execution.
- **notebooks/**: Includes Jupyter notebooks used in the project.
   - `data_exploration.ipynb`: Initial exploration and understanding of the datasets.
   - `data_analysis.ipynb`: Execution of SQL queries and data analysis.
- **README.md**: This documentation file, providing an overview of the project.

## Running the Analysis

To run the analysis and reproduce the results, follow these steps:

1. Download the project repository or clone it to your local machine.
2. Ensure you have SQLite or a compatible database system installed.
3. Navigate to the `notebooks/` directory.
4. Open and execute the `data_exploration.ipynb` notebook to understand the datasets.
5. Execute the `data_analysis.ipynb` notebook to run SQL queries and analyze the data.
6. Refer to the `results/` directory for screenshots of query results.

## Project Contributors

- [Mohamed Farahat]: [GitHub Profile](https://github.com/Farahat612)

## Acknowledgments

This project was completed as part of an educational assignment and is based on the provided datasets from the Chicago Data Portal.
It serves as an assignment for `Databases and SQL for Data Science with Python` course which is part of `IBM Data Engineer` Professional Certificate on Coursera. 

## License

This project is licensed under the [MIT License](LICENSE).



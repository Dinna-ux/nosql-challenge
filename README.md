# nosql-challenge
# Hawaii Weather Data Analysis

## Overview

This project aims to analyze weather data from Hawaii, focusing on precipitation and temperature measurements. The data is stored in a SQLite database (`hawaii.sqlite`) containing two main tables: `measurement` and `station`. Python, along with libraries like SQLAlchemy, Pandas, and Matplotlib, is used for data retrieval, analysis, and visualization.

## Prerequisites

- Python 3.x
- Jupyter Notebook or any Python IDE
- Required Python libraries: SQLAlchemy, Matplotlib, Pandas, NumPy

## Getting Started

1. **Clone this repository to your local machine:**
- pip install -r requirements.txt

 Project Structure
 |-- README.md
|-- NoSQL_analysis_starter.ipynb
|-- NoSQL_setups_starter.ipynb
|-- Resources folder

Data Source
The data is sourced from the Food Standards Agency (FSA) API, specifically the food hygiene ratings.

Analysis
Establishments with a Hygiene Score of 20:

Query establishments with a hygiene score of 20, display the first document, and output to a Pandas DataFrame.
Establishments in London with RatingValue >= 4:

Query establishments in London with a rating value greater than or equal to 4, display the first document, and output to a Pandas DataFrame.
Top 5 Establishments with RatingValue of 5, Sorted by Lowest Hygiene Score, Nearest to "Penang Flavours":

Query establishments with a rating value of 5, sorted by hygiene score, and near specified coordinates.
Number of Establishments with a Hygiene Score of 0 in Each Local Authority Area:

Aggregate establishments with a hygiene score of 0 and group by Local Authority, sorted by count.
Contributors
Dinna WItness

Acknowledgments
Food Standards Agency (FSA) for providing the data.
MongoDB and pymongo developers for their work on the database and driver.

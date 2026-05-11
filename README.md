

## Student Name
- Ismail Mahmoud Basbous (ismail_158818)
- Layla Sameeh Nayyouf (layla_197901)

## Project Title
Big Data Analytics System for Airbnb Listings Using Apache Spark and Spark SQL

## Tools and Libraries Used

### Core Tools
- Apache Spark 3.x (PySpark)
- Python 3.13
- Jupyter Notebook

### Python Libraries
- pyspark - Spark DataFrame API and Spark SQL
- pandas - Initial data cleaning and preprocessing
- numpy - Numerical operations
- plotly - Interactive charts

## Dataset
- **Source:** Kaggle - Airbnb Open Data
- **Original File:** Airbnb_Open_Data.csv
- **Size:** 102,599 records, 26 columns
- **Description:** Airbnb listings data including price, room type, reviews, availability, and host information

## Project Overview
This project implements a complete big data analytics pipeline using Apache Spark and Spark SQL. It includes:
- Data cleaning and preprocessing using Pandas
- Distributed data processing using Spark
- 5 analytical queries using Spark DataFrame API
- 5 analytical queries using Spark SQL
- Data visualizations using Plotly

## Data Files

| File | Description |
|------|-------------|
| `Airbnb_Open_Data.csv` | Original raw dataset downloaded from Kaggle |
| `airbnb_cleaned_data.csv` | Raw data file after initial cleaning (output from preprocessing stage) |
| `airbnb_data_cleaned.csv` | Final cleaned dataset after full preprocessing with Pandas (ready for Spark analysis) |

## Project Files Description

| File | Description |
|------|-------------|
| `preprocessing.py` | Contains the cleaning and preprocessing code implemented on the dataset using Pandas |
| `spark_loader.ipynb` | Creates Spark session and loads cleaned data |
| `spark_analysis.ipynb` | Contains the analytics performed through Apache Spark (DataFrame API) with visualizations |
| `spark_sql_queries.ipynb` | Contains the SQL queries developed and the result tables |
| `main.ipynb` | Main orchestrator that runs all project files in sequence |

## Steps Required to Run the Project

### Prerequisites
1. Install Java JDK 11 or 17
2. Install Apache Spark
3. Install Python 3.13

### Installation

1. Download or clone the project folder to your desktop

2. Install required Python packages:
```bash
pip install pyspark pandas numpy plotly

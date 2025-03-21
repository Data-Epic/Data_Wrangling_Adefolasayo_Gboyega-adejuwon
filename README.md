# Data Wrangling Project

This project demonstrates data wrangling techniques using Pandas on a customer dataset (`MOCK_DATA.csv`).

## Project Overview

The project involves the following steps:

1.  **Data Loading:** Loading the first 75% of the `MOCK_DATA.csv` file into a Pandas DataFrame.
2.  **Data Cleaning:**
    * Removing consecutive duplicate rows.
    * Converting the "Sign-up Date" column to datetime and replacing 2020 dates with NaN.
    * Dropping rows where "Total Purchases" < 5 and "Country" is "Canada."
3.  **Feature Engineering:** Creating a "Loyalty Score" column based on "Total Purchases" and "Sign-up Date."
4.  **Data Aggregation & Filtering:**
    * Grouping data by "Country" (excluding "Mexico").
    * Calculating the average and maximum "Total Purchases."
    * Finding the most common "Loyalty Score" for each country.
5.  **Data Export & Report Generation:**
    * Saving the processed DataFrame to a CSV file named "processed_data\_DD\_MM\_YYYY.csv."
    * Printing the first 10 shuffled rows of the processed DataFrame.
6.  **Report Generation:**
    * Creating a markdown report summarizing the findings.

## Files

* `MOCK_DATA.csv`: The original dataset.
* `processed_data_DD_MM_YYYY.csv`: The processed dataset (where DD\_MM\_YYYY is the current date).
* `Data_Wrangling_Task_one.ipynb`: The Jupyter Notebook containing the code and report.
* `README.md`: This file.

## Dependencies

* Python 3.x
* Pandas
* NumPy
* SciPy


## Usage

1.  Ensure that `MOCK_DATA.csv` is in the same directory as the Jupyter Notebook or adapt the file path in the notebook.
2.  Run the `Data_Wrangling_Task_one.ipynb` Jupyter Notebook.
3.  The processed CSV file (`processed_data_DD_MM_YYYY.csv`) will be generated.
4.  The output will be printed to the notebook's output cells.
5.  The markdown report will be printed to the notebook's output cells.

## Results

The processed data provides insights into customer loyalty and purchase behavior across different countries. The "Loyalty Score" feature helps categorize customers, and the aggregated data shows variations in purchase patterns. The final CSV file contains the cleaned and processed data, ready for further analysis.

## Author

Adefolasayo


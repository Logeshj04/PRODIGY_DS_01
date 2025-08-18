# Global Population Dynamics (1960-2022): Data Wrangling, Analysis, and Visualization

## Project Description

This project analyzes and visualizes world population data from 1960 to 2022 using Python, pandas, and seaborn. The objective is to explore population trends globally and for specific countries, identify patterns, and present the findings through various plots. The analysis includes data cleaning, transformation, and the generation of visualizations to show population changes over time and compare population sizes across different entities.

## Data Source

The dataset used in this notebook is sourced from the World Bank and contains total population data for various countries and regions from 1960 to 2022. The file used is `API_SP.POP.TOTL_DS2_en_csv_v2_498834.csv`.

## Notebook Structure

The notebook is structured as follows:

1.  **Setup and Data Loading**: Imports necessary libraries (pandas, matplotlib, seaborn) and loads the dataset.
2.  **Data Inspection and Cleaning**: Performs initial data inspection (head, tail, shape, columns, dtypes, info, describe) and handles missing values by forward filling.
3.  **Data Transformation**: Melts the dataframe to transform the year columns into rows for easier analysis and visualization.
4.  **Exploratory Data Analysis and Visualization**:
    *   Visualizes world population over the years using a bar plot.
    *   Calculates and visualizes the total population values per year using a horizontal bar plot.
    *   Identifies and displays the countries with the lowest population in 1960 and 2022.
    *   Generates bar plots to visualize the population trends for the countries with the lowest population in 1960 and 2022.

## Technical Details

The following libraries are used in this notebook:

*   **pandas**: For data manipulation and analysis.
*   **matplotlib**: For creating static, interactive, and animated visualizations.
*   **seaborn**: For creating informative statistical graphics.

## Instructions

To run this notebook, follow these steps:

1.  Clone the GitHub repository to your local machine.
2.  Make sure you have Python installed, along with the required libraries. You can install them using pip:

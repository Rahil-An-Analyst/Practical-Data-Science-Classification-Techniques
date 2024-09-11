# Rainfall Pattern Analysis in ABC City (2013-2023)

## Report
View the analysis and visualizations here -  
(https://nbviewer.org/github/rahilprime/Practical-Data-Science/blob/main/Project_1_Rainfall_Pattern_Analysis_ABC_City/PracticalDS_Project1.ipynb)

## Overview
This project aims to clean and analyze daily rainfall data for ABC City between 2013 and 2023. The goal is to identify rainfall patterns, trends, and seasonal variations over time, providing valuable insights for further analysis or modeling.

## Objectives
- Clean the dataset to handle missing values, duplicates, and inconsistent data.
- Perform exploratory data analysis (EDA) to uncover rainfall trends and patterns over the decade.
- Visualize seasonal rainfall variations and highlight extreme weather events.

## Data Description
- **Data Source**: Daily rainfall records from ABC City (2013-2023).
- **Filtered Columns**:
  - **Date**: The specific date of rainfall measurement.
  - **Rainfall (mm)**: The daily rainfall in millimeters.
- **Filtered Observations**: Daily rainfall data for a 10-year period, containing over 3,650 observations.

## Methodology
- **Data Cleaning**: Handling missing values through interpolation, removing duplicates, and standardizing date formats.
- **Exploratory Data Analysis (EDA)**:
  - **Univariate**: Analyzing rainfall distribution across different time periods.
  - **Bivariate**: Investigating the relationships between rainfall and seasons or years.
  - **Seasonal Analysis**: Identifying patterns across months and years to detect wet and dry seasons.

## Results
Key insights from the exploratory analysis include:
- Detection of distinct wet and dry seasons for ABC City.
- Increasing or decreasing trends in annual rainfall over the years.
- Identification of extreme rainfall events and their distribution across the decade.

## How to Use
- **Setup**: Ensure Python is installed with relevant packages (`pandas`, `matplotlib`, `seaborn`, etc.).
- **Usage**: Run `data_cleaning.ipynb` for cleaning the dataset and `exploratory_analysis.ipynb` to generate insights and visualizations. Make sure the dataset `rainfall_data.csv` is placed in the `data/` directory before executing.

## Files
- `README.md`: This file.
- `PracticalDS_Project1.ipynb`: Notebook containing the exploratory analysis and visualizations.
- `PracticalDS_Project1.doc`: Report document.
- `Data.csv`: The original dataset containing daily rainfall records for ABC City.

## License
This project is licensed under the MIT License.

## Contact
For more information, please contact [Mohammad Rahil](mailto:smrahil98@gmail.com).

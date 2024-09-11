# Classification Models Analysis for Customer Data

## Report
View the analysis and visualizations here -  

## Overview
This project involves analyzing and modeling customer data to predict customer behavior. The goal is to evaluate and compare the performance of various classification models to identify the most effective model for the given dataset.

## Objectives
- Clean the dataset to handle missing values, outliers, and data inconsistencies.
- Perform exploratory data analysis (EDA) to understand the dataset and its features.
- Apply and evaluate multiple classification models, including Logistic Regression and Random Forest.
- Compare model performance and select the best-performing model.

## Data Description
- **Data Source**: Customer data used for classification tasks.
- **Filtered Columns**:
  - **Customer_ID**: Unique identifier for each customer.
  - **Features**: Various attributes relevant to customer behavior.
  - **Target**: The classification label indicating customer behavior.
- **Filtered Observations**: Data includes several thousand customer records with multiple features.

## Methodology
- **Data Cleaning**: Addressing missing values, handling outliers, and standardizing data formats.
- **Exploratory Data Analysis (EDA)**:
  - **Univariate**: Analyzing individual features and their distributions.
  - **Bivariate**: Investigating relationships between features and the target variable.
  - **Correlation Analysis**: Identifying key features that impact customer behavior.
- **Modeling**:
  - **Logistic Regression**: Building and evaluating a logistic regression model.
  - **Random Forest**: Building and evaluating a random forest model.
  - **Model Comparison**: Assessing model performance using metrics like accuracy, precision, recall, and F1-score.

## Results
Key insights from the analysis include:
- Performance comparison of Logistic Regression and Random Forest models.
- Identification of key features influencing customer behavior.
- Recommendations for the most effective model based on performance metrics.

## How to Use
- **Setup**: Ensure Python is installed with relevant packages (`pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, etc.).
- **Usage**: Run `PracticalDS_Project2.ipynb` for data cleaning and preprocessing, and `modeling_analysis.ipynb` to train and evaluate classification models. Ensure the dataset `customer_data.csv` is placed in the `data/` directory before executing.

## Files
- `README.md`: This file.
- `PracticalDS_Project2.ipynb`: Notebook containing the model training, evaluation, and comparison
- `report.pdf`: Report document. 
- `buddymove_holidayiq.csv`: The dataset used for classification tasks.

## License
This project is licensed under the MIT License.

## Contact
For more information, please contact [Mohammad Rahil](mailto:smrahil98@gmail.com).

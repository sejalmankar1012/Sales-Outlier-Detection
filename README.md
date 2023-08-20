
# Outlier Sales Detection Project

## Overview

This project involves the development of a predictive analytical solution for outlier sales detection using the Isolation Forest algorithm. The project aims to identify unusual sales patterns and provide insights for effective inventory management and business decision-making.

## Project Highlights

- Developed a predictive analytical solution using the Isolation Forest algorithm for outlier sales detection.
- Conducted univariate and bivariate analysis resulting in approximately 25% outlier detection.
- Collaborated across different teams and business units to understand requirements, including key performance indicators (KPIs) like contribution gap and sales growth.
- Communicated results to stakeholders, providing valuable insights for informed business decisions.

## Project Steps

1. **Data Loading and Preprocessing**
   - Loaded training and test datasets (`Train.csv` and `Test.csv`).
   - Handled duplicate rows and transformed data to align with sales-related parameters.

2. **Outlier Detection**
   - Used Isolation Forest algorithm to predict outlier sales.
   - Identified and visualized potential outliers using boxplots and scatter plots.

3. **Data Exploration and Visualization**
   - Explored sales trends, product categories, and geographical sales distributions.
   - Visualized correlations and relationships between variables.

4. **Data Processing and Scaling**
   - Extracted relevant features and target variables.
   - Applied MinMaxScaler to scale feature variables.

5. **Isolation Forest for Outlier Detection**
   - Fitted Isolation Forest model to the scaled training data.
   - Predicted outliers in the training dataset.

6. **Tableau Dashboard (Optional)**
   - Created a Tableau dashboard to visually present analysis results.
   - Incorporated interactive visualizations and filters for user exploration.

7. **Results and Communication**
   - Shared insights with stakeholders, emphasizing contribution gap, sales growth, and outliers.
   - Facilitated informed business decisions through clear communication of findings.

## Requirements

- Python 3.x
- Required Python libraries (NumPy, Pandas, Seaborn, Scikit-learn, Matplotlib)

## Usage

1. Clone this repository.
2. Install the required Python libraries using `pip install -r requirements.txt`.
3. Run the provided Jupyter Notebook to perform data analysis and outlier detection.
4. Optionally, create and explore the Tableau dashboard for visualizing project results.


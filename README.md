# Data Visualization and Cleaning Project

## Overview
This Jupyter notebook demonstrates a data visualization and cleaning process for the "Fury_Friends" dataset. The dataset contains sales information related to pet products, including details about managers, sales units, revenue, costs, and profits across different areas.

## Key Features
Data loading and initial inspection

Data cleaning and preprocessing

Exploratory data analysis

Visualization techniques

## Dataset Information
The dataset contains 1001 rows and 9 columns initially, which was reduced to 647 rows after removing duplicates.

Columns:
* ManagersFirstName

* ManagersSurname

* Area

* Pet

* UnitsSld (Units Sold)

* Revenue

* Cost

* Profit

* Date

## Data Cleaning Steps
Removed duplicates: 354 duplicate rows were removed

## Renamed columns:

'Managers First Name' → 'ManagersFirstName'

'Managers Surname' → 'ManagersSurname'

'Units Sld' → 'UnitsSld'

## Handled missing values:

Identified missing values (about 1.15% of total data)

Visualized missing data using a heatmap

## Exploratory Analysis
Calculated basic statistics (mean, min, max, etc.)

Examined value counts for categorical columns

Checked data types

## Visualization
Created a heatmap to visualize missing data patterns in the dataset.

### Dependencies
pandas

numpy

matplotlib

seaborn

plotly.express

scikit-learn (LabelEncoder)

## Usage
Install required packages: pip install pandas openpyxl

Run the notebook cells sequentially to perform data cleaning and visualization

### Insights
The dataset contains sales records from 5 main managers

Data spans from February to December 2020

Most missing values are in the Profit and UnitsSld columns

#### Next Steps
Potential future work could include:

More advanced visualizations

Time series analysis

Predictive modeling

Further feature engineering

#### This notebook provides a solid foundation for understanding and preparing the Fury_Friends dataset for further analysis.
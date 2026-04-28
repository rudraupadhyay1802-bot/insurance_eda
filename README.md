# Insurance Charges Analysis

This project performs exploratory data analysis on a medical insurance dataset to understand how personal attributes such as age, sex, BMI, number of children, smoking status, and region affect insurance charges.

The analysis is implemented in Python using Pandas, NumPy, Matplotlib, and Seaborn inside a Jupyter Notebook / Google Colab environment.

## Overview

The main objective of this project is to explore the dataset, identify meaningful patterns, and understand which factors are associated with higher medical insurance costs.

The notebook includes:
- Data loading and inspection
- Data cleaning and validation
- Descriptive statistical analysis
- Category-wise distribution analysis
- Correlation analysis of numerical features
- Visualizations for pattern discovery

## Dataset Description

The dataset contains **1338 records** and **7 features**.

### Features

- **age** – Age of the individual
- **sex** – Gender of the individual
- **bmi** – Body Mass Index
- **children** – Number of dependents covered by insurance
- **smoker** – Smoking status
- **region** – Residential region
- **charges** – Medical insurance cost billed to the individual

## Data Inspection

Initial exploration was carried out using:
- `head()`
- `tail()`
- `info()`
- `describe()`
- `shape`
- `columns`
- `dtypes`

This helped confirm the structure of the dataset and the type of each variable.

## Data Cleaning

The notebook includes basic data quality checks such as:
- Checking for missing values
- Identifying duplicate records
- Removing duplicates where necessary

The dataset does not contain missing values, and duplicate rows were handled during preprocessing.

## Descriptive Statistics

Key observations from the numerical summary include:
- Average age is around **39 years**
- Average BMI is around **30.66**
- Average number of children is about **1.09**
- Average insurance charge is approximately **13270**
- Maximum insurance charge exceeds **63770**

These statistics provide a quick overview of the central tendency and spread of the dataset.

## Category Distribution

The notebook also explores the distribution of categorical and discrete variables:
- Gender distribution
- Smoker vs non-smoker counts
- Region-wise distribution
- Number of children distribution
- Age frequency analysis

This helps in understanding how the dataset is balanced across different groups.

## Correlation Analysis

Correlation analysis was performed on the numerical variables to measure their relationship with insurance charges.

Main findings:
- **Age** shows a moderate positive relationship with charges
- **BMI** shows a weaker positive relationship with charges
- **Children** has a relatively low relationship with charges

A heatmap was also created to visualize the correlation matrix.

## Visualizations

Several visualizations were used to better understand the data, including:
- Correlation heatmap
- Gender distribution plot
- Region distribution plot
- BMI distribution/value analysis
- Scatter plot showing the relationship between BMI and charges

These charts help reveal patterns and trends that may not be obvious from tables alone.

## Tools and Libraries

This project uses the following Python libraries:
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Matplotlib** for plotting
- **Seaborn** for statistical visualization

## How to Run

1. Clone the repository:
   ```bash
   git clone <your-repository-link>
   ```

2. Move into the project folder:
   ```bash
   cd <your-project-folder>
   ```

3. Install the required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

4. Place the `insurance.csv` file in the same directory as the notebook.

5. Launch Jupyter Notebook:
   ```bash
   jupyter notebook Insurance-1.ipynb
   ```

## Learning Outcomes

This project is useful for learning:
- Exploratory Data Analysis (EDA)
- Data cleaning and validation
- Statistical summary interpretation
- Correlation analysis
- Data visualization with Python

## Future Improvements

This project can be extended by:
- Encoding categorical variables
- Building regression models to predict charges
- Evaluating model performance using MAE, RMSE, and R-squared
- Comparing multiple machine learning algorithms

## Author

**Rudra M. Upadhyay**

## License

This project is intended for educational and practice purposes.

# Data Visualization: Car Sales Analysis

## Project Overview
The goal of this project is to conduct an exploratory analysis on the "carSales" dataset, which contains various quantitative and qualitative details about used car sales. We aim to execute the classic steps of Preparation, Processing, Transformation, Analysis, and Visualization to extract valuable insights from the exploratory analysis.

## Table of Contents
1. Importing Libraries
2. Importing and Exploring the Dataset
3. Data Visualization
4. Conclusion

## 1) Importing Libraries
In this project, we utilize a range of libraries for data manipulation and visualization:
- Plotly (for interactive plots)
- Seaborn and Matplotlib (for statistical visualizations)
- Pandas (for data manipulation)
- Missingno (for handling missing values)
- Pandasql (for applying SQL queries to Pandas DataFrames)

## 2) Importing and Exploring the Dataset
The initial stage involves loading the dataset and conducting a preliminary examination to understand its variables and the necessary data cleaning steps. We use `pandasql` for executing SQL queries within our notebook. Key functions include:
- Reading the dataset
- Displaying the first and last few records
- Generating summary statistics
- Checking the dataset information for data types and missing values

## 3) Data Visualization
This crucial stage involves various forms of visualizations:
- Missing Data Visualization: Using Missingno to visualize missing (NaN) values in the dataset.
- Histograms: Plotting histograms for various variables like Power Performance Factor, Year Resale Value, Sales in Thousands, and Price in Thousands to understand their distribution.
- Correlation Matrix: Creating a heatmap to observe Pearson correlation among different quantitative variables.
- Scatter Plots: Examining relationships between variables like Power Performance vs Price and Horsepower vs Price.
- Bar Charts: Understanding which car brand has the highest total sales value and average resale value.
- Pie Chart: Analyzing the proportion of sales by vehicle type (Passenger vs Car).

## Conclusion
The exploratory data analysis of the "Car Sales" dataset demonstrates the power of data visualization in extracting meaningful insights. The analysis reveals critical trends and correlations in the used car sales market, emphasizing the importance of visual tools in understanding complex datasets.

---

For any queries or feedback, please contact me through my [Linkedin](https://www.linkedin.com/in/vinicius-capozzi)

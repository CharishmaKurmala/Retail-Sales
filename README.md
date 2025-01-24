# Retail Sales Analysis Project

This project analyzes retail sales data to provide insights into sales trends, profitability, and customer behavior. The analysis is performed using Python and various data analysis libraries.

## Project Structure

The project consists of a Jupyter Notebook file (`RetailSalesProject.ipynb`) that contains the following main sections:

1. **Importing Required Libraries**
2. **Reading the Data**
3. **Data Preprocessing**
4. **Exploratory Data Analysis**
5. **Time Series Analysis**

## Required Libraries

The following Python libraries are used in this project:

- `numpy`
- `pandas`
- `matplotlib`
- `requests`
- `seaborn`
- `plotly.express`

## Data

The project uses a CSV file named `SalesData.csv`, which contains retail sales information. The dataset includes the following key columns:

- **Order Date**
- **Ship Date**
- **Ship Mode**
- **Customer Name**
- **Segment**
- **Country**
- **City**
- **State**
- **Product Name**
- **Category**
- **Sub-Category**
- **Sales**
- **Quantity**
- **Discount**
- **Profit**

External Dataset from Calendarific was integrated using API Key for analyzing Holiday Sales.

## Features

The analysis includes:

- **Data cleaning and preprocessing**
- Calculation of additional features such as:
  - Year
  - Is Holiday
  - Month
  - Days to Ship
- Aggregation of sales and profit data by various dimensions (e.g., city, state)
- Time series analysis of sales data

## Usage

To run this project:

1. Ensure all required libraries are installed.
2. Place the `SalesData.csv` file in the same directory as the notebook.
3. Open and run the `RetailSalesProject.ipynb` file in a Jupyter Notebook environment.

## Results

The notebook generates various visualizations and insights about the retail sales data, including:

- Sales and profit trends over time
- Top-performing cities and states
- Product category performance
- Impact of holidays on sales
- Shipping efficiency analysis

These results can be used to inform business decisions and strategies in the retail sector.

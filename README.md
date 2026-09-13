
# Capstone_Project Used Car Market Analysis

An exploratory data analysis project focused on understanding the used car market and identifying patterns in used car selling prices.

## Project Overview

This project analyses a dataset containing information about **6,019 used cars**.

The analysis focuses on understanding the relationship between used car prices and factors such as:

- Car brand
- Location
- Manufacturing year
- Kilometres driven
- Fuel type
- Transmission
- Ownership type
- Mileage
- Engine
- Power
- Number of seats

The project also includes data cleaning, handling of missing values, feature transformation and exploratory analysis.

## Dataset

The dataset contains **6,019 records and 14 columns**.

Key features include:

| Feature | Description |
|---|---|
| Name | Name of the car |
| Location | Location where the car is listed |
| Year | Manufacturing year |
| Kilometers_Driven | Distance driven by the car |
| Fuel_Type | Fuel type |
| Transmission | Transmission type |
| Owner_Type | Number/type of previous owners |
| Mileage | Mileage of the car |
| Engine | Engine capacity |
| Power | Engine power |
| Seats | Number of seats |
| Price | Selling price |

## Project Workflow

### 1. Data Understanding
- Inspected dataset dimensions
- Examined data types
- Generated descriptive statistics
- Analysed unique values and value distributions
- Checked for duplicate records

### 2. Data Cleaning
- Analysed missing values
- Removed unnecessary columns
- Converted numerical features containing units into numerical values
- Extracted car brands from the `Name` column

### 3. Exploratory Data Analysis
Explored patterns in used car prices across different characteristics, including:

- Car brands
- Locations
- Fuel types
- Transmission types
- Vehicle characteristics

### 4. Brand-level Price Analysis

The project examines the **average selling price of used cars by brand** to understand differences in pricing across manufacturers.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib

## Key Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Transformation
- Missing Value Analysis
- Feature Extraction
- Descriptive Statistics
- Data Visualisation

## Project Structure

```text
Used-Car-Market-Analysis/
│
├── used_car_market_analysis.ipynb
├── Excel Solutions.ipynb
├── used_cars.csv
└── README.md

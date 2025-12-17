# Indian Fashion Analytics Dashboard

## Project Overview

This project presents an end-to-end data analytics workflow to analyze Indian fashion trends using real e-commerce data from Myntra. The goal is to uncover insights related to brand popularity, gender-based preferences, price segmentation, and color trends, and prepare a clean dataset for BI dashboarding.

The project focuses on data cleaning, exploratory data analysis (EDA), visualization, and dashboard-ready data preparation.

## Objectives

1. Analyze Indian fashion product data in a structured, analytics-driven way

2. Understand gender-wise product distribution

3. Identify top fashion brands in India

4. Study price distribution and segmentation

5. Explore popular fashion colors

6. Prepare clean data for Power BI dashboard

## Dataset

**Source**: Myntra Fashion Product Catalogue (India)

**Type**: E-commerce product data

**Key Features**: Product ID, Product Name, Brand, Gender, Price (INR), Primary Color, Number of Images, Description

The dataset represents Indian fashion products with prices in INR, making the analysis contextually relevant.

## Tools & Technologies Used

**Python** 3.12.4<br>
**Pandas** – data cleaning & manipulation<br>
**NumPy** – numerical operations<br>
**Matplotlib** – data visualization<br>
**VS Code** – development environment<br>
**Git & GitHub** – version control<br>
**Power BI** – dashboard creation<br>

## Project Workflow

1. **Data Loading & Inspection**
	-Loaded CSV data into Pandas
	-Inspected structure, datatypes, and missing values
	-Removed nulls and duplicates

2. **Data Cleaning & Preprocessing**
	-Renamed columns for consistency
	-Standardized categorical values (e.g., gender labels)
	-Converted price data to numeric format
	-Created price range buckets:
		Very Budget
		Budget
		Mid-range
		Premium
		Luxury

3. **Exploratory Data Analysis (EDA)**
	Key analyses performed:
		-Gender-wise product distribution
		-Top 10 fashion brands on Myntra
		-Product distribution across price ranges
		-Most popular fashion colors

4. **Data Preparation for BI Dashboard**
	-Selected only analysis-relevant columns
	-Renamed columns for dashboard readability
	-Exported a clean, dashboard-ready CSV file

	Sample Insights:<br>
	1. Women’s fashion products dominate the listings <br>
	2. Majority of products fall into budget to mid-range pricing<br>
	3. A small segment of luxury products significantly skews price distribution<br>
	4. Certain colors and brands show strong dominance across listings<br>

## Project Structure
Indian-Fashion-Analytics/<br>
│<br>
├── data/<br>
│   └── myntra_fashion.csv<br>
│<br>
├── notebooks/<br>
│   └── fashion_analytics.ipynb<br>
│<br>
├── output/<br>
│   └── cleaned_fashion_data.csv<br>
│<br>
├── Myntra Fashion Analytics<br>
|<br>
|__README.md<br>

## Future Work
1. Add slicers for gender, price range, and brand
2. Perform deeper brand-wise and gender-specific analysis
3. Extend analysis with time-based trends (if data available)

## Dashboard Overview
<img width="1290" height="743" alt="image" src="https://github.com/user-attachments/assets/525d9f38-b851-482b-b976-b2866af39d1d" />


## Author

Shireen Kachroo<br>
Aspiring Data Analyst / Data Scientist<br>

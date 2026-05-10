# Cognifyz Data Science Internship

**Author:** RAGHUL K  
**Email:** raghul1826@gmail.com  
**Dataset:** Zomato Restaurant Dataset  

## Overview
This repository contains the completed tasks for the Cognifyz Technologies Data Science Internship. The project involves an end-to-end data analysis and machine learning pipeline applied to the Zomato Restaurant Dataset. It focuses on extracting actionable insights through data exploration, geospatial analysis, feature engineering, and predictive modeling.

## Tasks Accomplished

### Level 1
* **Task 1: Data Exploration and Preprocessing**
    * Explored dataset dimensions and structure.
    * Handled missing values and performed data type conversions.
    * Analyzed the target variable ("Aggregate rating") and identified class imbalances.
* **Task 2: Descriptive Analysis**
    * Calculated basic statistical measures for numerical features.
    * Explored distributions of categorical variables (Country Code, City, Cuisines).
    * Identified top cities and cuisines with the highest number of restaurants.
* **Task 3: Geospatial Analysis**
    * Mapped restaurant locations using latitude and longitude coordinates.
    * Analyzed the geographic distribution of restaurants across cities.
    * Investigated the correlation between restaurant locations and aggregate ratings.

### Level 2
* **Task 1: Table Booking and Online Delivery**
    * Calculated the percentage of restaurants offering table booking and online delivery.
    * Compared average ratings between restaurants with and without table booking.
    * Analyzed the availability of online delivery across various price ranges.
* **Task 2: Price Range Analysis**
    * Identified the most common price range among all restaurants.
    * Calculated the average aggregate rating for each price range.
* **Task 3: Feature Engineering**
    * Extracted and created new features from existing data (e.g., name length, address length, cuisine count).
    * Binary encoded categorical variables for machine learning compatibility.

### Level 3
* **Task 1: Predictive Modeling**
    * Built regression models (Linear Regression, Decision Tree, Random Forest) to predict restaurant aggregate ratings.
    * Performed train-test splits and evaluated models using metrics like Mean Absolute Error (MAE) and R-squared.
* **Task 2: Customer Preference Analysis**
    * Analyzed the relationship between cuisine types and restaurant ratings.
    * Identified the most popular cuisines based on total customer votes.
    * Determined specific cuisines that consistently receive higher ratings.
* **Task 3: Data Visualization**
    * Created histograms, bar plots, and pair plots to visualize rating distributions and feature relationships.
    * Visually compared average ratings across different cities and cuisines.

## Technologies Used
* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
* **Environment:** Jupyter Notebook

## Repository Structure
* `Dataset.csv`: The Zomato dataset used for the analysis.
* `Level1_Tasks.pdf` / `Level1_Tasks.ipynb`: Output report and code for Level 1 tasks.
* `Level2_Tasks.pdf` / `Level2_Tasks.ipynb`: Output report and code for Level 2 tasks.
* `Level3_Tasks.pdf` / `Level3_Tasks.ipynb`: Output report and code for Level 3 tasks.

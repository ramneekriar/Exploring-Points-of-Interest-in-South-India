# Exploring-Points-of-Interest-in-South-India: Data Analysis

## Overview
This project is part of the **Practical Data Science with Python** course at RMIT University. The assignment focuses on data modeling, including classification or clustering tasks. The project involves retrieving, preparing, exploring, and modeling data from a chosen dataset.

## Project Structure
- `Assignment2.ipynb`: Jupyter Notebook containing the Python code for data retrieval, preparation, exploration, and modeling.
- `buddymove_holidayiq.csv`: The dataset used for this assignment.
- `buddymove_holidayiq.csv`: The cleaned dataset after processing.
- `report.pdf`: A detailed report summarizing the project's methodology, results, and analysis.

## Tasks Overview

### 1. Data Retrieval and Preparation
- **Objective**: Select BuddyMove Data Set from UCI's Machine Learning Repository, convert it to CSV format if necessary, and thoroughly pre-process the data.
- **Steps**:
  - Loaded and examined the dataset using `pandas`.
  - Performed necessary pre-processing steps, such as handling missing values, normalizing data, and encoding categorical variables.

### 2. Data Exploration
- **Objective**: Explore the data to gain insights into each attribute and relationships between pairs of attributes.
- **Explorations**:
  - Descriptive statistics and visualizations for each attribute.
  - Correlation analysis between pairs of attributes, with relevant visualizations to illustrate relationships.

### 3. Data Modeling
- **Objective**: Model the data using decision tree classifier models and K-Nearest Neighbour classifier models with various split ratios for training and test data (60/40, 50/50, 80/20).
- **Steps**:
  - Selected and trained two models using `scikit-learn`.

### 4. Report
- **Objective**: Document the entire process from data preparation to model evaluation.
- **Content**:
  - Introduction, methodology, results, and discussion sections.
  - Detailed analysis and comparison of the models.
  - References to any external sources used.

## How to Run
1. Ensure you have `Anaconda` installed with the necessary packages (`pandas`, `scikit-learn`, `matplotlib`, etc.).
2. Open `Assignment2.ipynb` in Jupyter Notebook.
3. Run all cells to load, explore, and model the data.
4. Review the output for analysis and visualizations.

## Requirements
- Python 3
- Jupyter Notebook
- `pandas`, `scikit-learn`, `matplotlib`, and other relevant libraries.

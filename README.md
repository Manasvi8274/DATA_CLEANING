# DATA_CLEANINGSimple Data Cleaning Using Python
## Welcome to the Simple Data Cleaning project! This project demonstrates basic data cleaning techniques using Python and popular libraries such as Pandas, NumPy, Matplotlib, and Seaborn. Data cleaning is a crucial step in the data analysis process, ensuring that your dataset is accurate, consistent, and ready for analysis.

## Table of Contents
###     Features
###     Requirements
###     Installation
###     Usage
###     How It Works


## Features
###     Handling missing values
###     Removing duplicates
###     Data type conversion
###     Basic data visualization
###     Simple exploratory data analysis (EDA)


## Requirements
### To run this project, you need to have the following libraries installed:
    Python 3.x
    NumPy
    Pandas
    Matplotlib
    Seaborn
    scikit-learn
    
    You can install the required libraries using pip:
        pip install numpy pandas matplotlib seaborn scikit-learn
    
    Installation
        Clone the repository:
            git clone https://github.com/yourusername/simple-data-cleaning.git
        cd simple-data-cleaning
    
    Install the required libraries (as mentioned above).


## Usage
### Prepare your dataset:
    Place your CSV file in the project directory.
    Run the data cleaning script:

    python data_cleaning.py
        The script will perform various data cleaning operations and display visualizations of the cleaned data.


## How It Works
### Import Libraries: The script begins by importing necessary libraries, including Pandas for data manipulation, NumPy for numerical operations, Matplotlib and Seaborn for data visualization, and scikit-learn for machine learning tasks.

    import random
    import math
    import matplotlib.pyplot as plt
    import seaborn as sns
    import numpy as np
    import pandas as pd
    import warnings
    from sklearn import linear_model
    from sklearn.model_selection import train_test_split
    warnings.filterwarnings('ignore')

Load Data: The dataset is loaded into a Pandas DataFrame for easy manipulation.

Handle Missing Values: The script identifies and handles missing values by either filling them with appropriate values or removing the rows/columns.

Remove Duplicates: Duplicate entries in the dataset are identified and removed to ensure data integrity.

Data Type Conversion: The script checks and converts data types as necessary to ensure that the data is in the correct format for analysis.

Data Visualization: Basic visualizations are created using Matplotlib and Seaborn to provide insights into the cleaned data.

Exploratory Data Analysis (EDA): The script performs simple EDA to summarize the main characteristics of the dataset.
# Food Test Dataset - Data Cleaning Project

## Overview

This project involves comprehensive data cleaning tasks performed on the **Food Test Dataset**. The goal is to prepare the dataset for further analysis by addressing various data quality issues such as missing values, outliers, and inconsistent data formats.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Cleaning Steps](#data-cleaning-steps)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Data cleaning is a crucial step in the data analysis process. It involves identifying and correcting (or removing) errors and inconsistencies in data to improve its quality. This project demonstrates various data cleaning techniques using Python libraries such as pandas.

## Dataset

The dataset used in this project is the **Food Test Dataset**. It contains various attributes related to food testing and quality assessment.

## Data Cleaning Steps

The following data cleaning steps were performed:

1. **Initial Exploration**:
   - Displaying the first few rows of the dataset using `head()`.
   - Displaying the last few rows of the dataset using `tail()`.
   - Getting a concise summary of the dataset using `info()`.
   - Generating descriptive statistics using `describe()`.

2. **Renaming Columns**:
   - Renaming columns to more meaningful names for better readability.

3. **Handling Missing Values**:
   - Identifying and removing rows with null values.
   - Imputing missing values where appropriate.

4. **Removing Garbage Values**:
   - Identifying and removing irrelevant or erroneous data entries.

5. **Handling Outliers**:
   - Detecting outliers using statistical methods.
   - Removing or transforming outliers to minimize their impact on analysis.

6. **Data Type Conversion**:
   - Converting data types to appropriate formats for analysis.

## Usage

To use this project, follow these steps:

1. Clone the repository:
   ```bash
   https://github.com/HarshaVardhan1505/pandas2_cleaning_task4_cp.git
   ```
2. Navigate to the project directory:
   ```bash
   cd food-test-dataset-cleanin
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the data cleaning script:
   ```bash
   python data_cleaning.py
   ```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.

## License

This project is licensed under the MIT License. 

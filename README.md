# README: ECON1612 - Assessment 3: Empirical Project in Python

## Overview
This project is an individual assignment for the ECON1612 course. It involves analyzing a dataset related to banking using Python. The notebook demonstrates data preprocessing, cleaning, and preparation steps necessary for building a machine learning pipeline.

## Author Information
- **Student Name:** Tran Huong Ly
- **Student ID:** 4000175
- **Class Group:** SGS01

## Dataset
- **Filename:** `bank-additional-full-1.csv`
- **Description:** This dataset contains information related to banking campaigns. The target variable, `y`, indicates whether a customer subscribed to a term deposit.
- **Format:** CSV file with `;` as the delimiter.

## Key Features
1. **Data Loading:**
   - The dataset is read into a pandas DataFrame for analysis.
2. **Data Cleaning:**
   - Removal of unneeded columns to simplify the analysis pipeline.
   - Encoding categorical data (e.g., transforming `yes/no` into binary values).
3. **Data Exploration:**
   - Preliminary exploration using DataFrame operations and visualizations.
4. **Random Seed:**
   - A fixed random seed (4000175, the student ID) ensures reproducibility of results.

## Prerequisites
- Python 3.x
- Required Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - Additional libraries may be imported for specific tasks.

## How to Use
1. **Set Up the Environment:**
   - Ensure Python and the required libraries are installed.
   - Install missing libraries using `pip install <library_name>`.
2. **Run the Notebook:**
   - Open the Jupyter Notebook `S1_2024_Assignment_3.ipynb`.
   - Execute cells sequentially to preprocess, clean, and analyze the dataset.
3. **Modify Parameters:**
   - Update file paths or parameters like `random_state` if running with different datasets or configurations.

## Notes
- Data cleaning and encoding steps use `pandas` methods for simplicity, though `sklearn` tools can be used for advanced pipelines.
- Column operations often use `axis=1` for clarity.
- The notebook assumes the input dataset is in the same directory as the notebook.

## Deliverables
- Processed dataset ready for further analysis.
- Encoded target variable (`y_encoded`) for machine learning models.
- Visualizations and preliminary insights.

## Contact
For any queries related to this assignment, please contact the author through the provided course communication channels.

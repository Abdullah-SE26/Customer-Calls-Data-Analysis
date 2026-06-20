# Customer Calls Data Cleaning Using Python

## Project Overview

This project focuses on cleaning and preparing a customer calls dataset using Python and Pandas. The objective was to transform raw and inconsistent data into a structured, accurate, and analysis-ready dataset.

The project demonstrates essential data cleaning techniques commonly performed by Data Analysts before conducting exploratory analysis, visualization, or building dashboards.

---

## Dataset

The dataset contains customer call records including customer information, contact details, and address-related fields.

The original dataset contained several data quality issues, including:

* Missing values
* Inconsistent text formatting
* Incorrect phone number formats
* Duplicate records
* Combined address fields requiring separation
* Unnecessary columns and formatting inconsistencies

---

## Tools & Technologies

* Python
* Pandas
* Jupyter Notebook (VS Code)

---

## Data Cleaning Process

The following data cleaning steps were performed:

### 1. Data Inspection

* Examined dataset structure using `.info()`, `.describe()`, and `.head()`
* Identified missing values and inconsistent data types

### 2. Handling Missing Values

* Detected and managed missing and invalid values such as `NaN` and `N/A`

### 3. Removing Duplicate Records

* Identified duplicate rows and removed unnecessary duplicate entries

### 4. Standardizing Data Formats

* Cleaned and standardized:

  * Phone number formatting
  * Text capitalization and spacing
  * Inconsistent string values

### 5. Address Transformation

* Split the original address column into separate fields:

  * Street Address
  * State/County
  * Zip Code

### 6. Dataset Preparation

* Removed unnecessary columns
* Reset the index after cleaning
* Exported the final cleaned dataset as a CSV file

---

## Project Structure

```
Customer-Calls-Data-Analysis/
│
├── 01_data_cleaning.ipynb     # Data cleaning notebook
├── cleaned_data.csv           # Final cleaned dataset
├── README.md                  # Project documentation
└── .gitignore                 # Files excluded from Git tracking
```

---

## Final Outcome

The final output is a clean, consistent, and analysis-ready customer calls dataset that can be used for further exploratory data analysis (EDA), visualization, and reporting.

---

## Skills Demonstrated

* Data Cleaning
* Data Wrangling
* Data Quality Assessment
* Missing Value Treatment
* Duplicate Handling
* Data Transformation
* String Manipulation with Pandas
* Data Preparation for Analysis

---

## Author

**Muhammad Abdullah Saleem**


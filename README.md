# House Price Data Cleaning using Pandas

This project focuses on cleaning and preprocessing a real-world house price dataset sourced from Kaggle using Python and Pandas.  
The goal of this project is to transform raw, messy data into a clean and structured format suitable for data analysis and machine learning tasks.

---

## Project Overview

Real estate datasets often contain missing values, inconsistent formats, and mixed data types that make analysis difficult.  
In this project, I performed end-to-end data cleaning, handling issues such as:

- Missing values in numerical and categorical columns  
- Inconsistent text values (e.g., "Covered", "Covered,")  
- Price values stored as strings (e.g., "65 Lac", "2 Cr")  
- Area values with units (e.g., "1250 sqft", "1480 sqf")  
- Removal of irrelevant and redundant columns  

The final output is a clean dataset ready for further analysis or modeling.

---

## Tools & Technologies Used

- Python  
- Pandas  
- NumPy  
- Google Colab  
- Git & GitHub  

---

## 📂 Project Structure
house-price-data-cleaning-pandas/
│
├── data/
│ └── (Dataset not included due to size limitations)
│
├── notebooks/
│ └── house-price-data-cleaning-pandas.ipynb
│
├── scripts/
│ └── house-price-data-cleaning-pandas.py
│
├── README.md
└── .gitignore


---

## 🧹 Data Cleaning Steps Performed

### 1. Handling Missing Values
- Numerical columns were filled using **mean** values.
- Categorical columns were filled using **mode** values.
- Columns with excessive or irrelevant missing data were removed.

### 2. Price Column Cleaning
- Extracted numeric values from strings like `"65 Lac"`, `"54 Cr"`.
- Extracted units (`Lac`, `Cr`) into a separate column.
- Converted all prices into a **single numeric rupees format**.

### 3. Area Column Cleaning
- Cleaned values like `"1250 sqf"`, `"1480 sqft"`.
- Removed text units and converted area columns to numeric type.

### 4. Categorical Data Standardization
- Cleaned inconsistent values such as:
  - `"Covered"` vs `"Covered,"`
- Standardized text formats for consistency.

### 5. Removing Unnecessary Columns
The following columns were dropped as they were not useful for analysis:
- Title
- Description
- Status
- Facing
- Overlooking
- Society
- Ownership

---

## 📊 Final Output

- Cleaned and structured dataset
- Consistent numeric formats
- No unnecessary columns
- Ready for:
  - Exploratory Data Analysis (EDA)
  - Feature engineering
  - Machine learning models

---

## Dataset Information

- Dataset Source: **Kaggle**
- The raw dataset is not included in this repository due to GitHub file size limitations.
- Users can download the dataset directly from Kaggle and place it inside the `data/` folder.

---

## How to Run This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/khanarhamali/house-price-data-cleaning-pandas.git



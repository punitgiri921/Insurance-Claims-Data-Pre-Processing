# Insurance-Claims-Data-Pre-Processing
Data cleaning and preprocessing project built using Python + Pandas, focused on handling messy dummy insurance claim data.

# **Insurance Claims Data Cleaning & EDA Project**

This project walks through **real-world messy data cleaning**, **feature standardization**, and **exploratory analysis** on an insurance claims dataset.

## **🔍 Project Overview**

Insurance companies store claim and customer information in multiple raw data files. These files often contain:

* Mixed date formats
* Inconsistent categorical values
* Duplicate or malformed columns
* Missing values
* Numeric values stored as text
* Misspelled labels
* Format inconsistencies across tables

This project cleans, validates, merges, and analyzes the **customers** and **claims** datasets end-to-end.

---

## **📂 Files in This Repository**

| File                                        | Description                                                                 |
| --------------------------------------------| --------------------------------------------------------------------------- |
| `Insurance_Claims_Data_Preprocessing.ipynb` | Full notebook containing cleaning steps, validations, analysis, and outputs |
| `messy_customers_70.csv`                    | Raw customer data                                                           |
| `messy_claims_70.csv`                       | Raw claims data                                                             |
| `cleaned_claims.csv`                        | Cleaned claim data                                                          |
| `cleaned_customers.csv`                     | Cleaned customer data                                                       |
---

## **🎯 Key Objectives**

1. **Explore & validate raw data**

   * Inspect file structure
   * Check datatypes
   * Identify inconsistent formats
   * Find missing values and anomalies

2. **Clean both datasets**

   * Convert mixed date formats to unified datetime
   * Standardize categorical values
   * Fix duplicate/malformed columns
   * Clean text fields
   * Standardize column names
   * Handle missing values logically

3. **Perform Exploratory Data Analysis (EDA)**

   * Customer segmentation
   * Claims distribution
   * Date-wise claim frequency

4. **Merge datasets** to create a final analysis-ready dataset.

---

## **🛠️ Techniques Demonstrated**

### **✔️ Data Cleaning**

* `pd.to_datetime()` with mixed format handling
* Regex-based text cleaning
* Categorization and type optimization
* Missing value treatment
* Replacing inconsistent labels (“theft”, “Theft”, “THEFT”)
* Fixing date columns with **dayfirst issues**, ambiguous formats, and errors

### **✔️ Exploratory Analysis**

* Frequency distributions
* Groupby aggregations
* Trend analysis
* Outlier inspection
* Identifying claim patterns

### **✔️ Data Validation**

* Shape checks
* Column name audit
* Duplicate detection
* Cross-table consistency checks

---

## **📊 Sample-Data Insights**

* Claim dates were in **four different formats** and required systematic normalization.
* Several categorical fields had **25+ inconsistent labels** due to case sensitivity and spelling issues.
* Claims dataset contained **missing statuses**, requiring logical imputation.
* Customer demographic fields had inconsistent capitalizations and spacing.

---

## **📦 Tech Stack**

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib / Seaborn**
* **Regex (re)**
* **Google Colab **

---


LinkedIn: *<www.linkedin.com/in/punitgiri921>*

---


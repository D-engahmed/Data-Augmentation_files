# ITI Data Analysis Project

This project is part of the **ITI Training Program**, focusing on conducting a comprehensive analysis of a dataset. The primary objectives include identifying duplicates, handling missing values, detecting outliers, and generating essential data insights to support further data processing and modeling tasks.

---

## Dataset Overview

The dataset analyzed in this project contains the following characteristics:

- **Total Samples (Rows)**: 11,914  
- **Features (Columns)**: 16 (prior to feature extraction)  
- **Total Data Points**: 190,624 (rows × columns)  
- **Duplicated Rows**: 715  

---

## Insights and Observations

1. **Null Values**:  
   - **HP**: 69 missing entries  
   - **Cylinders**: 30 missing entries  
   - **Market Category**: 3,742 missing entries  
   - **Total Records with Missing Values**: 3,841  

2. **Outliers**:  
   - The **Number of Doors** feature has been assessed, and no outliers were detected.

3. **Feature Summary**:  
   - The dataset contains 16 features in its raw state, with potential for feature engineering and dimensionality reduction.

---

## Project Workflow

1. **Data Cleaning**:  
   - Removed duplicated rows.  
   - Handled missing values across key features.  

2. **Exploratory Data Analysis (EDA)**:  
   - Conducted statistical analysis and visualized trends to uncover patterns in the data.  

3. **Outlier Detection**:  
   - Verified data consistency to ensure robustness for downstream applications.

4. **Reporting**:  
   - Documented key findings to guide further modeling and analysis efforts.

---

## Project Structure

```plaintext
├── data/                # Raw and processed datasets
├── notebooks/           # Jupyter notebooks for EDA and analysis
├── README.md            # Project documentation

# Erode Traffic Analysis

## Project Overview
This project focuses on traffic data preprocessing and analysis for Erode District.  
The aim is to clean raw traffic data and prepare it for machine learning and data analysis tasks.

---

## Dataset Details

### Raw Dataset
- File: `Erode-Traffic-Analysis uncleaned.csv`
- Description:  
  This file contains the original, unprocessed traffic data collected for Erode District.
- Issues in raw data:
  - Missing values
  - Categorical (text) data
  - Different value ranges

### Preprocessed Dataset
- File: `Erode-Traffic-Analysis preprocessed.csv`
- Description:  
  This file contains the cleaned and transformed version of the raw dataset, ready for analysis and machine learning.

---

## Data Preprocessing Steps
1. Missing values were handled  
   - Numerical columns filled using mean  
   - Categorical columns filled using mode  

2. Categorical features were converted into numerical values using label encoding  

3. Feature scaling was applied using Min-Max normalization to bring all values into a 0–1 range  

---

## Tools and Technologies Used
- Python  
- Pandas  
- Scikit-learn  
- GitHub  

---

## Applications
- Traffic congestion prediction  
- Accident risk analysis  
- Data visualization dashboards  
- Final year academic project  

---

## Conclusion
The preprocessing steps ensure that the dataset is clean, consistent, and suitable for further analysis and machine learning models.

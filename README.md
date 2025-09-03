# Task 1: Data Cleaning and Preprocessing - Netflix Dataset 🎬

## Objective
This task aimed to clean the raw Netflix dataset so that it’s ready for analysis. The raw data had missing values, duplicates, and inconsistent formats, which were fixed step by step.

---

## Tools Used
- Python (Pandas, NumPy)

---

## What I Did
1. Filled in missing values:  
   - Director → marked as "Unknown"  
   - Cast → marked as "Not Available"  
   - Country → marked as "Unknown"  
   - Date added → fixed formatting, converted to datetime, filled in missing with the most frequent date  
   - Rating → filled with the most common rating  
   - Duration → dropped 3 rows where values were missing  

2. Removed duplicate records to keep only unique rows.  

3. Cleaned column names by making them lowercase and replacing spaces with underscores.  

4. Fixed data types:  
   - Converted `date_added` into proper datetime format  
   - Ensured `release_year` is stored as an integer  

---

## Final Deliverables
- **Cleaned Dataset:** `cleaned_netflix.csv`  
- **Code File:** Jupyter Notebook or Python script used for cleaning  
- **Raw Dataset:** Original Netflix dataset  
- **README.md:** This explanation file  

---

## Final Note
After cleaning, the dataset is now consistent, complete, and ready for any analysis or visualization work. This process helped in understanding real-world data problems, such as missing values and formatting issues, and how to handle them effectively.

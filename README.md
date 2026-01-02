# Stack Overflow Survey — Data Cleaning, Imputation, and Salary Normalization

This project performs data cleaning and preprocessing on the Stack Overflow Developer Survey dataset. The notebook focuses on identifying and removing duplicate rows, analyzing and imputing missing values (including forward-fill for the CodingActivities column), and applying Min–Max and Z-score normalization to the ConvertedCompYearly salary column. The normalized salary values are then visualized to compare distribution changes.

## 🧰 Libraries Used
- Python
- Pandas
- Matplotlib

## ✅ Tasks Performed
1. Loaded the dataset into a Pandas DataFrame  
2. Identified and removed duplicate rows  
3. Counted and analyzed missing values across columns  
4. Imputed missing values in `CodingActivities` using forward-fill  
5. Identified the `ConvertedCompYearly` compensation column  
6. Applied Min–Max normalization and created `ConvertedCompYearly_MinMax`  
7. Applied Z-score normalization and created `ConvertedCompYearly_Zscore`  
8. Visualized salary values before and after normalization

## ▶️ How to Run
1. Open the notebook in Jupyter or JupyterLab  
2. Install dependencies if needed:
3. Run the cells step-by-step

## 🎯 Project Focus
This project is limited to:
- duplicate handling  
- missing-value analysis and imputation  
- salary normalization and visualization

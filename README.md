# Week 1 – Data Acquisition, Cleaning, and Preprocessing

## Project
Data acquisition, data-quality assessment, cleaning, and preprocessing using Python.

## Dataset
Uploaded dataset: `437a054e-1438-4f79-ac55-47a28de08f0b.csv`  
Rows: 10,194 after cleaning  
Columns: 24

## Files
- `Week_1_Data_Cleaning.ipynb` – complete executable notebook
- `data/raw_dataset.csv` – original uploaded data
- `data/cleaned_dataset.csv` – cleaned output
- `visualizations/` – generated quality/distribution plots
- `requirements.txt` – Python dependencies

## Main Steps
1. Load dataset
2. Inspect shape, types, and descriptive statistics
3. Analyze missing values
4. Remove exact duplicates
5. Standardize column names and text values
6. Impute missing numeric/categorical values
7. Detect outliers using IQR
8. Review numeric distributions
9. Perform final quality checks
10. Export cleaned dataset

## Run
```bash
pip install -r requirements.txt
jupyter notebook Week_1_Data_Cleaning.ipynb
```

## Note
The notebook intentionally reports outliers rather than automatically deleting them, because extreme observations may be valid records. Domain-specific decisions can be added after inspection.

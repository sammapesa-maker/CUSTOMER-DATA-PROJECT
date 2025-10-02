# Customer Data Cleaning & Exploration Project

This project demonstrates a complete workflow for exploring and cleaning customer data. It includes raw and cleaned datasets, Jupyter notebooks for data analysis and cleaning, and generated reports in both PDF and HTML formats.

---

## Project Structure

```

.
├── data/         # Contains raw and cleaned datasets
├── notebooks/    # Jupyter notebooks for data exploration, cleaning, and reporting
└── reports/      # Generated reports documenting the project

````

---

## Folder Overview

### 1. `data/`
- Stores all dataset files.  
- `raw/` → Original datasets, kept unchanged as the source of truth.  
- `cleaned/` → Cleaned and processed datasets ready for analysis.

### 2. `notebooks/`
- Contains Jupyter notebooks used to:
  - Explore raw data
  - Clean datasets
  - Generate reports
- Examples:
  - `raw_data_exploration.ipynb`
  - `data_cleaning.ipynb`
  - `data_cleaning_report.ipynb`

### 3. `reports/`
- Contains generated reports in PDF and HTML format:
  - `raw_data_exploration` → Summary of the raw data analysis
  - `data_cleaning_report` → Documentation of the cleaning process
- Reports are suitable for sharing, presentation, or documentation purposes.

---

## How to Use

1. Clone the repository:
```bash
git clone <repository_url>
````

2. Navigate to the project folder:

```bash
cd <project_folder>
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open and run notebooks from the `notebooks/` folder or view reports in `reports/`.

---

## Dependencies

* Python 3.x
* Pandas
* NumPy
* phonenumbers
* Jupyter Notebook
* Matplotlib / Seaborn (optional for visualizations)

---

## Workflow Summary

1. Start with the raw dataset in `data/raw/`.
2. Explore and understand the data using notebooks in `notebooks/`.
3. Clean and standardize the data (handling missing values, duplicates, phone formats, dates, and text capitalization).
4. Save the cleaned data to `data/cleaned/`.
5. Generate reports in `reports/` to document your analysis and cleaning process.

This structured workflow ensures reproducibility, clarity, and high-quality data ready for analysis.


# Data Folder

This folder contains all datasets used in the project, organized into raw and cleaned versions.

---

## Folder Structure

data/
├── raw/         # Original, unprocessed datasets
│    └── customers.csv
└── cleaned/     # Cleaned and processed datasets ready for analysis
     ├── clean_customer_data.csv
     └── clean_customer_data.xlsx

---

## Description

- **raw/** → Contains the original datasets as obtained. These files should never be modified directly, as they serve as the source of truth.  
- **cleaned/** → Contains datasets that have been processed, cleaned, and standardized. These are ready for analysis, reporting, or export.

---

## Guidelines

- Always start any cleaning or analysis workflow using the datasets in **raw/**.  
- Use **cleaned/** datasets for downstream tasks such as data analysis, visualization, or modeling.  
- Keep track of any transformations or cleaning steps applied to ensure reproducibility.  
- Do not overwrite raw data files; always save cleaned versions in the `cleaned/` folder.


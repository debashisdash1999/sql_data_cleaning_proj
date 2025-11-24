# SQL Data Cleaning Project – World Layoffs Dataset

## 📌 Overview
This project focuses on **data cleaning using MySQL**, working with a real-world dataset containing global company layoffs. The dataset includes details such as company names, locations, industries, number of layoffs, percentage laid off, funding raised, and more.

The goal of this project is to clean, standardize, and prepare the dataset for future analysis. This includes handling missing values, fixing inconsistent formatting, correcting invalid entries, and ensuring all columns are in the proper structure for reporting and analytics.

---

## 📂 Dataset Source
An Excel file (`layoffs.xlsx`) containing worldwide layoff records was imported into MySQL using the **Table Data Import Wizard**.

### Columns in the dataset:
- `company`
- `location`
- `industry`
- `total_laid_off`
- `percentage_laid_off`
- `date`
- `stage`
- `country`
- `funds_raised_millions`

No column types were modified during import.  
All cleaning and transformations were performed inside MySQL.

---

## 🛠️ Steps Performed in the Project

### **1. Database Creation**
A new database named **`world_layoffs`** was created to manage and store the dataset.
```sql
CREATE DATABASE world_layoffs;
```

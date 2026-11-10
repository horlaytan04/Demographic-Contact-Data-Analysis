# Demographic & Contact Data Analysis | Power BI Dashboard

## Dashboard Preview
![Overview] (screenshots/page1_gender.png)
![Email Domain] (screenshots/page2_email.png)
![Names] (screenshots/page3_names.png)

## Project Overview

This project focuses on analyzing demographic and contact information using Microsoft Excel and Power BI.

The objective is to clean, organize, transform, and analyze a mock dataset to identify demographic patterns, understand gender distribution, and examine email domain information through data visualization.

## Tools Used

- **Microsoft Excel:** Data inspection, cleaning, validation, and preparation.
- **Microsoft Power BI:** Data import, analysis, visualization, and dashboard development.

## Dataset Description

The project uses a mock dataset containing demographic and contact-related information.

The dataset includes information such as:
- Gender
- Email addresses
- Email domains
- Other demographic and contact attributes available in the source dataset.

## Project Workflow

### 1. Data Import and Inspection
- Imported the original dataset into Microsoft Excel.
- Examined the dataset structure, columns, and data types.
- Reviewed the records to understand the available demographic and contact information.

### 2. Data Cleaning in Excel
The following data quality checks and preparation activities were performed:

- Checked for missing or blank values.
- Checked for duplicate records.
- Reviewed gender categories for consistency.
- Created an `email_domain` column to extract domain information from email addresses.
- Validated the prepared dataset before using it for analysis.

**Data Quality Check:** No blank values or duplicate records were identified during the completed checks.

### 3. Data Import into Power BI
- Imported the prepared dataset into Power BI.
- Reviewed the imported fields.
- Prepared the data for analysis and visualization.

### 4. Data Analysis and Visualization
Developed a Power BI dashboard to explore the demographic and contact information.

The analysis focused on:
- Gender distribution.
- Demographic patterns.
- Email domain distribution.
- Contact information analysis.

### 5. Dashboard Development
Created visual representations of the dataset to make demographic and contact information easier to understand and interpret.

## Key Insights & Findings

**Dataset Overview:**
1,000 Total Records | 1,000 Unique IDs | 1,000 Unique Emails | 1,000 Unique IP Addresses -100% unique, zero duplicates

**Gender Demographic (Core Analysis):**
- Female: 467 (46.7%) - Largest segment
- Male: 438 (43.8%)
- Diverse identities: Genderfluid 22 (2.2%), Agender 15, Bigender 15, Polygender 15, Genderqueer 14, Non-binary 14
- Insight: Balanced gender distribution with inclusive categories, ideal for diversity reporting

  **Email & Identity Analysis:**
- Email Domains: Highly diverse global set - top domains (gno.gl, spiegel.de, zimbio.com) only 7 each (0.7%)
- Name Uniqueness: Most common first names (Hoyt, Kirbee, Winnie) appear only 3 times, last names only 2 times - confirms high data quality

**Technical Achievement:**
- Built interactive slicers for gender & email_domain filtering
- KPI cards for instant data quality validation
- Clean dataset suitable for banking KYC / customer segmentation demos

## Key Skills Demonstrated

- Data Cleaning and Preparation
- Data Quality Validation
- Excel Data Analysis
- Data Transformation
- Power BI Data Visualization
- Dashboard Development
- Analytical Thinking
- Data Interpretation

## Project Files

| File | Description |
|---|---|
| `MOCK_DATA Analysis.pbix` | Power BI analysis and dashboard file |
| `README.md` | Project documentation |

## Conclusion

This project demonstrates an end-to-end data analysis workflow, from initial data inspection and cleaning in Microsoft Excel to analysis and dashboard development in Power BI.

It highlights the importance of data quality, structured preparation, and effective visualization in transforming raw data into meaningful analytical information.

---

**Tools:** Microsoft Excel | Microsoft Power BI

**Project:** Demographic & Contact Data Analysis

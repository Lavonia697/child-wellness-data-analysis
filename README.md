# Child Wellness Data Portfolio

**Prepared by:** Lavonia Munedzimwe  
**Role Focus:** Data Entry Specialist | Junior Data Analyst  

---

## Project Overview
This project analyses child health, well-being, and school performance data collected from multiple sources including schools, clinics, and community programs.

The goal is to demonstrate strong data entry practices, data cleaning, and exploratory analysis using Microsoft Excel, with a focus on producing accurate, decision-ready insights for NGO and public-sector stakeholders.

---

## Tools Used
- Microsoft Excel
  - Data validation
  - Data cleaning
  - Pivot Tables
  - Pivot Charts
- PowerPoint (reporting)
- GitHub (version control & documentation)

---

## Project Structure
- **Raw data:** Original dataset as received
- **Cleaned data:** Standardised, validated, and corrected dataset
- **Modified data:** To derive and populate new calculation-specific columns (age group, attendance category, checkup status)
- **Processed data:** Analysis-ready dataset used for visualisations
- **Visuals:** Key charts exported from Excel
- **Portfolio:** Final presentation and PDF summary

---

## Key Analysis Areas
- Attendance rates and well-being outcomes
- Data integrity through completeness
- Health checkup coverage
- Correlations between attendance, performance, and well-being

---

## Notes
This project was intentionally completed using an Excel-only workflow to reflect common NGO and operational environments where Python or SQL may not always be available.

---
## Data Workflow

The project follows a structured, Excel-based data workflow designed to reflect real-world NGO and operational reporting environments.

### 1. Raw Data
- Original dataset as received
- No transformations applied

### 2. Cleaned Data
- Removal of duplicates
- Standardised date and percentage formats
- Addressed missing values using appropriate methods
- Corrected inconsistencies across records

### 3. Modified Data (Feature Engineering)
- Created analytical fields to support segmentation and comparison:
  - Age Group categories
  - Attendance rate bands
  - Health checkup status indicators

### 4. Processed Data
- Final analysis-ready dataset
- Used to create pivot tables, pivot charts, and visual insights

  ---

  # Methodology

## Data Sources
The dataset consolidates child-level information collected from schools, healthcare interactions, and community wellbeing assessments.

---

## Data Preparation Process

### Raw Data Review
- Verified column completeness
- Identified missing values and inconsistencies
- Reviewed data types and formats

### Data Cleaning
- Removed duplicate and invalid records
- Standardised attendance rates as percentages
- Applied International-standard date formatting (YYYY/MM/DD)
- Handled missing values using:
  - Median imputation for numeric wellbeing indicators
  - Row removal where critical identifiers were missing
  - Retention of missing dates where absence itself was informative

### Data Modification (Feature Engineering)
Additional analytical fields were created to improve interpretability:
- **Age_Group:** Categorised age bands for comparison
- **Attendance_Category:** Grouped attendance levels (Low / Medium / High)
- **Checkup_Status:** Indicator of Checkup Completed and Not Completed

### Data Processing
- Created pivot tables for aggregation
- Generated pivot charts for exploratory analysis
- Prepared final datasets for reporting

---

## Limitations
- Some health checkup dates were unavailable due to reporting gaps
- 55% of Well-being scores were missing values making data imputation inappropriate 

---

## Ethical Considerations
- All personal identifiers were anonymised
- Data used strictly for demonstration and portfolio purposes

---

# Insights & Recommendations

## Key Insights

### Attendance & Wellbeing
Higher attendance rates are generally associated with higher well-being scores, although variability suggests additional influencing factors beyond attendance alone.

### Data Completeness & Reporting Gaps
A notable proportion of records contain missing values for key fields such as well-being scores and health checkup dates. These gaps limit certain analyses but also highlight inconsistencies in data collection practices, emphasizing the need for improved standardisation and reporting processes.

### Health Access
A substantial proportion of children lack recent health checkups, which may delay early identification of physical or psychological concerns.

---

## Recommendations

1. Strengthen attendance monitoring to support early intervention
2. Expand school-based wellbeing and mental health support programmes
3. Improve access to routine health checkups
4. Standardise data collection practices across institutions
5. Conduct periodic data quality audits to improve reporting reliability



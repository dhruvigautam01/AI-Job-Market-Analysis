# AI Job Market Analysis

> **Project status:** In progress\
> **Current phase:** Phase 1 --- Exploratory Data Analysis in Microsoft
> Excel

## Project Overview

This project explores an AI job-market dataset to investigate
job-posting patterns, salary information, company hiring activity, and
the geographical distribution of AI-related opportunities.

The project is being developed in phases. It begins with exploratory
analysis in Excel and will expand to SQL, Python, and Power BI. The goal
is to practice the full analytical workflow: asking useful questions,
examining data, validating findings, interpreting limitations, and
communicating results clearly.

## Project Objectives

-   Identify job categories with the highest number of job postings.
-   Compare average recorded salaries across job categories.
-   Identify companies with the highest number of postings in the
    dataset.
-   Compare the number of AI-related job postings across countries.
-   Continue investigating the dataset to discover additional meaningful
    patterns.
-   Revisit and validate findings using other tools where appropriate.

## Dataset

The dataset contains job-posting information, including fields such as
job title, company, category, location, country, contract type, salary
range, posting date, and whether a posting is AI-related.

The working dataset contains approximately 1,696 job records. The exact
usable record count may depend on the dataset version and any cleaning
or filtering applied.

**Data note:** Check the dataset's source and sharing permissions before
distributing it publicly. Do not include confidential, private, or
restricted data in this repository.

## Tools and Skills

### Phase 1 --- Microsoft Excel *(in progress)*

-   Data exploration
-   PivotTables and aggregations
-   Comparing job-posting counts
-   Comparing average recorded salaries
-   Documenting findings and data limitations

### Phase 2 --- SQL *(planned)*

-   Querying the dataset
-   Filtering, grouping, and aggregating records
-   Investigating additional questions with SQL
-   Comparing relevant results with the Excel analysis

### Phase 3 --- Python *(planned)*

-   Using Pandas and NumPy for data analysis
-   Exploring distributions and missing values
-   Creating visualizations with Matplotlib and, where useful, Seaborn
-   Checking and extending findings from earlier phases

### Phase 4 --- Power BI *(planned)*

-   Building an interactive dashboard
-   Creating useful KPIs and visualizations
-   Adding slicers and filters to support exploration

### Phase 5 --- Final Insights and Validation *(planned)*

-   Comparing findings across tools
-   Summarizing important patterns
-   Documenting assumptions and limitations
-   Preparing final conclusions supported by the data

### Phase 6 --- Portfolio Documentation *(planned)*

-   Organizing project files
-   Adding screenshots and visualizations
-   Updating this README as the project progresses
-   Presenting the completed workflow and findings clearly

## Initial Research Questions and Findings

These are preliminary findings from the current Excel analysis. They
describe the records in this dataset and should not automatically be
interpreted as representing the entire job market.

### 1. Which job categories have the highest number of postings?

The initial PivotTable identified **IT Jobs** as the category with the
highest number of postings in the dataset, with **695 postings**.

### 2. Which job category has the highest average recorded salary?

The initial analysis identified **Consultancy Jobs** as having the
highest average recorded salary among the categories. Of the five
consultancy postings observed, only three had salary values recorded.
This comparison is therefore based on a limited number of available
salary records and may not represent the wider consultancy job market.

### 3. Which companies have the highest number of job postings?

**Bespoke** had the highest count in the company PivotTable, with **112
postings**, followed by **EE** with 111 and **Maximus** with 71.

### 4. Which countries have the highest number of AI-related job postings?

With the PivotTable filtered to AI-related postings, the counts were:

-   **United States (US):** 449
-   **United Kingdom (GB):** 405
-   **India (IN):** 167

These counts describe the dataset and do not necessarily represent the
total number of AI-related vacancies in each country.

## Data Limitations

-   Some job postings have missing salary information.
-   Average salary comparisons are based on records with available
    salary values; missing values should not be treated as zero.
-   A high number of postings in the dataset does not necessarily
    indicate the largest employer or the best employer.
-   The dataset may not represent every vacancy or the entire job market
    in a country or category.
-   Findings may change as data cleaning, validation, or further
    analysis is performed.

## Planned Repository Structure

The repository will grow as the project progresses. The intended
structure is:

``` text
AI-Job-Market-Analysis/
├── README.md
├── data/           # Dataset, only if sharing is permitted
├── analysis/       # Excel workbook and later analysis files
├── sql/            # SQL queries (planned)
├── python/         # Python scripts or notebooks (planned)
├── powerbi/        # Power BI project/dashboard files (planned)
└── screenshots/    # Selected charts and project visuals
```

Folders and files will be added as they are created; this outline does
not mean those files already exist.

## Current Status

Phase 1 is underway. Four questions have been explored in Excel:

1.  Job-posting counts by category
2.  Average recorded salary by category
3.  Job-posting counts by company
4.  AI-related job-posting counts by country

Additional questions will be investigated before moving to the next
phase.

## Project Updates

This README will be updated as new analyses, SQL queries, Python work,
visualizations, and conclusions are added. The aim is to keep the
process transparent and distinguish preliminary findings from results
validated across tools.


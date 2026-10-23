# Netflix Content Intelligence Dashboard

An interactive Power BI dashboard for exploring Netflix's content catalog through content type, release year, IMDb ratings, runtime, and age certification.

## Project Overview

This project analyzes Netflix's content catalog to understand its composition and explore patterns across release years, content types, ratings, and age-certification categories. The dashboard presents key metrics and visualizations to make the data easier to explore and interpret.

## Business Objectives

- Analyze the distribution of Movies and TV Shows.
- Explore content distribution across release years.
- Examine IMDb ratings across different release years.
- Analyze runtime patterns in the catalog.
- Compare average IMDb scores across age-certification categories.

## Tools & Technologies

- **Power BI Desktop:** Dashboard development and data visualization
- **Power Query:** Data preparation and transformation
- **Data Analytics:** Exploratory analysis, KPI reporting, and insight generation

## Dataset Overview

- **Number of titles:** 5,267
- **Key attributes:** Title, Content Type, Release Year, IMDb Score, Runtime, and Age Certification

The dataset provides information about Netflix titles and supports analysis of content distribution, ratings, and runtime patterns.

## Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Titles | 5,267 |
| Average Runtime | 79.31 minutes |
| Average IMDb Score | 6.53 |
| Movies Share | 64.38% |

## Key Findings

**1. Content Type Distribution**

Movies account for approximately 64.38% of the catalog, representing a larger share than TV Shows.

**2. Release-Year Analysis**

The dashboard explores how titles are distributed across release years to identify patterns in the catalog.

**3. IMDb Rating Analysis**

IMDb ratings are examined across release years to explore changes and differences in average scores.

**4. Runtime Analysis**

The dashboard analyzes runtime to understand the distribution of content duration across the catalog.

**5. Age Certification Analysis**

Average IMDb scores are compared across age-certification categories to identify differences between groups.

## Business Insights

- **Content Mix:** Movies represent the larger share of the analyzed catalog.
- **Catalog Composition:** Release-year analysis helps explore how the dataset is distributed over time.
- **Rating Patterns:** Comparing IMDb scores across categories helps identify areas for further investigation.
- **Runtime Patterns:** Runtime analysis provides an overview of content duration within the catalog.

These observations describe the available dataset and do not establish viewer preferences or explain the causes of rating differences.

## Limitations & Future Scope

- IMDb scores represent one rating source and may not reflect Netflix viewers' preferences.
- Findings are limited to the information available in the dataset.
- The 5,267 titles exclude entries with no IMDb vote count (16 of 5,283 in the source file). About 43% of titles have no age certification, so that comparison covers only the rated titles.
- Further analysis could examine Movies and TV Shows separately and compare additional rating sources.

## How to Open the Project

1. Download `netflix pb 0910.pbix` from this repository.
2. Open the file in Power BI Desktop.
3. Explore the dashboard and its visualizations.

## Author

**Sukanya Saha**

PhD Research Scholar, CSIR–IICT Hyderabad  
M.Sc. Chemistry, IIT Madras

- [LinkedIn](https://www.linkedin.com/in/sukanya-saha-921a20295)
- [GitHub](https://github.com/iitsukanya-hash)
- [Portfolio](https://sukanya-portfolio-rust.vercel.app/)

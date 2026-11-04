# Week 1 | Data Collection, Exploration and Cleaning in Agribusiness

### Establishing a Reliable Data Foundation for Agricultural Market Analysis

![Internship](https://img.shields.io/badge/Internship-Yuva%20Intern-green)
![Domain](https://img.shields.io/badge/Domain-Agribusiness-blue)
![Focus](https://img.shields.io/badge/Focus-Data%20Analytics-purple)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 1. Project Overview

This project focuses on the systematic collection, exploration, and quality assessment of agricultural datasets to establish a reliable foundation for data-driven analysis in the agribusiness sector.

The study examines agricultural market-price information, with particular emphasis on understanding commodity representation, geographical coverage, price distributions, and data-quality characteristics.

The project also establishes a reproducible methodology for identifying credible public data sources, inspecting dataset structures, applying validation rules, and documenting data-preparation procedures.

The primary objective is to ensure that agricultural data are sufficiently consistent, interpretable, and reliable before being used for advanced statistical analysis or predictive modelling.

## 2. Project Objectives

- Identify credible public sources of agricultural and market-related information.
- Examine the structure and characteristics of agricultural datasets.
- Analyse commodity representation and geographical coverage.
- Explore minimum, maximum, and modal market-price distributions.
- Identify missing values, duplicate records, and potential data inconsistencies.
- Establish systematic data-cleaning and validation procedures.
- Document limitations affecting the reliability and interpretation of agricultural data.

## 3. Data Sources

| Data Source | Intended Application |
|---|---|
| Government Open Data Platform (OGD) | Agricultural and crop-production datasets |
| AGMARKNET / OGD Mandi Price Catalogue | Wholesale agricultural market prices |
| FAOSTAT | National and international agricultural statistics |
| India Meteorological Department (IMD) | Weather and climate information |

The supplied mandi-price dataset forms the basis of the completed exploratory analysis. Other sources are identified as candidates for further agricultural analysis and are not represented as datasets already integrated into the study.

## 4. Dataset Overview

The working dataset, `Task1_DataSet.csv`, contains:

| Attribute | Description |
|---|---|
| Total records | 11,215 |
| Total columns | 10 |
| States / regional labels | 26 |
| Districts | 333 |
| Markets | 995 |
| Commodities | 197 |
| Varieties | 365 |
| Grades | 13 |
| Distinct arrival dates | 1 |

**Principal Variables:**

- State
- District
- Market
- Commodity
- Variety
- Grade
- Arrival_Date
- Min_Price
- Max_Price
- Modal_Price

The dataset represents a single-day market snapshot dated 26 October 2026. Consequently, the analysis focuses on cross-sectional comparisons rather than historical price movements.

## 5. Exploratory Data Analysis

The exploratory analysis examines the structure, distribution, and composition of the agricultural market-price dataset.

The principal analytical areas include:

- Commodity-wise record distribution.
- Geographical distribution of agricultural market observations.
- Minimum, maximum, and modal-price summaries.
- Modal-price distribution and potential extreme observations.
- Dataset completeness and structural consistency.

Four charts were regenerated using the supplied dataset to support the descriptive analysis.

## 6. Data Quality Assessment

The following checks were performed on the supplied dataset:

| Quality Indicator | Verified Result |
|---|---:|
| Missing cells | 0 |
| Exact duplicate rows | 0 |
| Records where minimum price exceeds maximum price | 0 |
| Records where modal price falls outside the minimum–maximum range | 0 |

These checks establish that the tested structural and numerical conditions were satisfied. They do not independently guarantee that every source observation is error-free.

## 7. Key Analytical Findings

### Commodity Representation

The most frequently represented commodities were:

| Commodity | Number of Records |
|---|---:|
| Brinjal | 376 |
| Tomato | 370 |
| Onion | 343 |
| Bhindi (Ladies Finger) | 327 |
| Potato | 308 |

These figures represent record frequency within the supplied dataset, not agricultural production or consumption volumes.

### Geographical Concentration

Tamil Nadu contributed 6,740 records, representing approximately 60.1% of the dataset.

This indicates substantial geographical concentration and highlights the importance of examining coverage before making broader comparisons.

### Modal-Price Distribution

The mean modal price was 5,608.47, while the median was 4,200.00 in source-reported price units.

The difference indicates a right-skewed distribution in which higher observations influence the arithmetic mean.

## 8. Data Collection and Cleaning Methodology

The project establishes a structured data-preparation workflow:

1. Identify suitable agricultural data sources.
2. Verify source metadata, geographical coverage, and measurement units.
3. Preserve original datasets and document retrieval information.
4. Inspect dataset structure, variable types, and descriptive statistics.
5. Identify missing values, duplicate records, and suspicious observations.
6. Standardise data types, labels, dates, and measurement units where required.
7. Validate numerical relationships and dataset consistency.
8. Document transformations, limitations, and analytical outputs.

## 9. Limitations

The principal limitation is that all 11,215 observations share a single arrival date.

Therefore, the dataset cannot independently establish:

- Historical agricultural price trends.
- Seasonal price movements.
- Long-term market volatility.
- Rainfall-versus-crop-yield relationships.

Additional compatible historical agricultural and meteorological datasets would be required for these analyses.

## 10. Project Deliverables

| Deliverable | Description |
|---|---|
| Dataset | Agricultural mandi-price CSV |
| Source Inventory | Identification of public agricultural data sources |
| Exploratory Analysis | Descriptive dataset examination |
| Visualizations | Four regenerated analytical charts |
| Data Quality Assessment | Missing-value and consistency checks |
| Cleaning Methodology | Documented preparation and validation workflow |
| Project Report | Detailed methodology, findings, limitations, and recommendations |

## 11. Project Status

**Phase:** Data Collection, Exploration and Quality Assessment

**Estimated Project Effort:** 32 hours.

The project establishes an initial analytical understanding of agricultural market-price data and documents the procedures required to prepare reliable datasets for subsequent analytical activities.

## 12. Key Areas of Learning

- Agricultural Data Acquisition
- Exploratory Data Analysis (EDA)
- Data Quality Assessment
- Descriptive Statistics
- Data Validation
- Data Cleaning Methodologies
- Data Visualization
- Agricultural Market Analysis

---

**Internship:** Yuva Intern – Junior Data Analyst (Agribusiness)  
**Project:** Week 1 – Data Collection, Exploration and Cleaning  
**Domain:** Agribusiness and Data Analytics

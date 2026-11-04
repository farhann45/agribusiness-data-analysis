# Week 2 | Data Visualization and Reporting in Agribusiness

### Transforming Agricultural Market Data into Meaningful Analytical Insights

![Internship](https://img.shields.io/badge/Internship-Yuva%20Intern-green)
![Domain](https://img.shields.io/badge/Domain-Agribusiness-blue)
![Focus](https://img.shields.io/badge/Focus-Data%20Visualization-purple)
![Status](https://img.shields.io/badge/Status-Analysis%20%26%20Reporting-brightgreen)

---

## 1. Project Overview

This project focuses on developing a structured visualization and reporting framework for agricultural market-price information.

Building upon the dataset exploration conducted during Week 1, the project examines how agricultural data can be transformed into meaningful visual representations that improve interpretation, comparison, and communication of market information.

The study uses descriptive statistics, graphical analysis, and dashboard-planning methodologies to examine commodity representation, geographical coverage, modal-price distributions, and data-quality indicators.

The primary objective is to establish a professional reporting approach that communicates analytical findings accurately while distinguishing observed patterns from unsupported assumptions.

## 2. Project Objectives

- Identify appropriate visualization techniques for agricultural market data.
- Examine commodity-wise and geographical record distributions.
- Compare modal-price statistics across agricultural commodities.
- Analyse price distributions and identify observations requiring further investigation.
- Develop a structured dashboard concept for agricultural market analysis.
- Establish visualization standards and reporting guidelines.
- Communicate analytical findings through evidence-based interpretations.

## 3. Dataset Overview

The project uses `Task1_DataSet.csv`, containing 11,215 observations and 10 variables.

| Attribute | Description |
|---|---|
| Records | 11,215 |
| Columns | 10 |
| States / regional labels | 26 |
| Districts | 333 |
| State–District–Market combinations | 995 |
| Commodities | 197 |
| Varieties | 365 |
| Grades | 13 |
| Arrival-date coverage | 26 October 2026 |

The dataset contains agricultural market-price information, including minimum, maximum, and modal prices.

**Important Data Limitation:** All observations belong to one arrival date. Therefore, the dataset supports cross-sectional comparisons but cannot establish historical price trends or seasonal movements.

## 4. Visualization Strategy

The project develops a visualization framework based on specific analytical requirements.

| Visualization | Analytical Purpose |
|---|---|
| Horizontal Bar Chart | Compare commodity record frequencies |
| Ranked Bar Chart | Compare mean modal prices across commodities |
| Histogram | Examine modal-price distributions and skewness |
| Box Plot | Identify price spread and potential extreme observations |
| Geographic Summary | Examine the distribution of records across states |
| Dashboard Components | Present key indicators, filters, and data-quality information |

Each visualization is designed to communicate a specific analytical observation rather than simply display data.

## 5. Actual Dataset Analysis

The supplied dataset was examined to generate descriptive statistics and analytical visualizations.

### Commodity Representation

The most frequently represented commodities were:

| Commodity | Records |
|---|---:|
| Brinjal | 376 |
| Tomato | 370 |
| Onion | 343 |
| Bhindi (Ladies Finger) | 327 |
| Potato | 308 |

Brinjal had the highest record frequency in the supplied dataset. This indicates its representation within the file, not its production volume or market demand.

### Geographical Distribution

Tamil Nadu contributed 6,740 observations, representing approximately 60.1% of the dataset.

This concentration indicates that aggregate visualizations may be strongly influenced by the geographical composition of the available records.

### Modal-Price Distribution

| Statistical Measure | Modal Price |
|---|---:|
| Mean | 5,608.47 |
| Median | 4,200.00 |
| First Quartile | 2,800.00 |
| Third Quartile | 6,500.00 |

The mean being higher than the median indicates a right-skewed distribution.

The analysis also identified 719 observations (approximately 6.4%) outside the global interquartile-range screening fences. These observations require further commodity-specific and market-specific investigation; they should not automatically be treated as errors.

*Prices are presented in source-reported units. The unit definition should be verified from source metadata before external comparisons.*

## 6. Data Quality and Validation

The following checks were performed:

| Validation Check | Result |
|---|---:|
| Missing cells | 0 |
| Exact duplicate rows | 0 |
| Duplicate business keys | 0 |
| Negative-price records | 0 |
| Invalid minimum–modal–maximum price ordering | 0 |
| Unparsed arrival dates | 0 |

These checks support the reliability of the tested dataset structure while leaving room for further source-level and domain-specific validation.

## 7. Dashboard Design and Reporting Framework

The project proposes a dashboard structure for presenting agricultural market information.

The proposed components include:

- **Header and Scope:** Report title, data source, extraction date, and observation period.
- **KPI Cards:** Total records, unique markets, commodities, arrival dates, and missing-price counts.
- **Commodity Analysis:** Record frequency and mean or median modal-price comparisons.
- **Geographical Analysis:** State, district, and market-level coverage.
- **Price Distribution:** Histograms and box plots for examining price variability.
- **Data Quality Panel:** Missing values, duplicate candidates, and invalid price checks.
- **Interactive Filters:** State, district, market, commodity, variety, and grade.

The dashboard is a proposed reporting design, not a claim that a fully deployed interactive dashboard has been implemented.

## 8. Analytical Interpretation Principles

The reporting methodology emphasizes:

1. Selecting charts according to the analytical question.
2. Including appropriate titles, labels, legends, and measurement units.
3. Displaying sample sizes alongside group comparisons.
4. Distinguishing record frequency from production or sales volume.
5. Investigating unusual values before classifying them as errors.
6. Clearly documenting limitations and avoiding unsupported conclusions.
7. Ensuring that visual outputs can be traced back to the source dataset.

## 9. Key Findings and Recommendations

The analysis establishes that:

- Brinjal is the most frequently represented commodity in the supplied extract.
- Tamil Nadu accounts for approximately 60.1% of the records.
- The modal-price distribution exhibits a right tail.
- The dataset passes the reported missing-value, duplicate, and price-order checks.
- A single-date dataset cannot support historical price-trend analysis.

### Recommended Next Steps

- Develop commodity-specific price-distribution comparisons.
- Include geographical filters in the proposed dashboard.
- Retain sample sizes and data-quality indicators in visual reports.
- Acquire multi-date historical data before attempting time-series analysis.
- Preserve the original CSV, analytical code, and generated visualizations for reproducibility.

## 10. Project Deliverables

| Deliverable | Description |
|---|---|
| Visualization Strategy | Selection of charts based on analytical objectives |
| Dataset Analysis | Descriptive statistics and market-data examination |
| Analytical Charts | Four additional visualizations |
| Dashboard Storyboard | Proposed dashboard layout and components |
| Validation Framework | Dataset and visualization quality checks |
| Python Implementation | Code for dataset auditing and visualization |
| Reporting Document | Detailed findings, interpretation, and recommendations |

## 11. Project Status

**Phase:** Data Visualization, Analytical Interpretation and Reporting

**Estimated Project Effort:** 28 hours.

The project combines actual descriptive analysis of the supplied agricultural dataset with a structured visualization and dashboard-planning framework.

It establishes a reporting foundation for communicating agricultural market information and prepares the analytical workflow for future predictive modelling activities.

## 12. Key Areas of Learning

- Data Visualization
- Exploratory Data Analysis
- Descriptive Statistics
- Agricultural Market Analysis
- Python-Based Data Analysis
- Analytical Reporting
- Dashboard Planning
- Data Quality Validation
- Evidence-Based Interpretation

---

**Internship:** Yuva Intern – Junior Data Analyst (Agribusiness)  
**Project:** Week 2 – Data Visualization and Reporting  
**Domain:** Agribusiness and Data Analytics

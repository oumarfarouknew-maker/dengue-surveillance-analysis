# 🦟 Dengue Surveillance Analysis Dashboard

## Global Epidemiological Analysis of Dengue Cases, Severity, and Mortality

[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)](https://powerbi.microsoft.com/)
[![Domain](https://img.shields.io/badge/Domain-Epidemiology%20%7C%20Public%20Health-blue)](#)
[![Data Analytics](https://img.shields.io/badge/Focus-Health%20Data%20Analytics-green)](#)
[![Status](https://img.shields.io/badge/Project-Completed-brightgreen)](#)

---

## 📌 Project Overview

The **Dengue Surveillance Analysis Dashboard** is an epidemiological data analytics project designed to analyze the global burden, geographic distribution, severity, and mortality associated with dengue.

The project transforms dengue surveillance data into an interactive **Microsoft Power BI dashboard**, enabling users to explore key epidemiological indicators across countries and WHO regions.

The dashboard provides a multidimensional view of dengue through:

* Total reported cases
* Confirmed cases
* Severe cases
* Severe case rate
* Deaths
* Case-fatality rate (CFR)
* Geographic distribution
* Regional comparisons
* Epidemiological patterns

The project demonstrates the integration of **epidemiology, health data analytics, data visualization, and business intelligence** to support public health decision-making.

---

# 🎯 Project Objectives

### General Objective

To develop an interactive epidemiological dashboard for analyzing the global distribution, severity, and mortality of dengue disease.

### Specific Objectives

* Quantify the overall burden of reported dengue cases.
* Identify countries and WHO regions with the highest dengue burden.
* Analyze the distribution of severe dengue cases.
* Calculate and compare severe case rates.
* Examine dengue-associated mortality.
* Calculate and compare case-fatality rates.
* Identify geographic patterns in dengue burden and outcomes.
* Develop an interactive surveillance dashboard.
* Translate epidemiological data into actionable visual insights.
* Demonstrate practical skills in health data analytics and Power BI.

---

# 📊 Key Epidemiological Indicators

| Indicator            | Definition                                             |
| -------------------- | ------------------------------------------------------ |
| **Total Cases**      | Total number of reported dengue cases                  |
| **Confirmed Cases**  | Laboratory or surveillance-confirmed dengue cases      |
| **Severe Cases**     | Reported cases classified as severe dengue             |
| **Severe Case Rate** | Severe cases as a proportion of total reported cases   |
| **Deaths**           | Reported dengue-associated deaths                      |
| **CFR**              | Proportion of reported dengue cases resulting in death |

### Severe Case Rate

```text
Severe Case Rate (%) =
Severe Cases / Total Cases × 100
```

### Case-Fatality Rate

```text
CFR (%) =
Deaths / Total Cases × 100
```

These indicators are interpreted together because no single measure adequately describes the epidemiological impact of dengue.

---

# 🗂️ Dataset

The project uses a dengue surveillance dataset containing epidemiological information at country and regional levels.

### Main Variables

* Country
* Geographic region
* Year
* Total dengue cases
* Confirmed cases
* Severe cases
* Deaths
* Population-related information
* Case-fatality measures

Before dashboard development, the data were reviewed and prepared to improve consistency and analytical reliability.

---

# 🔄 Data Analysis Workflow

The project followed a structured health-data analytics workflow:

```text
Raw Surveillance Data
        ↓
Data Cleaning & Validation
        ↓
Data Preparation
        ↓
Epidemiological Indicator Calculation
        ↓
Exploratory Analysis
        ↓
Power BI Data Modeling
        ↓
Dashboard Development
        ↓
Epidemiological Interpretation
        ↓
Public Health Recommendations
```

---

# 🧹 Data Preparation

The data preparation process included:

* Reviewing variable names and data types
* Checking missing values
* Checking duplicate records
* Standardizing geographic information
* Validating numerical variables
* Reviewing epidemiological calculations
* Creating calculated measures
* Preparing data for Power BI visualization

Data quality was considered an important component of the analytical process because differences in reporting and surveillance completeness can influence epidemiological interpretation.

---

# 📈 Dashboard Pages

## 1. Global Overview

The **Global Overview** page provides a high-level summary of the dengue situation.

### KPI Cards

* Total Cases
* Confirmed Cases
* Severe Cases
* Deaths
* CFR

The page provides users with a rapid overview before moving into more detailed analyses.

---

## 2. Geographic Analysis

The **Geographic Analysis** page examines the spatial distribution of dengue.

Users can compare:

* Countries
* WHO regions
* Total cases
* Severe cases
* Deaths
* CFR

Geographic visualization helps identify areas contributing substantially to the reported dengue burden.

---

## 3. Severity & Mortality

The **Severity & Mortality** page focuses on clinical outcomes.

### Main Indicators

* Severe Cases
* Severe Case Rate
* Deaths
* CFR

This page allows users to examine whether areas with high dengue burden also experience high levels of severe disease or mortality.

---

# 🔎 Epidemiological Analysis

The dashboard is designed around several important epidemiological questions:

### Disease Burden

**Where is the largest number of dengue cases being reported?**

### Geographic Distribution

**How does dengue burden vary between countries and WHO regions?**

### Disease Severity

**Which areas report the greatest burden of severe dengue?**

### Mortality

**Where are dengue-associated deaths concentrated?**

### Case Fatality

**Which areas have relatively high case-fatality rates?**

These questions help move the analysis from simple descriptive statistics toward meaningful epidemiological interpretation.

---

# 💡 Key Epidemiological Insights

The dashboard highlights several important principles:

### 1. Dengue burden is geographically heterogeneous

Reported dengue cases are not evenly distributed across countries and regions.

### 2. High case counts do not necessarily indicate high mortality

A region may report a large number of cases while maintaining a relatively low CFR.

### 3. Severe disease provides additional information

Total cases alone cannot fully describe the clinical impact of dengue. Severe cases and severe case rates provide additional information about disease outcomes.

### 4. Mortality indicators require contextual interpretation

Differences in surveillance completeness, healthcare access, diagnostic capacity, and case detection can influence observed mortality and CFR.

### 5. Surveillance data should be interpreted carefully

Reported cases represent detected disease and may not capture the complete burden of infection in the population.

---

# 🌍 Public Health Relevance

The dashboard can support public health activities including:

* Dengue surveillance
* Geographic risk assessment
* Outbreak monitoring
* Health-system preparedness
* Resource allocation
* Vector-control planning
* Mortality monitoring
* Epidemiological reporting
* Data-driven decision-making

The project demonstrates how interactive data visualization can help transform surveillance data into information that is easier for epidemiologists, health managers, and decision-makers to understand.

---

# 🛠️ Tools & Technologies

| Tool                        | Purpose                                        |
| --------------------------- | ---------------------------------------------- |
| **Microsoft Power BI**      | Dashboard development and visualization        |
| **Power Query**             | Data preparation and transformation            |
| **DAX**                     | Epidemiological measures and calculations      |
| **Microsoft Excel**         | Data inspection and preparation                |
| **Epidemiological Methods** | Indicator development and interpretation       |
| **GitHub**                  | Project documentation and portfolio management |

---

# 📐 Analytical Approach

The project applies descriptive epidemiological methods to examine:

* Person/place/time dimensions where available
* Disease burden
* Disease severity
* Mortality
* Case fatality
* Geographic variation
* Regional differences

The analysis primarily describes observed surveillance patterns and does not establish causal relationships between dengue and potential environmental or demographic determinants.

---

# ⚠️ Limitations

Several limitations should be considered when interpreting the dashboard.

### Reporting Bias

Not all dengue infections are necessarily detected or reported.

### Surveillance Differences

Countries may differ in diagnostic capacity, reporting systems, case definitions, and surveillance completeness.

### Missing Data

Missing observations may affect comparisons across countries and years.

### CFR Interpretation

CFR depends on the detection of both mild and severe cases. Under-detection of mild cases can result in an apparently higher CFR.

### Ecological Interpretation

Country-level and regional findings should not automatically be interpreted as individual-level risk.

### Temporal Comparability

Changes in surveillance systems and reporting practices may influence trends over time.

---

# 📌 Recommendations

Based on the analytical framework, the project recommends:

1. Strengthening routine dengue surveillance.
2. Improving completeness and timeliness of reporting.
3. Monitoring severe cases and deaths alongside total cases.
4. Prioritizing high-burden areas for surveillance and vector-control activities.
5. Investigating areas with unusually high CFRs.
6. Improving diagnostic and laboratory capacity.
7. Integrating epidemiological data with environmental and climatic information.
8. Using population-adjusted indicators when comparing countries.
9. Maintaining interactive surveillance dashboards for decision support.
10. Strengthening data-quality assurance and validation procedures.

---

# 📁 Repository Structure

```text
Dengue-Surveillance-Analysis/
│
├── data/
│   └── README.md
│
├── dashboard/
│   └── Dengue_Surveillance_Dashboard.pbix
│
├── images/
│   ├── global-overview.png
│   ├── geographic-analysis.png
│   └── severity-mortality.png
│
├── report/
│   └── Dengue_Surveillance_Report.pdf
│
├── README.md
│
└── LICENSE
```

> **Note:** Raw or restricted datasets should not be uploaded to GitHub if their licensing or data-sharing conditions prohibit redistribution.

---

# 📷 Dashboard Preview

## Global Overview

*Add screenshot of the Global Overview page here.*

```text
![Global Overview](images/global-overview.png)
```

## Geographic Analysis

*Add screenshot of the Geographic Analysis page here.*

```text
![Geographic Analysis](images/geographic-analysis.png)
```

## Severity & Mortality

*Add screenshot of the Severity & Mortality page here.*

```text
![Severity and Mortality](images/severity-mortality.png)
```

---

# 📄 Project Report

The detailed epidemiological report covers:

* Background
* Objectives
* Data and methodology
* Epidemiological indicators
* Dashboard design
* Geographic analysis
* Severity and mortality
* Epidemiological interpretation
* Public health implications
* Limitations
* Recommendations
* Conclusion

The full report is available in the `/report` directory.

---

# 🎓 Skills Demonstrated

This project demonstrates practical competencies in:

### Epidemiology

* Descriptive epidemiology
* Disease surveillance
* Epidemiological indicators
* Mortality analysis
* Case-fatality analysis
* Geographic epidemiology
* Public health interpretation

### Health Data Analytics

* Data cleaning
* Data validation
* Data transformation
* KPI development
* Data visualization
* Data storytelling

### Power BI

* Data modeling
* Power Query
* DAX measures
* Interactive dashboards
* Geographic visualization
* KPI cards
* Slicers and filters
* Dashboard design

### Professional Skills

* Analytical thinking
* Public health communication
* Evidence-based interpretation
* Decision-support reporting
* Technical documentation

---

# 🚀 Future Improvements

Future versions of the project could incorporate:

* Population-adjusted dengue incidence rates
* Monthly or weekly surveillance trends
* Climate and weather variables
* Rainfall and temperature data
* Vector distribution data
* Age- and sex-specific analysis
* Dengue serotype information
* Outbreak detection algorithms
* Automated data refresh
* Near-real-time surveillance
* Predictive modeling and forecasting
* Integration with additional public health data sources

These additions would allow the dashboard to move from primarily descriptive surveillance toward **early-warning and predictive epidemiological analytics**.

---

# 🧠 Conclusion

The **Dengue Surveillance Analysis Dashboard** demonstrates how epidemiological surveillance data can be transformed into an interactive public health intelligence product.

By integrating disease burden, geographic distribution, severity, and mortality indicators, the dashboard provides a multidimensional view of dengue epidemiology.

The project combines **epidemiological knowledge with modern health data analytics and Power BI visualization** to support the interpretation of complex surveillance information.

Ultimately, the project demonstrates the ability to move from:

```text
Data
  ↓
Information
  ↓
Epidemiological Insight
  ↓
Public Health Interpretation
  ↓
Decision Support
```

This workflow represents an important practical application of **Epidemiology + Health Data Analytics + Business Intelligence**.

---

# 👤 Author

**Oumar Mahamat Ahmat**

**Epidemiologist | Health Data Analyst | Public Health Professional**

### Areas of Interest

* Epidemiology
* Public Health Surveillance
* Health Data Analytics
* Disease Surveillance
* Data Visualization
* Power BI
* Health Information Systems
* Evidence-Based Decision Making

---

# 📬 Contact

For professional collaboration, research, or health data analytics opportunities, please connect through LinkedIn or GitHub.

---

## ⭐ Project Status

**Completed — Portfolio Project**

**Project:** Dengue Surveillance Analysis Dashboard
**Focus:** Global Epidemiological Analysis of Dengue Cases, Severity, and Mortality
**Primary Platform:** Microsoft Power BI
**Domain:** Epidemiology & Public Health Data Analytics

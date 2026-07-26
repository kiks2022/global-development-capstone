# Global Development Indicators: Health, Economy & Education Analysis

**Data Analytics Capstone Project — AnalystLab Africa Internship (Batch B)**
**Author:** Kikelomo Adekoya

## Project Overview

This project applies a complete data analytics workflow — data cleaning, analysis, visualization, and reporting — to the World Bank's World Development Indicators (WDI) dataset. It explores how health, economic, and education outcomes have evolved across 200+ countries between 1960 and 2024, and examines the relationship between economic prosperity, healthcare investment, and life expectancy, as well as global progress toward literacy and gender equality in education.

The project is delivered as **two linked Power BI dashboards**:

1. **Global Health & Development Dashboard** — GDP, health expenditure, life expectancy, and internet adoption trends
2. **Education & Gender Equality Dashboard** — Adult literacy rates by gender, the Gender Parity Index, and progress toward global literacy targets

## Dataset

- **Source:** [World Bank World Development Indicators (WDI)](https://datatopics.worldbank.org/world-development-indicators/)
- The dataset is not included in this repository due to its size. Download it directly from the link above (CSV format, "Bulk Downloads" section).
- **Indicators used:**
  - GDP growth (annual %)
  - GDP per capita (current US$)
  - Current health expenditure (% of GDP)
  - Current health expenditure per capita (current US$)
  - Life expectancy at birth, total (years)
  - Mortality rate, infant and under-5 (per 1,000 live births)
  - Individuals using the Internet (% of population)
  - Literacy rate, adult total / female / male (% of relevant population)
  - Literacy rate, youth Gender Parity Index (GPI)

## Tools Used

- **Power BI Desktop** — data modeling, DAX measures, dashboard design
- **Power Query** — data cleaning and transformation
- **DAX** — calculated measures for indicator-specific averages
- **Microsoft Word / PDF export** — final report

## Repository Contents

| File | Description |
|---|---|
| `Global_Health_Development_Dashboard.pbix` | Power BI file — health, GDP, and internet adoption dashboard |
| `Education_Literacy_Dashboard.pbix` | Power BI file — literacy and gender equality dashboard |
| `dashboard_health_screenshot.png` | Screenshot of the Health & Development dashboard |
| `dashboard_education_screenshot.png` | Screenshot of the Education & Gender Equality dashboard |
| `Capstone_Report.pdf` | Full written report (objective, methodology, findings, recommendations) |
| `README.md` | This file |

> **Note on the raw dataset:** The original WDI CSV file is too large to include in this repository. Please download it directly from the World Bank source link below (see Dataset section) to reproduce or extend this analysis.

## Data Cleaning Process

Using Power Query in Power BI, the raw WDI data was:
- Filtered down to the specific indicators relevant to this analysis
- Cleaned of blank rows and duplicates
- Unpivoted from a wide, year-per-column format into a long format with single `Year` and `Indicator Value` columns
- Renamed for clarity (`Country Name`, `Indicator Name`, etc.)

## Key Insights

**Health & Development:**
- GDP per capita has trended upward globally, though growth varies by country
- Higher GDP per capita is associated with higher life expectancy, though with diminishing returns at higher income levels
- Health expenditure per capita varies widely across countries

**Education & Gender Equality:**
- Global adult literacy averages 76.01%, still ~14 points below the commonly cited 90% benchmark
- A persistent gender gap exists: male literacy (81.61%) vs. female literacy (70.53%)
- The youth Gender Parity Index of 0.92 suggests the gap is narrowing among younger generations

Full findings, methodology, and recommendations are available in [`Capstone_Report.pdf`](./Capstone_Report.pdf).

## Demo Video

📹 **[Watch the full walkthrough here]** — *(https://drive.google.com/file/d/1YxJd_WPKNDx5TpKXAHStvc72lI4nWxnf/view?usp=drive_link)*

## Connect

📌 [LinkedIn Post](#) — *(https://www.linkedin.com/in/kikelomo-adekoya/)*

---

*Submitted as part of the AnalystLab Africa Data Analytics Internship, Week 8 Capstone Project.*

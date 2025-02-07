# 🦠 COVID-19: National Trends and Local Impact

## 📌 Overview
This project explores the **temporal and spatial impact of COVID-19** in the U.S., with a detailed focus on Oregon. It analyzes:
- National **case and death trends** (2020-2023)
- County-level **lethality rate variations** in Oregon
- The **effectiveness of vaccination campaigns** using regression analysis

## 🛠️ Tools & Techniques
- **Data Cleaning & Transformation**: `tidyverse`, `dplyr`
- **Data Visualization**: `ggplot2`, `scales`
- **Geospatial Analysis**: `tigris`, `sf`
- **Statistical Modeling**: Linear regression in `broom`
- **Automated Reporting**: `R Markdown` → `PDF`

## 📂 File Structure
- `covid19_analysis.Rmd` → The main R Markdown file for analysis
- `covid19_analysis.pdf` → Final report output

## 🔍 Reproducibility
1️⃣ Clone this repository  
2️⃣ Install required R packages using:
   ```r
   install.packages(c("tidyverse", "ggplot2", "sf", "tigris", "broom"))

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
2️⃣ This analysis requires several R packages to be installed and loaded for proper execution. Before running the code, please ensure the following packages are installed on your system:
`tidyverse`, `ggplot2`, `knitr`, `scales`, `tigris`, `sf`, `broom`.

To check whether a package is installed, you can use the `require() function`. If the package is not installed, `require()` will return `FALSE`. You can then install the missing package using the `install.packages()` function.

Here is a code snippet to automate this process. Copy and paste the code in the console to execute it:

```{r, eval = FALSE}
# required packages
required_packages <- c("tidyverse", "ggplot2", "knitr", "scales", "tigris", "sf", "broom")

# install missing packages
for (pkg in required_packages) {
  if (!require(pkg, character.only = TRUE)) {
    install.packages(pkg)
  }
}

# load all packages
lapply(required_packages, library, character.only = TRUE)
```

# Air Quality Case Study: Bundaran HI (2010–2021)

## Overview
This repository contains an exploratory data analysis (EDA) on **Jakarta’s air quality** at Bundaran HI station from 2010–2021.
The project is developed as part of an academic case study, aligned with:
- **SDG 3**: Good Health and Well-being
- **SDG 11**: Sustainable Cities and Communities

The goal is to analyze air pollutant trends, identify critical factors, and visualize results in support of public awareness and policy insights.

---

## Repository Structure  
data/ # Raw and processed datasets
scripts/ # R Markdown script for preprocessing, EDA, and visualization
results/ # Final outputs: knitted reports, infographic poster, and explanation video

---

## Files
- **data/**
  - `ispu_dki1.csv` → original dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/senadu34/air-quality-index-in-jakarta-2010-2021), originally published by **Satu Data Jakarta**
  - `preprocessed_df.csv` → cleaned and preprocessed dataset

- **scripts/**
  - `AQI_BundaranHI.Rmd` → main analysis script with preprocessing, EDA, and discussions

- **results/**
  - `air_quality_report.pdf` → finalized full analysis report with structured discussions
  - `air_quality_report.html` → knitted output of the R Markdown script
  - `Air Quality Chronicles Bundaran HI 2010-2021.png` → infographic e-poster (case study summary)
  - `air_quality_explanation.mp4` → project presentation video

---

## Methodology  
1. **Data Preprocessing**
   - Missing value imputation
   - Removal of incomplete PM2.5 column (except 2021)
   - Encoding categorical variables

2. **Exploratory Data Analysis (EDA)**
   - Summary statistics & distributions
   - Correlation analysis (Pearson)
   - Critical pollutant identification
   - Time-series trends and visualization

3. **Visualization**  
   - Histograms, correlation plots, bar charts
   - Time series line charts (per pollutant, yearly averages)
   - Box plots & scatter plots

---

## Key Insights  
- **PM10** consistently emerges as the dominant critical pollutant.
- Air quality fluctuated over the decade, with noticeable declines in 2011–2012 and improvements post-2017.
- The analysis highlights the impact of particulate matter (PM10, PM2.5) on urban air quality and health risks.

---

## References  
- Dataset: [Kaggle – Air Quality Index in Jakarta 2010–2021](https://www.kaggle.com/datasets/senadu34/air-quality-index-in-jakarta-2010-2021)
- Open Data Jakarta (DLH DKI Jakarta)
- Supporting literature on Pearson correlation & exploratory data analysis

---

## Authors
- Gabriella Widjaja
- Khansa Nabilah Awali
- Syalista Galuh Nadira

---

## License
This project is for educational and portfolio purposes. Dataset attribution belongs to Kaggle/Open Data Jakarta.

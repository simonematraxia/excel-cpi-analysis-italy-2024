# Excel CPI Analysis — Italy 2024

**Course**: Information Processing Systems
**Author**: Simone Giovanni Matraxia

## Overview
Developed as the final exam project for the *Information Processing Systems* course, this workbook performs a structured analysis of the Italian Consumer Price Index (CPI) throughout 2024. The dataset is sourced from the official ISTAT FOI index (Families of Blue and White-Collar Workers, base 2015=100), covering 14 ECOICOP spending categories with monthly granularity.

## Core Features & Analysis
* **Statistical Summary**: Annual average, category ranking, and absolute year-on-year price variation (Jan–Dec) computed for all 14 ECOICOP spending categories.
* **Extremes Detection**: Monthly peak and trough values per category, dynamically linked to their corresponding month label.
* **Trend Classification**: Identification of categories with a stable and low price trend, and detection of categories with a constant month-over-month price increase throughout the year.
* **Quarterly Moving Average**: 3-month rolling average tracked for four key categories: All Items, Food, Health, and Transport.
* **Conditional Formatting**: Color-gradient scale (green-to-red) on the general index; 5-symbol icon sets applied per individual spending category.
* **Data Quality & Correlation**: Completeness validation across all sheets to detect missing values; Pearson correlation computed between Food and Transport monthly price series.
* **Chart**: Line chart visualizing the monthly price trend of Communication and Education across all 12 months of 2024.

## Data Source
ISTAT — *Indice dei prezzi al consumo per famiglie di operai e impiegati (FOI)*  
Table: *Prezzi al consumo - indici nazionali per divisione di spesa* | [esploradati.istat.it](https://esploradati.istat.it/databrowser/#/it/dw/categories)

## Technical Stack
* **Tool**: Microsoft Excel
* **Dataset**: ISTAT FOI Monthly Index 2024 (14 ECOICOP categories)
* **Functions used**: `AVERAGE`, `MAX`, `MIN`, `RANK.EQ`, `INDEX`, `MATCH`, `SUMPRODUCT`, `IF`, `IFS`, `IFERROR`, `CONCATENATE`, `MID`, `RIGHT`, `SEARCH`, `PROPER`, `TRIM`, `COUNTBLANK`, `NOW`
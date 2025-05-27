# 🛒 Tesco Grocery Analysis: Exploring Public Health & Income Patterns Through Retail Data
![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue?logo=python)

This project investigates grocery purchasing patterns across London using the **Tesco Grocery dataset**, in combination with public health and income data. The goal is to explore how **demographics and income levels influence food choices**, and to uncover potential links to **obesity-related hospitalisation trends**. This work showcases how **data science can inform social policy and public health strategy** through real-world, large-scale data analysis.

---

## 📌 Project Overview

**Data Source**: Tesco Grocery 1.0 (420M+ transactions from Tesco Clubcard holders, 2015)  
**Additional Data**:
- Obesity-related hospitalisation rates (NHS & Public Health England)
- Gross Disposable Household Income (ONS)  
**Area of Focus**: Greater London (aggregated by LSOA/MSOA/Borough/Ward)

This case study was completed as part of the **Applied Data Science MSc module** at the University of Bath. The project combines data cleaning, visualisation, statistical correlation, and storytelling using both Python and Tableau.

---

## 🎯 Objectives

1. **Demographic Insight**  
   Examine how age and gender distribution across London boroughs influence grocery buying patterns (e.g. sweets, grains, dairy, ready-made meals).

2. **Public Health Correlation**  
   Investigate potential relationships between nutritional trends in regions and obesity-related hospitalisation rates.

3. **Socioeconomic Impact**  
   Explore how income levels affect consumer preferences for food categories, and identify any associations between economic status and health-conscious purchasing behaviour.

---

## 🧰 Tools & Technologies

- **Languages**: Python (pandas, seaborn, numpy, matplotlib)
- **Environment**: Jupyter Notebook
- **Visualisation**: Tableau, Matplotlib
- **Statistical Methods**: Spearman correlation, distributional analysis
- **Other**: ONS & NHS datasets (public sources)

---

## 🧪 Methodology

### 🟠 Data Preparation
- Cleaned and standardised Tesco datasets by borough
- Engineered new columns to segment regions by age and gender (e.g., High-Youth, Female-Dominated)
- Merged external datasets (GDHI & obesity hospitalisation) on common geography levels

### 🟠 Analysis
- Created Tableau dashboards to visualise spatial and behavioural trends
- Performed Spearman correlation to identify potential associations between:
  - Nutrient consumption and hospitalisation
  - Income levels and specific food preferences
- Created age and gender segmentation maps, and income distribution overlays

### 🟠 Documentation
- Each stage of analysis is annotated in the Jupyter Notebook using markdown cells
- Supplementary files (presentation & executive summary) included for interpretive context

---

## 📊 Key Findings

### 📍 Demographics & Purchasing
- **Male-Dominated Areas**: Higher intake of grains, dairy, and eggs (energy-dense foods)
- **Female-Dominated Areas**: Greater preference for sweets and ready-made foods
- **High-Youth Regions**: More consumption of sweets and grains, less fruit and vegetables
- **Low-Youth Regions**: More ready-made dishes and fruits/vegetables, possibly reflecting health-conscious or convenience-focused behaviour

### 📍 Health & Nutrition
- **Fibre** intake negatively correlated with hospitalisation rates (expected, aligns with public health guidance)
- Surprisingly, **fat and sugar** intake showed negative correlations, suggesting potential data limitations or confounding variables
- **Protein** intake positively correlated with hospitalisations — could reflect deeper socio-behavioural trends or dietary overconsumption

### 📍 Income & Preferences
- Higher-income boroughs showed preference for:
  - Organic and premium foods (e.g., grains, bottled water)
  - Quality proteins (e.g., fish and poultry)
- Negative correlation between income and purchase of dairy/wine/fruit in some areas — indicating emerging preferences for plant-based or alternative diets

---

## 📎 Supporting Materials

- 📄 [Executive Summary (PDF)](docs/CM50266_TescoDataAnalysis.pdf): Concise summary of objectives, insights, and conclusions.
- 🎤 [Presentation Slides (PDF)](docs/CM50266_Presentation.pdf): Stakeholder-facing presentation outlining key findings and public health implications.

These materials offer context for the analysis and showcase how results were communicated clearly for both technical and non-technical audiences.

# Air Pollution & Lung Cancer Analysis

> A spatiotemporal data analysis project exploring the relationship between air pollution and lung cancer incidence across Taiwan.

## Project Overview

This project is based on my master's research in Statistics at National Dong Hwa University.

The study integrates multiple data sources, including air pollution, population demographics (population size and age structure), lung cancer incidence, smoking prevalence, and geographic information. The datasets were cleaned, processed, and merged into a unified township-level dataset.

The final dataset contains **2,576 township-year observations** covering **368 townships over seven years**.

---

## Tools & Methods

**Programming**
- Python
- R

**Data Processing**
- Multi-source data cleaning and integration
- Missing value handling

**Spatial Analysis & Prediction**
- Ordinary Kriging
- Universal Kriging
- Random Forest-based Regression Kriging
- Leave-One-Out Cross-Validation (LOOCV)

**Statistical Modeling**
- Poisson Data Rate Model
- Bayesian Spatiotemporal Varying Coefficient Model (STVC)
- R-INLA

---

## Analysis Workflow

- **Data Cleaning & Integration**  
  Integrated and processed multi-source data into a unified township-level structure.

- **Spatial Prediction**  
  Applied spatial prediction methods to estimate township-level air pollution concentrations.

- **Model Evaluation**  
  Evaluated prediction performance using **LOOCV** and **MSE**.

- **Statistical Modeling**  
  Applied Poisson rate and Bayesian STVC models to examine the relationship between air pollution and lung cancer incidence.

- **Visualization & Interpretation**  
  Visualized spatial patterns and regional differences in model estimates.

---

## Key Results

- Built a spatiotemporal dataset covering **368 townships over seven years**.
- Compared multiple spatial prediction approaches for estimating township-level air pollution concentrations.
- Examined spatial and temporal heterogeneity in the estimated associations between air pollutants and lung cancer incidence.
- Visualized regional patterns to support interpretation of model results.

---

## Visualizations
### Air Pollution Distribution
<table>
  <tr>
    <td align="center"><b>PM2.5</b></td>
    <td align="center"><b>NO2</b></td>
  </tr>
  <tr>
    <td>
      <img src="https://github.com/user-attachments/assets/2c80a577-d040-4892-865c-7665dfe1ec56" width="90%" alt="PM2.5 Distribution">
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/55755267-f37c-4112-bbd7-ce095a39751f" width="100%" alt="NO2 Distribution">
    </td>
  </tr>
</table>

---

## Data Availability

The original research datasets are not included due to data access and research restrictions. This repository presents selected code, analytical workflows, and results for portfolio purposes.

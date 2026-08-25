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

`Data Cleaning & Integration`
→ `Spatial Prediction`
→ `Model Evaluation`
→ `Statistical Modeling`
→ `Visualization & Interpretation`

- Integrated and processed multi-source data into a unified township-level structure.
- Applied spatial prediction methods to estimate township-level air pollution concentrations.
- Evaluated prediction performance using **LOOCV** and **MSE**.
- Applied Poisson rate and Bayesian STVC models to examine the relationship between air pollution and lung cancer incidence.
- Visualized spatial patterns and regional differences in model estimates.

---

## Key Results

- Built a spatiotemporal dataset covering **368 townships over seven years**.
- Compared multiple spatial prediction approaches for estimating township-level air pollution concentrations.
- Examined spatial and temporal heterogeneity in the estimated associations between air pollutants and lung cancer incidence.
- Visualized regional patterns to support interpretation of model results.

---

## Visualizations

### Air Pollution Distribution

<!-- ![Air Pollution Distribution](figures/air_pollution_distribution.png) -->

Township-level geographic distribution of air pollution concentrations.

### Spatial Prediction Results

<!-- ![Spatial Prediction](figures/spatial_prediction.png) -->

Comparison and visualization of township-level air pollution predictions.

### Spatiotemporal Model Results

<!-- ![STVC Results](figures/stvc_results.png) -->

Spatial patterns of estimated pollutant effects from the Bayesian STVC model.

---

## Data Availability

The original research datasets are not included due to data access and research restrictions. This repository presents selected code, analytical workflows, and results for portfolio purposes.


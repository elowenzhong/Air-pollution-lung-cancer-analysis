# Air Pollution & Lung Cancer Analysis

> A spatiotemporal data analysis project exploring the relationship between air pollution and lung cancer incidence across Taiwan.

## Project Overview

This project is based on my master's research in Statistics at National Dong Hwa University.

The study integrates multiple data sources, including air pollution, population, lung cancer incidence, smoking prevalence, and geographic information. The final dataset contains 2,576 township-year observations covering 368 townships in Taiwan over a seven-year period.

The project focuses on data preprocessing, spatial prediction, statistical modeling, model evaluation, and spatial visualization to investigate the spatiotemporal relationship between air pollution and lung cancer incidence.

## Tech Stack

**Programming**
- Python
- R

**Spatial Analysis and Statistical Modeling**
- Ordinary Kriging
- Universal Kriging (Random forest)
- Bayesian Spatiotemporal Varying Coefficient Model (STVC)
- Poisson Rate Model

**Visualization**
- ggplot2
- Spatial visualization

## Analysis Workflow

1. **Data Cleaning & Integration**
   - Integrated data from multiple sources
   - Handled missing values and prepared township-level data

2. **Spatial Prediction**
   - Applied Kriging and Random Forest-based approaches to estimate air pollution concentrations across townships

3. **Model Evaluation**
   - Compared spatial prediction methods using cross-validation and prediction error metrics

4. **Statistical Modeling**
   - Applied Poisson rate models to examine associations between air pollutants and lung cancer incidence
   - Used Bayesian STVC models to investigate spatial and temporal variation in pollutant effects

5. **Visualization & Interpretation**
   - Visualized geographic patterns of air pollution and model estimates
   - Examined regional differences in estimated pollutant effects

## Key Results

- Built a township-level spatiotemporal dataset covering 368 townships and seven years.
- Compared multiple spatial prediction approaches for estimating township-level air pollution concentrations.
- Identified spatial and temporal heterogeneity in the estimated associations between air pollutants and lung cancer incidence.
- Produced spatial visualizations to support interpretation of regional patterns and model results.

## Selected Visualizations

Selected figures from the analysis will be presented here.

<!-- Example:
![Air Pollution Distribution](figures/air_pollution_distribution.png)
![Spatial Prediction](figures/spatial_prediction.png)
![STVC Results](figures/stvc_results.png)
-->

## Repository Structure

```text
air-pollution-lung-cancer-analysis/
├── README.md
├── code/
│   ├── data_preprocessing/
│   ├── spatial_prediction/
│   └── statistical_modeling/
├── figures/
└── data/
    └── README.md
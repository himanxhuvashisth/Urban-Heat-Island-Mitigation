# Urban Heat Island Effect Mitigation for Chandigarh

This repository provides a comprehensive analysis and solution for mitigating the Urban Heat Island (UHI) effect in Chandigarh city. The project includes data generation, analysis, modeling, and actionable insights to address the UHI phenomenon effectively.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Project Workflow](#project-workflow)
3. [Dataset Details](#dataset-details)
4. [Technologies Used](#technologies-used)
5. [Key Features](#key-features)
6. [Usage Instructions](#usage-instructions)


---

## Introduction

Urban Heat Island (UHI) is a phenomenon where urban areas exhibit significantly higher temperatures compared to surrounding rural areas due to human activities, reduced vegetation, and heat-absorbing surfaces. This project focuses on identifying UHI hotspots in Chandigarh, predicting future trends, and recommending cooling actions.

---

## Project Workflow

The workflow for this project includes the following steps:

1. **Linking to Google Drive**:
   - Storing and accessing datasets and results.
2. **Importing Necessary Libraries**:
   - Libraries for data processing, visualization, machine learning, and geospatial analysis.
3. **Initializing Google Earth Engine (GEE)**:
   - Authenticate and initialize GEE for remote sensing data access.
4. **Dataset Generation**:
   - Extracting UHI and environmental features (e.g., NDVI, EVI, NO₂) using satellite datasets for multiple regions in Chandigarh.
5. **Exploratory Data Analysis (EDA)**:
   - Visualizing feature distributions and correlations with UHI.
6. **Hot Spot Identification**:
   - Using clustering techniques to identify UHI hotspots.
7. **Predictive Modeling**:
   - Building machine learning models (e.g., Random Forest, XGBoost, Prophet) to predict UHI trends.
8. **Cooling Action Suggestions**:
   - Providing actionable recommendations to mitigate UHI effects.

---

## Dataset Details

The dataset includes:
- **Time Period**: Data collected from 2018 to 2022 at 16-day intervals.
- **Features**:
  - UHI (Urban Heat Island Index)
  - NDVI (Normalized Difference Vegetation Index)
  - EVI (Enhanced Vegetation Index)
  - Albedo (Surface Reflectance)
  - NO₂ Levels (Air Pollution)
  - Population Density
  - Geospatial Metadata (Latitude, Longitude)

---

## Technologies Used

- **Languages**: Python
- **Libraries**:
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `scikit-learn`, `xgboost`
  - `keras`, `prophet`
  - `folium`, `geemap`
- **Google Earth Engine (GEE)**: Satellite data extraction.
- **Jupyter Notebook**: Interactive data analysis and visualization.

---

## Key Features

1. **Dynamic Region Analysis**:
   - Automatically define and analyze multiple regions within Chandigarh.
2. **16-Day Interval Data**:
   - Temporal aggregation for detailed trend analysis.
3. **Hot Spot Identification**:
   - Clustering UHI data to pinpoint the most affected areas.
4. **Predictive Modeling**:
   - Forecasting future UHI trends using machine learning.
5. **Cooling Action Recommendations**:
   - Suggestions based on environmental and socio-economic features.

---

## Usage Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/JaskaranSingh0/UHI-Mitigation.git
   cd uhi-mitigation
   

# Traffic Accident Analysis & Severity Prediction

![Project Banner](https://via.placeholder.com/800x200?text=Traffic+Accident+Analysis) <!-- Add a relevant banner image -->

A comprehensive analysis of US traffic accidents using two datasets to understand patterns, contributing factors, and predict accident severity.

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Datasets](#-datasets)
- [Key Features](#-key-features)
- [Technical Approach](#-technical-approach)
- [Installation](#-installation)
- [Usage](#-usage)
- [Key Findings](#-key-findings)
- [Future Work](#-future-work)
- [License](#-license)

## 🌟 Project Overview
This project analyzes two complementary datasets on US traffic accidents to:
1. Explore spatial and temporal patterns of accidents
2. Identify key contributing factors to accident severity
3. Develop predictive models for accident severity
4. Visualize hotspots and risk factors

## 📂 Datasets
1. **US Accidents Dataset** (7.7M+ records)
   - Source: Kaggle (sobhanmoosavi/us-accidents)
   - Features: Location, time, weather, road conditions, severity (1-4)
   - Time period: 2016-2023

2. **Traffic Conditions Dataset** (8,756 records)
   - Features: Traffic density, pavement quality, vehicle counts, etc.
   - Complementary metrics for contextual analysis

## 🚀 Key Features
- **Data Exploration**: Comprehensive EDA with visualizations
- **Geospatial Analysis**: Accident heatmaps across the US
- **Temporal Analysis**: Hourly, weekly, and seasonal patterns
- **Weather Impact**: Relationship between conditions and severity
- **Predictive Modeling**: XGBoost classifier for severity prediction

## 🔧 Technical Approach
```mermaid
graph TD
    A[Data Collection] --> B[Data Cleaning]
    B --> C[Exploratory Analysis]
    C --> D[Feature Engineering]
    D --> E[Model Development]
    E --> F[Visualization]
    F --> G[Insights Generation]

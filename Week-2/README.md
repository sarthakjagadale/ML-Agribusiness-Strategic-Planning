# Week 2 – Data Exploration and Preprocessing Strategy

## Overview

Week 2 focuses on preparing agricultural data for Machine Learning. Since a specific dataset was not provided, publicly available agricultural and weather datasets are used as realistic examples.

The main focus areas are:

* Public agricultural data research
* Data profiling
* Data cleaning
* Missing-value handling
* Duplicate detection
* Outlier detection
* Data transformation
* Exploratory Data Analysis
* Feature engineering
* Data leakage prevention
* Train/validation/test splitting
* Data quality validation

## Objectives

1. Identify suitable agricultural datasets.
2. Understand agricultural data quality challenges.
3. Develop a systematic preprocessing framework.
4. Design a comprehensive EDA methodology.
5. Define missing-value and outlier strategies.
6. Prevent data leakage.
7. Prepare data for future ML modeling.

## Public Data Sources

* FAOSTAT
* NASA POWER
* USDA NASS Quick Stats
* Satellite/Remote Sensing Data
* Soil Data

## Main Agricultural ML Problem

The recommended initial problem is crop-yield prediction using:

* Weather data
* Soil information
* Historical crop yield
* Crop type
* Location
* Agricultural management information
* Remote-sensing features where available

## Preprocessing Pipeline

```text
Raw Data
   ↓
Data Collection
   ↓
Data Profiling
   ↓
Data Validation
   ↓
Missing Value Handling
   ↓
Duplicate Removal
   ↓
Outlier Detection
   ↓
Data Transformation
   ↓
Feature Engineering
   ↓
EDA
   ↓
Leakage Check
   ↓
Train/Validation/Test Split
   ↓
Model-Ready Dataset
```

## Expected Outcome

At the end of Week 2, the project will have a documented and reproducible data exploration and preprocessing strategy that can be used for future machine-learning model development.

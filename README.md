# ClimateAi Data Science Challenge: Seasonal Forecasting of Summertime Precipitation in the Midwest US
This repository contains notebooks and code for the ClimateAi Data Science Challenge, which involves forecasting summertime (June, July, and August) precipitation in the Midwest US using a machine learning approach. The project aims to leverage spatio-temporal predictors such as sea surface temperature, atmospheric conditions, and other oceanic and atmospheric variables to predict precipitation patterns that are critical for agriculture.

## Challenge Description
The goal of this challenge is to propose a methodology for forecasting summertime precipitation in the Midwest, utilizing the provided spatio-temporal predictor datasets. The challenge emphasizes not only the proposed solution but also the rationale behind modeling decisions.

## Repository Structure
This repository is organized as follows:

```bash
├── 01_etl.ipynb            # Data Extraction, Transformation, and Loading (ETL)
├── 02_eda.ipynb            # Exploratory Data Analysis (EDA)
├── 03_model_baseline.ipynb # Baseline Model Setup and Evaluation
├── 04_model_ml.ipynb       # Advanced Machine Learning Models
└── README.md               # Project documentation
```

## Notebooks Overview
### 01_etl.ipynb:

Performs data extraction, transformation, and loading of the provided datasets.
Reads the NetCDF files, upsamples target data, and prepares additional Ocean Nino Index (ONI).
Prepares the data for analysis and modeling.

### 02_eda.ipynb:

Conducts exploratory data analysis to uncover insights that inform the modeling approach.
Visualizes trends, patterns, and correlations in the predictor variables and precipitation data.
Highlights important features for forecasting precipitation.

### 03_model_baseline.ipynb:

Develops a baseline model for comparison purposes.
Evaluates simple statistical models (e.g., arithmetic mean) as a benchmark.
Sets up basic performance metrics to measure model accuracy.

### 04_model_ml.ipynb:

Implements neural networks for precipitation forecasting.
Includes feature engineering, hyperparameter tuning, and model evaluation.

## Data
Data Sources: [here.](https://drive.google.com/drive/folders/1ZIY5uPlTJrFByvD2QNDGZV70bGMxXVFd)
The provided datasets consist of:

### Predictors File:
Includes monthly oceanic and atmospheric variables (e.g., sea surface temperature, tropospheric thickness, precipitable water, etc.) spanning January 1982 to December 2023.

### Predicted Variable File:
Contains monthly gridded precipitation data for the Midwest US, covering the same time period.

# License
This project is for the ClimateAi Data Science Challenge and is not licensed for public distribution or commercial use.

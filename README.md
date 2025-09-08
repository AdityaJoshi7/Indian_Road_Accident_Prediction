#  Road Accident Prediction & Dashboard  

## Introduction  
The **Road Accident Prediction & Dashboard** project is designed to analyze and predict accident severity in India. Using **Python (Jupyter Notebook)** for preprocessing and modeling, and **Power BI** for visualization, this project delivers insights into accident causes, trends, and hotspots.  

The workflow integrates **data from Kaggle**, cleans and processes it in Python, trains a machine learning model (achieving **52% accuracy**), and visualizes results in a **3-page Power BI dashboard**.  

---

## Table of Contents  
1. [Project Objective](#project-objective)  
2. [Data Source](#data-source)  
3. [Notebook Workflow](#notebook-workflow)  
4. [Dashboard & Features](#dashboard--features)  
5. [Usage](#usage)  
6. [Key Insights](#key-insights)  
7. [Dependencies](#dependencies)  

---

## Project Objective  
To build a **predictive model and dashboard** that:  
- Analyzes **accident patterns** (time, location, severity, vehicle type).  
- Predicts **accident severity** with ML models.  
- Provides **interactive Power BI visuals** for decision-making.  
- Highlights **road safety insights** for policymakers.  

---

## Data Source  
The dataset was taken from **Kaggle**:  
- **File:** `accident_prediction_india.csv`  
- Contains accident records with details on:  
  - Severity (Fatal, Serious, Minor)  
  - Road & weather conditions  
  - Vehicle type involved  
  - Driver demographics  
  - Accident year & state  

---

## Notebook Workflow  
The **Jupyter Notebook (`India_Road_Accident_Prediction.ipynb`)** includes:  

1. **Data Cleaning**  
   - Handling missing values and duplicates.  
   - Encoding categorical variables.  
   - Normalizing numerical features.  

2. **Exploratory Data Analysis (EDA)**  
   - Accidents by **year, state, and severity**.  
   - Breakdown by **vehicle type, road type, and weather**.  
   - Hotspot identification.  

3. **Model Training & Evaluation**  
   - Machine learning models trained for **severity prediction**.  
   - Evaluated with **Accuracy, Precision, Recall**.  
   - **Final Model Accuracy: 52% (0.52)**  

---

## Dashboard & Features  
The **Power BI Dashboard (`Road_Accident India.pbix`)** contains 3 pages:  

- **Page 1: Accident Overview**  
  - Total accidents, casualties, fatalities  
  - Year-wise trends  

- **Page 2: Causes & Severity**  
  - Analysis by weather, road conditions, vehicle type  
  - Traffic control and license status impact  

- **Page 3: Hotspots & Predictions**  
  - State-wise accident hotspots  
  - Demographics (age, gender of drivers)  
  - Severity vs road type & lighting conditions  

---

## Usage  
1. Run the Jupyter Notebook for **data cleaning, EDA, and model training**.  
2. Load the processed data into **Power BI**.  
3. Explore the interactive dashboard pages.  
4. Export visuals to **PDF, Excel, or PowerPoint** for reporting.  

---

## Key Insights  
From the analysis and dashboard:  
- **Two-wheelers and trucks** have the highest fatalities.  
- Accidents are more severe on **state & national highways**.  
- **Weather and road conditions** significantly influence accident severity.  
- Peak accident times: **morning and evening hours**【Road_Accident India.pdf】.  
- Total dataset stats: **3000 accidents, 15K casualties, 7366 fatalities**.  

---

## Dependencies  
- **Python (3.x)**  
- **Jupyter Notebook**  
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  
  - scikit-learn  
- **Power BI Desktop** (for visualization)  

---

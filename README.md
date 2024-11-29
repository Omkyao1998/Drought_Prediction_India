Drought Severity Prediction in Maharashtra, India
This repository contains the research and implementation of a machine learning-based system to predict drought severity in Maharashtra, India. The project leverages the Standardized Precipitation Index (SPI) and climate features influenced by the El Niño Southern Oscillations (ENSO).
Overview
Droughts significantly affect agriculture, water resources, and rural livelihoods, especially in rainfed regions like Maharashtra. This study employs a Logistic Regression Model to predict drought severity, using historical climate data from NASA POWER (2001-2021). The system provides actionable insights for drought preparedness by forecasting SPI values for 1, 3, and 6 months.
Key Features:
Machine Learning Model: Predicts drought severity with high accuracy based on SPI values.
ENSO Analysis: Explores the relationship between ENSO indicators (SOI, ONI) and drought occurrences.
Data-Driven Insights: Highlights increasing frequency and severity of droughts in Maharashtra.
Feature Engineering: Utilizes key meteorological parameters such as precipitation, temperature, and soil moisture.
Dataset
The project uses publicly available data from the NASA POWER platform. Features include:
Meteorological Variables: Precipitation, surface pressure, soil wetness, temperature, wind speed.
Climate Indices: SOI, ONI.
Methodology
Data Preprocessing: Cleaning and scaling using StandardScaler.
Feature Selection: Pearson correlation, Recursive Feature Elimination (RFE), and Random Forest.
Dimensionality Reduction: Principal Component Analysis (PCA) with scree plot analysis.
Modeling: Logistic Regression for drought classification based on SPI.
SPI Categories:
SPI Range	Drought Category
> 2.0	Extremely Wet
1.5 to 1.99	Very Wet
1.0 to 1.49	Moderately Wet
-0.99 to 0.99	Near Normal
-1.0 to -1.49	Moderately Dry
-1.5 to -1.99	Severely Dry
< -2.0	Extremely Dry
Results
Accuracy: The model accurately predicts drought severity for 1, 3, and 6-month horizons.
Findings: Notable drought events (2002, 2008, 2012, 2013) were correctly identified.
ENSO Impact: A strong correlation between ENSO phases and drought occurrences was observed.
Future Work
Expand analysis with updated datasets.
Integrate additional climate variables for improved accuracy.
Develop a user-friendly interface for real-time predictions.

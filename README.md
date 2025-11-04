🌧️ MSc Dissertation: Predicting Tropical Rainfall Using Machine Learning

Author: Shubham Ganesh Shinde

Degree: MSc Advanced Computer Science (Data Analytics)

Institution: University of Leeds

Year: 2024/2025

📘 Project Overview

This dissertation explores whether machine learning models trained solely on satellite rainfall data can outperform traditional weather forecasting methods in tropical Africa — a region where convective storms make prediction exceptionally difficult.

🛰️ Dataset
- Source: NASA’s Integrated Multi-satellite Retrievals for GPM (IMERG)
- Coverage: Daily precipitation data across tropical Africa (1998–2024)

🧪 Methodology
- Preprocessing: Data integrity checks, lag features, rolling averages, seasonal indicators
- Classification: Rainfall grouped into No Rain, Light Rain, Heavy Rain
- Models Used:
- Decision Tree
- Logistic Regression
- Random Forest
- K-Nearest Neighbours (KNN)
- Long Short-Term Memory (LSTM)
- Balancing: SMOTE applied to address class imbalance

📊 Key Results
- Logistic Regression + SMOTE achieved 89% accuracy
- LSTM underperformed (66.5%), showing limitations of precipitation-only inputs
- Simpler models proved more reliable and interpretable

🌱 Impact
This study demonstrates that lightweight ML models can provide useful forecasting capabilities in resource-constrained environments — with applications in agriculture, disaster planning, and water management.


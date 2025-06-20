# 💻 Laptop Price Analysis
## 📊 Overview

This project analyzes a dataset of 1275 laptops to uncover insights into how various technical specifications influence laptop pricing. The objective is to assist consumers and businesses in making informed decisions based on feature-price relationships.

## 🔍 Objectives

Identify major price-determining features (e.g., brand, RAM, GPU, storage type).

Understand trends across screen size, weight, CPU types, and display features.

Predict laptop prices using machine learning regression models.

## 🧰 Tools & Technologies

Language: Python

Libraries:

pandas, numpy – Data processing

seaborn, matplotlib, plotly – Visualization

scikit-learn – Machine learning

Notebook: Jupyter

## 📁 Dataset Details
Feature	Description
Company	Laptop brand (e.g., Apple, HP)
Product	Model name
TypeName	Form factor (Notebook, Ultrabook, etc.)
Inches	Screen size
Ram	RAM in GB
OS	Operating system
Weight	Laptop weight (kg)
Price_euros	Price in Euros
Screen, ScreenW, ScreenH	Display specs
Touchscreen, IPSpanel, RetinaDisplay	Display features
CPU_company, CPU_model, CPU_freq	CPU info
PrimaryStorage, SecondaryStorage	Storage capacity (GB)
PrimaryStorageType, SecondaryStorageType	SSD/HDD/Flash
GPU_company, GPU_model	GPU specifications

✅ No missing values and data is clean and ready for analysis.

## 📈 Analysis Conducted
Brand-wise average pricing

RAM & Storage impact on price

Form factor vs Price (Ultrabook, Gaming, etc.)

CPU & GPU trends by manufacturer

Display types (Touchscreen, IPS, Retina) and price correlation

## 🤖 Machine Learning
Trained regression models to predict laptop prices using:

Linear Regression

Random Forest

XGBoost

Evaluation Metrics:

Root Mean Squared Error (RMSE)

R² Score

## 📊 Key Findings
SSD drives and higher RAM are strong predictors of higher price.

Apple and MSI have the highest price range.

Ultrabooks and Gaming laptops are more expensive.

GPU and CPU company significantly influence pricing.

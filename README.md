Machine Learning for Crude Oil Quality Prediction & Valuation

📖 Project Overview

Crude oil is not a uniform commodity; its quality varies significantly based on density (API Gravity) and Sulfur Content. This project leverages Machine Learning to automate the assessment of crude oil quality, helping refineries optimize their feedstock selection and valuation processes.

This repository contains the full project analysis, including the dataset, detailed project report, presentation slides, and the Python code used for modeling.

🏢 Business Context

The Challenge:

Refinery Complexity: Different refineries require specific crude types. Mismatches cause operational bottlenecks.

Cost & Safety: High sulfur ("Sour") crude is corrosive and expensive to process.

Valuation: Market price is dictated by quality. Inaccurate assessment leads to financial loss.

Our Solution:
A Data-Driven ML framework that predicts market-critical metrics using underlying chemical markers.

🎯 Project Objectives

1. Classification (Refinery Suitability)

Goal: Categorize crude samples to determine immediate processing compatibility.

Targets: * Crude Type: Light, Medium, Heavy

Sulfur Flavour: Sweet, Sour

Models Used: Logistic Regression, Decision Trees, Random Forest (Classifiers).

2. Regression (Precise Valuation)

Goal: Predict the exact numerical quality values for pricing.

Targets: * API Gravity

Total Sulfur (% wt)

Models Used: Linear Regression, Random Forest (Regressor), Gradient Boosting.

📂 Repository Structure

├── data/               # Contains the dataset (CSV/Excel)

├── docs/               # Project Report (PDF) and Presentation (PPT/PDF)

├── notebooks/          # Google Colab Notebooks (.ipynb)

├── README.md           # Project documentation


📊 Dataset Details

The dataset (Crudeoil.xlsx) contains physicochemical assays of various crude oil blends. Key features include:

Macro Properties: Density, API Gravity, Viscosity, Pour Point.

Chemical Impurities: Sulfur, Nitrogen, Acid Number, Nickel, Vanadium.

Composition: Detailed hydrocarbon chains (Light ends, C6/C7 groups).

🚀 Getting Started

Clone the repository:

git clone [https://github.com/your-username/Crude-Oil-Valuation-ML.git](https://github.com/your-username/Crude-Oil-Valuation-ML.git)


Explore the Notebook:

Navigate to the notebooks/ folder.

Open the .ipynb file in Google Colab or Jupyter Notebook.

Ensure the path to the dataset in the code matches your local environment.

📈 Key Results

Achieved 100% accuracy in classifying crude oil types.

Regression models predicted API Gravity with an R² score of 0.951.

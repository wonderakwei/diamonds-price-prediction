# Diamonds Price Prediction

## Overview

This repository contains a project focused on predicting diamond prices using the Diamonds Price Dataset. With features ranging from carat weight to clarity, the goal is to develop a robust machine learning model that accurately forecasts diamond valuations.

## Dataset

The dataset includes the following columns:
- **carat**: Diamond weight in carat
- **cut**: Diamond cutting quality
- **color**: Diamond color ranging from J (worst) to D (best)
- **clarity**: Clarity measure from I1 (worst) to IF (best)
- **x**: Diamond length in mm
- **y**: Diamond width in mm
- **z**: Diamond depth in mm
- **depth**: Percentage depth (z / mean(x,y))
- **table**: Width of the widest point at the top of the diamond
- **price**: Target variable representing diamond price

## Objectives

1. Data Exploration: Analyze diamond attributes and their correlation with prices.
2. Model Development: Train machine learning models to predict diamond prices.
3. Evaluation: Assess model performance using appropriate metrics.
4. Insights: Extract meaningful insights for diamond valuation.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## How to Use

1. Clone the repository:
git clone https://github.com/wonderakwei/diamonds-price-prediction.git

2. Navigate to the project directory:
cd diamonds-price-prediction

3. Install required packages:
pip install -r requirements.txt

4. Run the Jupyter Notebook or Python scripts to explore and train models.

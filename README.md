# Water Quality Prediction Project 🌊💧
Overview

This project uses Artificial Intelligence (AI) and Machine Learning (ML) to explore and analyze water quality data. The aim is to identify potential unsafe water sources using parameters like pH, turbidity, and dissolved oxygen.

# Dataset

Source: Kaggle - Water Potability Dataset

Features: pH, Hardness, Solids, Chloramines, Sulfate, Conductivity, Organic Carbon, Trihalomethanes, Turbidity

Target: Potability (1 = Safe, 0 = Unsafe)

# Tools & Technologies

Python Libraries: Pandas, NumPy, Matplotlib, Seaborn

Project Workflow (Up to Heatmap)

Import Libraries – Load Pandas, NumPy, Matplotlib, Seaborn

Load Dataset – Read water_potability.csv into a DataFrame

# Explore Dataset

View first few rows (head())

Check dataset info (info())

Get statistical summary (describe())

Identify missing values (isnull().sum())

# Visualize Missing Values

Plot a heatmap to see missing data distribution using Seaborn

# Visualization Example

The heatmap shows where the dataset has missing values:

sns.heatmap(df.isnull(), cbar=False, cmap='viridis')
plt.title("Missing Values Heatmap")
plt.show()


This helps quickly identify columns that require data cleaning.

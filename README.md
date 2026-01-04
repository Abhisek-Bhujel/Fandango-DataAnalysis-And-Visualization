# Fandango Data Analysis & Visualization

## Overview
This project analyzes **rating bias in Fandango movie ratings** by comparing them with other major platforms such as **IMDb, Metacritic, and Rotten Tomatoes**.

Fandango’s primary business model is **movie ticket sales**, and prior analysis suggests that movies on Fandango are often rated **higher than on competing platforms**. Inflated ratings may influence users to purchase tickets and watch movies.

In addition, this project examines discrepancies between **Fandango’s backend ratings** and the **ratings displayed to customers**, where in some cases the difference is close to **one full star**.

---

## Objectives
- Compare Fandango ratings with IMDb, Metacritic, and Rotten Tomatoes
- Identify rating inflation across platforms
- Analyze differences between backend and customer-facing Fandango ratings
- Visualize rating distributions and relationships
- Detect patterns and clustering among movies

---

## Key Findings
- Fandango ratings are **consistently higher** than ratings from other platforms.
- In several cases, the **backend rating differs significantly from the displayed rating**.
- The rating gap between Fandango and other platforms is often **larger than one star**.
- These patterns suggest ratings may be adjusted in ways that align with **ticket sales incentives** rather than objective evaluation.

---

## Methodology
The analysis is performed using **Exploratory Data Analysis (EDA)** and visualization techniques, including:
- **Scatter plots** to examine relationships between platforms
- **Histograms** and **KDE plots** to analyze rating distributions
- **Difference analysis** to quantify rating inflation
- **Clustering techniques** to identify similarity patterns among movies

---

## Project Structure
Fandango-DataAnalysis-And-Visualization/
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb       # Data loading & preprocessing
│   ├── 02_eda.ipynb                  # Exploratory data analysis
│   └── 03_visualizations.ipynb       # Final visualizations
│
├── data/
│   ├── raw/                          # Original datasets
│   └── processed/                   # Cleaned datasets
│
├── figures/                          # Saved plots
│
├── README.md
└── requirements.txt

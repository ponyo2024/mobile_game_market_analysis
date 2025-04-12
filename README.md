# 🎮 Mobile Game Market Analysis (2020–2024)

Welcome to the repository for the **Data Mining Analysis of the Global Mobile Game Market**.  
This project explores trends, regional dynamics, and genre-specific patterns in the mobile gaming industry from **2020 to 2024**, using data mining techniques such as:

- Clustering (K-Means, Hierarchical, DBSCAN)  
- Predictive Modeling (Linear Regression)  
- Exploratory Data Analysis (EDA)  
- Principal Component Analysis (PCA)

> 🎯 The analysis provides **actionable insights** for **developers**, **publishers**, and **investors** navigating this competitive landscape.

---

## 🔍 Project Overview

The global mobile gaming market has expanded rapidly, driven by:

- Increasing **smartphone adoption**
- Technological **advancements**
- Shifting **player behaviors**

This project analyzes market trends from **2020 to 2024**, focusing on:

- **Global Trends**: Download and revenue patterns, with a forecast for **2025**  
- **Regional Analysis**: Country-level clustering to identify market archetypes (e.g., high-revenue vs. high-download countries)  
- **Game-Level Insights**: Clustering of games by **engagement (DAU)** and **monetization (RPD)**, correlated with genres  

The analysis leverages data from **Sensor Tower**, a leading mobile app analytics platform.

---

## 📂 Dataset

The dataset is sourced from **Sensor Tower** and includes:

- **Global Top 10,000 Apps by Revenue and Downloads (2020–2024)**  
  → 50,000 rows per metric (5 years × 10,000 apps)
  
- **Top 10,000 Apps by Revenue in 21 High-GDP Countries (2020–2024)**  
  → 1,050,000 rows (21 countries × 5 years)

> 📊 **Total**: 115 CSV files, **1.15 million rows**

### 🗃️ Key Columns

- `App Name`, `App ID`, `Publisher Name`, `Publisher ID`  
- `Platform`: iOS (App Store) or Android (Google Play)  
- `Downloads`, `Revenue (USD)`, `Average DAU`, `RPD (Revenue per Download)`  
- `Game Genre`: Puzzle, Strategy, Shooter, Simulation, Casino, etc.

> ⚠️ Note: Due to file size, only a **sample dataset** is included in this repository.  
> The **full dataset** is referenced in the final report.

---


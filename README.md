# 🎮 Global Mobile Game Market Analysis (2020–2024)

This project analyzes the global mobile game market from 2020 to 2024 using Sensor Tower data, focusing on downloads, revenue, clustering, and genre performance by country.

**Author**: Ji Weng  
**Last Updated**: March 23, 2025

---

## 📁 Dataset

- Source: Sensor Tower  
- Global top 10,000 apps by downloads & revenue (2020–2024)  
- Country-level app data for 21 high-GDP countries  
- Genre-level and app-level performance  
- Format: CSV, preprocessed in Python

📂 [Dataset folder](./datasets)

---

## 📊 Project Structure

### ✅ Global Macro Trends
- Global downloads dropped slightly; revenue stayed strong.
- US, China, and Japan dominate both volume and monetization.

### ✅ Country Clustering
- Clustering by 5-year trends and 2024 genre revenue.
- Identified 4 clusters:
  - 🟩 Revenue Giant (US)
  - 🟥 East Hardcore (China, Japan)
  - 🟨 Light Volume Hybrid (India, Brazil)
  - 🟦 Balanced Medium (Europe)

### 🚧 Deep Dive: Key Countries
- U.S. complete (genre trends, RPD, total growth).
- Japan, China, India, Brazil to be added.

### 🚧 App Clustering
- Clustered by Average DAU and Revenue Per Download (RPD).
- Profiles include:
  - 👑 Revenue Kings
  - 🐋 Whales
  - 🌍 Traffic Giants
  - 🎮 Casual Sailors

### 🔜 Predictive Modeling
- Forecast 2025 downloads & revenue using cluster insights.

---

## 📌 Key Insights

- Revenue ≠ Downloads: Monetization is market-specific.
- GDP explains ~45% of revenue variance (Spearman correlation).
- Strong genres vary by country cluster.

---

## 🔗 Links

- GitHub: https://github.com/ponyo2024/mobile_game_market_analysis  
- Dataset: https://github.com/ponyo2024/mobile_game_market_analysis/datasets

---

> Mid-term project for data mining — focused on real-world industry insight for publishers & analysts.

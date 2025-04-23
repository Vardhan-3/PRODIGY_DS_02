# PRODIGY_DS_02

# 🌍 Earth Land Cover Analysis – EDA Project

This project focuses on **Data Cleaning** and **Exploratory Data Analysis (EDA)** using a sample dataset on **Earth's land cover**. The goal is to explore environmental variables, detect data quality issues, and identify meaningful patterns in geographic and ecological trends.

## 🎯 Project Objective

- Clean and prepare raw land cover data for analysis
- Perform EDA to understand feature distributions and correlations
- Visualize spatial and categorical patterns in land cover types
- Derive actionable insights for environmental or policy research

---

## 📁 Dataset: Earth Land Cover

- **Dataset Used**: Sample data containing land cover classification for various geographic zones
- **Source**: [Specify if from Kaggle, government, or academic repo – or mark as sample/synthetic data]
- **Features Include**:
  - `Region`
  - `Land_Cover_Type` (e.g., forest, urban, water, agriculture)
  - `Area_sq_km`
  - `Elevation`
  - `Soil_Type`
  - `Vegetation_Index`

---

## 🛠 Tools & Technologies

- **Python**
- **Pandas** – Data cleaning & manipulation
- **Matplotlib / Seaborn** – Visualizations
- **Jupyter Notebook / Google Colab** – Interactive analysis

---

## 🔍 EDA Workflow

1. **Data Cleaning**
   - Handle missing values and duplicates
   - Standardize column names
   - Fix inconsistent category entries (e.g., "Forest", "forest", "FOREST")

2. **Univariate Analysis**
   - Distribution of `Land_Cover_Type`
   - Histogram of `Area_sq_km` and `Elevation`

3. **Bivariate & Multivariate Analysis**
   - Relationship between elevation and vegetation
   - Correlation between soil types and land cover
   - Region-wise land cover proportions

4. **Visualization**
   - Bar charts and pie charts for category distribution
   - Box plots to compare elevation across land cover types
   - Heatmaps for correlation matrices

---

## 📈 Sample Visualizations

![Land Cover Distribution](images/land_cover_distribution.png)

![Elevation vs Vegetation](images/elevation_vs_vegetation.png)

(*Replace or add your actual plots*)

---

## 🔎 Key Findings

- Forests dominate regions with high elevation and high vegetation index
- Urban areas are concentrated in low-elevation zones with poor vegetation
- Agricultural areas often align with specific soil types and mid-level elevations

(*Customize based on your findings*)

---

## 🚀 Future Work

- Incorporate satellite imagery metadata for deeper spatial analysis
- Build predictive models for land cover classification
- Integrate GIS tools like QGIS or Folium for geographic visualization

---

## 👨‍💻 Author

**The Data Sailor**  
🔬 Data Enthusiast | EDA Explorer | Environmental Insight Seeker  
📬 [Your LinkedIn or portfolio link]

---

## 📜 License

This project is open-source and intended for educational and research purposes. Dataset is assumed to be public or synthetic.

---


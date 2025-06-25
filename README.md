# 📱 Mobile Ownership Analysis (Ages 18–30) in Uganda

This project analyzes mobile phone ownership among individuals aged 18–30 across districts, sub-counties, and parishes in Uganda. It aims to identify gender-based disparities in access to mobile technology and support data-driven inclusion efforts.

---

## 📊 Features and Visualizations

### ✅ Descriptive Statistics
- Dataset overview including column types, null values, and distribution.
- Gender totals and summary metrics.

### ✅ Gender-Based Insights
- Pie chart of ownership by gender.
- Grouped bar charts per district.
- Diverging bar charts for sub-county level gaps.

### ✅ Geo-Visualizations
- Choropleth maps (static and interactive) of total ownership by district.
- Gender ratio maps using `GeoPandas`, `Plotly`, and `Folium`.

### ✅ Interactive Dashboards
- Sunburst and treemap for hierarchical ownership breakdown.
- Bubble plots showing population vs ownership with gender coloring.

### ✅ Advanced Analysis
- Gender disparity ratios.
- Sub-county and parish-level heatmaps.
- Elbow method and KMeans clustering of districts.
- "What-If" simulation: Additional phones needed to close the gender parity gap.

---

## 📁 File Structure

- `mobile_ownership_analysis_final.py`: Main analysis and visualization script.
- `cleaned_mobile_ownership_data.csv`: Required input dataset (not included here).
- `Uganda Districts 2020.geojson`: Required for mapping Ugandan districts.
- `/figs/mobile_ownership/`: Directory where output plots are saved.

---

## 🧰 Requirements

Install the dependencies using pip:

```bash
pip install pandas numpy matplotlib seaborn plotly geopandas scikit-learn folium

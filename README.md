 # 🗽🍽️ Locating Afghan Restaurants in New York

## Overview
This project explores the distribution and quality of Afghan restaurants in New York City to help Afghan asylum seekers and cuisine lovers find authentic food and potential business opportunities.

---

## Objectives
- 📍 Identify where Afghan restaurants currently exist in NYC
- 💡 Recommend areas with opportunities for new Afghan eateries
- 🏠 Help new immigrants find neighborhoods with access to familiar cuisine
- 📊 Use data-driven visualizations and geospatial analysis to support insights

---

## Data Sources
- **Neighborhood and Borough Info**
  - NYC Open Data: New York City Dataset
  - NYC Borough Boundaries (GeoJSON)
- **Restaurant Data**
  - Foursquare API (Python `requests` library)

---

## Methodology

### 1. Data Collection
- Collected and cleaned neighborhood and borough data
- Retrieved Afghan restaurant data from Foursquare

### 2. Filtering & Ranking
- Filtered venues by "Afghan Restaurant"
- Counted tips, likes, and ratings for each location
- Identified top-rated and most popular spots

### 3. Visualization
- Plotted distribution using bar charts
- Mapped restaurant ratings on NYC map with Folium & Choropleth maps

### 4. Analysis
- Compared boroughs based on average ratings
- Identified potential market gaps for Afghan cuisine

---

## Key Results

- Only **3 Afghan restaurants** were found via Foursquare:
  - **Afghan Kebab House II** (Lenox Hill, Manhattan) – *Highest rating (7.8)*
  - **Bakhter Afghan Halal Kababs** (Utopia, Queens) – *Most likes and tips*
- Manhattan had the best-rated restaurant
- Queens showed market potential with multiple but under-rated locations
- **Lenox Hill (Manhattan)** and **Ravenswood (Queens)** recommended for Afghan food lovers

---

## Tools & Libraries Used

- 🐍 Python: `pandas`, `requests`, `folium`, `matplotlib`
- 📡 Foursquare API
- 🗺️ NYC Open Data
- 🗂️ GeoJSON mapping

---

## Limitations

- Foursquare API returned only 3 Afghan restaurants despite multiple attempts
- Clustering and predictive modeling (e.g., K-Means) were constrained by limited data
- Data accuracy depends on crowd-sourced Foursquare content

---

## Conclusion

There’s a significant gap and opportunity for Afghan cuisine in NYC. For asylum seekers and entrepreneurs, this project highlights ideal locations to either **find** or **open** Afghan restaurants. While the data is limited, the approach demonstrates how open data and APIs can support real-world community needs.

---

Locating Afghan Restaurants in New York 🗽🍽️
Overview
This project explores the distribution and quality of Afghan restaurants in New York City to help Afghan asylum seekers and cuisine lovers find authentic food and potential business opportunities. With increasing immigration due to the conflict in Afghanistan, the goal is to identify neighborhoods best suited for Afghan restaurants and provide insights into where such businesses might thrive.

Objectives
Identify where Afghan restaurants currently exist in NYC

Recommend areas with opportunity for opening new Afghan eateries

Help new immigrants find neighborhoods with access to familiar cuisine

Use data-driven visualizations and geospatial analysis to support insights

Data Sources
Neighborhood and Borough Info:
New York City Dataset
NYC Borough Boundaries GeoJSON

Restaurant Data:
Retrieved using the Foursquare API via Python requests

Methodology
Data Collection:
Collected and cleaned neighborhood and borough data; retrieved Afghan restaurant data from Foursquare.

Filtering & Ranking:

Filtered venues by "Afghan Restaurant"

Counted tips, likes, and ratings for each restaurant

Identified top-rated and most popular spots

Visualization:

Plotted distribution using bar charts

Displayed restaurant ratings on NYC map with Folium & Choropleth maps

Analysis:

Compared boroughs based on average ratings

Identified potential market gaps for Afghan cuisine

Key Results
Only 3 Afghan restaurants were found via Foursquare:

Afghan Kebab House II (Lenox Hill, Manhattan) – Highest rating (7.8)

Bakhter Afghan Halal Kababs (Utopia, Queens) – Most likes and tips

Manhattan had the best-rated restaurant

Queens showed market potential with multiple but under-rated locations

Lenox Hill (Manhattan) and Ravenswood (Queens) were recommended for Afghan food lovers

Tools & Libraries Used
Python (Pandas, Requests, Folium, Matplotlib)

Foursquare API

NYC Open Data

GeoJSON mapping

Limitations
Foursquare API returned only 3 Afghan restaurants despite multiple attempts

Clustering and predictive modeling (e.g., K-Means) were constrained by limited data

Data accuracy is dependent on crowd-sourced Foursquare content

Conclusion
There’s a significant gap and opportunity for Afghan cuisine in NYC. For asylum seekers and entrepreneurs, this project highlights ideal locations to either find or open Afghan restaurants. While Queens shows promise for growth, Manhattan offers high visibility and better ratings.


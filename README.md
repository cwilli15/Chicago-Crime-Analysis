# 🕵️‍♂️ Chicago Crime Analysis  
### 📊 By: Christopher Williams

This project analyzes and visualizes crime trends in the city of Chicago using publicly available datasets from the City of Chicago. It utilizes Python geospatial libraries such as **GeoPandas**, **Folium**, and **Plotly** to map and interpret crime incidents by year and type.

---

## 📂 Dataset

- **Source**: [Crimes - 2001 to Present (City of Chicago)](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2)

---

## 🛠️ Tools & Libraries

- Python 3.10
- pandas / NumPy
- matplotlib / seaborn / plotly.express
- folium + HeatMap & MarkerCluster plugins
- geopandas / shapely / contextily
- shapefiles for base maps

---

## 🔍 Key Features

- ✅ Exploratory Data Analysis (EDA) on over 1 million crime reports  
- ✅ Focused comparison between crime distributions in **2019**, **2021**, and **2022**  
- ✅ **Heatmaps** and **MarkerClusters** for interactive crime mapping  
- ✅ Integration of **GeoPandas** with shapefiles for geographic plotting of major crime categories  
- ✅ Use of **Plotly** for interactive scatter plots by crime type  

---

## 🗺️ Sample Visuals

> 📍 *The following crime categories were visualized over Chicago’s street map base:*

- Homicide  
- Theft  
- Battery  
- Motor Vehicle Theft  
- Narcotics  
- Prostitution  
- Sex Offenses  

Each category is plotted with custom markers and colors, layered over OpenStreetMap/Stamen basemaps using Contextily and GeoPandas.

---

## 🧠 How to Run This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/chicago-crime-analysis.git
   cd chicago-crime-analysis

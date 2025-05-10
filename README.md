# Hexagon-Based Geospatial Analysis in Lima and Callao, Peru

This project focuses on generating and analyzing hexagons based on geospatial coordinates using district data from Lima and Callao, Peru. The implementation includes creating hexagonal grids and visualizing their distribution using Folium.

---

## 📦 Dataset

- **Source:** District dataset of Peru uploaded in Kaggle.
- **Format:** CSV.
- **Key Columns:**
  - `nombdep`: Department name.
  - `nombprov`: Province name.
  - `nombdist`: District name.
  - `geo_shape`: District geometry in WKT format.

---

## 🚀 Project Features

- **Hexagon Generation:** 
  - Generate configurable hexagons based on center coordinates and radius.

- **Map Visualization:** 
  - Visualize generated hexagons on an interactive map using Folium.
  - Hexagons are color-coded based on the district (`nombdist`) for easy identification.

- **Potential Applications:**
  - Population density analysis.
  - Service distribution mapping.
  - Identification of geospatial hotspots.

---

## 🛠️ Libraries and Tools

- **Pandas:** Data processing and CSV manipulation.
- **Shapely:** WKT geometry handling and spatial operations.
- **Folium:** Interactive map visualization.
- **Matplotlib:** Unique color assignment to each district.

---

## 📂 Project Structure
├── project-repo/
│   ├── mi_notebook.ipynb  # Main notebook with the implementation
│   ├── README.md          # Project documentation
│   └── data/
│       └── peru_districts_shape.csv  # Dataset used

🌐 Map Visualization
	•	The notebook generates an interactive map using Folium.
	•	You can explore hexagons and their characteristics directly in the notebook.


📌 Contact
	•	Author: Fidel Roman
	•	Email: fidel.roman@outlook.com
	•	LinkedIn: [linkedin.com/in/fidelroman](https://www.linkedin.com/in/fidelroman/)

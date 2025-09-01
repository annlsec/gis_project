# Geographic Information System Project
[🌎 View Project Website Here 🌎](https://annlsec.github.io/gis_project/)  

## Overview  
This project analyzes the relationship between **natural resources and conflict events** using geospatial methods. By combining conflict data (2022–2024) with global power plant locations, it applies clustering and spatial autocorrelation techniques (e.g., Moran’s I) to identify geographic patterns of conflict near resource sites.  

The analysis demonstrates skills in:  
- **Data wrangling and preprocessing** (CSV datasets of conflicts and resources).  
- **Geospatial analysis** (conflict clustering, spatial autocorrelation).  
- **Visualization** (interactive HTML maps, reproducible outputs).  
- **Reproducible workflows** (Quarto `.qmd` to generate a complete analysis pipeline).  


---

## Repository Structure 

```
.
├── README.md                     # Project overview and usage instructions
├── LICENSE                       
├── data/                         # Input datasets
│   ├── conflict_data_22_24.csv             # Conflict data (2022-2024)
│   └── global_power_plant_database.csv     # Global power plant locations
├── index.html                    # Main project output (analysis + visuals)
├── conflict_clusters_map.html    # Interactive map of conflict clusters
├── resources_clusters_map.html   # Interactive map of resource clusters
├── index_files/                  # Supporting files for HTML output
├── index.qmd                     # Quarto manuscript (code + narrative + visuals)
└── code.qmd                      # Code-only version for preview on GitHub
```

---

## How to Explore  

- **Main Output:**  
  - Open `index.html` in a browser to view the full analysis with explanations and visualizations.  
  - Or visit the [rendered project site](https://annlsec.github.io/gis_project/).  

- **Code:**  
  - `index.qmd`: Full Quarto manuscript (code + narrative).  
  - `code.qmd`: Code-only file (easy preview on Github).  

- **Interactive Visualizations:**  
  - `conflict_clusters_map.html`: Explore spatial clusters of conflict events.  
  - `resources_clusters_map.html`: Explore geographic distributions of resource sites.  

---

## Reproducing the Analysis  
1. Clone the repository.  
2. Open `index.qmd` in [Quarto](https://quarto.org/).  
3. Render the file to generate `index.html` and supporting outputs.  

This ensures all results are fully reproducible.  

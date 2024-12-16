# GIS Final Project
## Description
Analysis of the Relationship Between Natural Resources and Conflicts Using GIS

## File Structure
The repository is organized as follows:
```
.
├── README.md                     # Project overview and usage instructions
├── LICENSE                       # License information for the project
├── data/                         # Datasets used in the analysis
│   ├── conflict_data_22_24.csv       # Dataset containing conflict data (2022-2024)
│   └── global_power_plant_database.csv  # Dataset of global power plant locations
├── index.html                    # Main Quarto HTML output summarizing the project (MAIN FILE)
├── conflict_clusters_map.html    # Interactive map visualizing conflict clusters
├── resources_clusters_map.html   # Interactive map visualizing resource clusters
├── index_files/                  # Supporting files for HTML output (plots, assets)
└── index.qmd                     # Quarto manuscript containing the project code and text (MAIN FILE)
```

## How to Use the Files
- **Main Files:**
   - `index.html`: the **primary output of the project**. It contains a comprehensive summary of the analysis, including visualizations and results. Open this file in a web browser for a complete view of the project.
   - `index.qmd`: the **Quarto manuscript that generates `final_3.html`**. It includes all the code, narrative, and visualizations. Use this file to reproduce the analysis or make updates.

- **Other Files:**
  - data/: Contains datasets used for analysis.
    - `conflict_data_22_24.csv`: Raw conflict data covering the years 2022-2024. Use this file for analyzing conflict events.
    - `global_power_plant_database.csv`: Dataset of global power plant locations and details. Use this for resource-related analysis.

  - docs/: Includes HTML outputs and supporting files.
    - `conflict_clusters_map.html`: An interactive map visualizing conflict clusters. Open in a web browser to explore clusters interactively.
    - `resources_clusters_map.html`: An interactive map visualizing resource clusters. Open in a web browser for exploration.
    - `index_files/`: Contains supporting files for the HTML outputs, such as plots and other visual elements.


### Instructions for the Project:

1. **Open the Main Output**:
  - View the main analysis by opening `index.html` in your web browser.
  - This file contains all key findings, visualizations, and explanations.

2. **Reproduce the Analysis**:
   - Run `index.qmd` using Quarto to generate the `index.html` file.
   - This ensures all code and results are reproducible.

# India Climate and Ecological Change Analysis 

## Overview

This project investigates how India’s ecosystems are transforming under the dual pressures of climate change and deforestation. We analyze:

1. **Tree Cover Loss (2001–2023)** across Indian states and biodiversity hotspots.
2. **Climate Classification Shifts (1901–2100)** using Köppen-Geiger data across biogeographic zones and hotspots.

The aim is to build a strong data storytelling portfolio showcasing geospatial analysis, climate science understanding, and sustainable development insights.

---

## Repository Structure

```
india-climate-ecological-analysis/
│
├── India_Climate_TreeCover_Analysis.ipynb   
├── data/                                     
├── maps/                                     
├── README.md                                 
├── LICENSE                                   
├── .gitignore                               
└── requirements.txt             
```

---

## How to Run the Notebook

### Requirements

* Python 3.8+
* Jupyter Notebook or Jupyter Lab
* Required libraries (install via pip):

```bash
pip install geopandas pandas matplotlib seaborn folium plotly shapely ipywidgets
```

### To Run:

1. Clone this repository:

```bash
git clone https://github.com/Spag98/india-climate-ecological-analysis.git
cd india-climate-ecological-analysis
```

2. Open the notebook:

```bash
jupyter notebook India_Climate_TreeCover_Analysis.ipynb
```

3. Run cells step-by-step. Outputs like maps and charts will be displayed inline.

 **NOTE:** Large shapefiles and full datasets are NOT included in this repo. If needed, instructions for sourcing them will be added.

---

## Key Analyses

### Tree Cover Loss Analysis

* Year-wise tree cover loss across biodiversity hotspot states.
* Insights into the effectiveness of protection measures (e.g., Sikkim, Mizoram).
* Heatmaps and animated bar charts by threshold.

###  Köppen-Geiger Climate Classification Change

* Historical and projected shifts (1901–2100) in India's climate zones.
* Climate zone transitions within:

  * National boundaries
  * Biogeographic zones
  * Biodiversity hotspots
* Stacked graphs, heatmaps, and animated bar charts.
* Transition matrix (2001–2100) under high-emission scenarios.

---

## Insights Summary

### Tree Loss:

* Northeast states suffered the highest tree loss.
* Sikkim remains resilient due to strong community programs and strict regulations.
* Kerala shows loss outside Northeast due to population pressure and natural disasters.

### Climate Change:

* Shift from humid (Cwa) to tropical savanna (Aw) climate is dominant.
* Gangetic Plain and Indo-Burma regions see major transformation.
* Desertification visible in northwest (BWh expansion).
* High-altitude climates (Dfc, ET) shrink in Himalayas due to warming.

---

## SDG Alignment

The analysis supports these UN Sustainable Development Goals:

* **SDG 13: Climate Action** – Identifying vulnerable zones to support climate mitigation.
* **SDG 15: Life on Land** – Assessing biodiversity and forest degradation patterns.
* **SDG 11: Sustainable Cities & Communities** – Tracking land-cover loss around urban hotspots.
* **SDG 6 & 2** – Implications for water stress and food systems under changing climates.

---


[View biodiversity hotspot and protected areas folium map](maps/biodiversity_hotspots_protected_areas_in_India.html)

  [View map for tree loss in biodiversity areas](maps/tree_loss_biodiversity_map.html)

  [View Interactive Tree Loss Bar graph for each hotspot](maps/Annual_Tree_Cover_Loss_per_Biodiversity_Hotspots_animation.html)

  [View Interactive Tree Loss Bar graph for each state encompassing global biodiversity hotspots](maps/tree_cover_loss_animation.html)
  
  [View tree loss in Indian States at 10% threshold](maps/compare_tree_loss_10_by_state.png)

  [View tree loss at 15% threshold vs tree loss at 75% threshold](maps/compare_tree_loss_15_75.png)

  [View line plot for tree loss in northeastern states at 10% threshold](maps/line_plot_tree_loss_10_northeast.png)

  [View change in climate class area from 1901-2000](maps/climate_class_area_change_historical_data.png)

  [View bar graph animation of climate class area change in Gangetic planes ](maps/climate_zone_animation.gif)



## License & Data Use Disclaimer

This project is licensed under [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/).



### Dataset Usage

> This project integrates publicly available datasets. Each dataset has its **own license and citation requirement**. Please check individual terms before reuse. This project does **not grant permission** to redistribute original datasets.

---

## Acknowledgments

* **Köppen-Geiger climate classification** datasets by Rubel & Kottek.
* **Tree cover loss** datasets from Global Forest Watch.
* **India Biogeographic Zones** by Wildlife Institute of India.

This is an independent, non-commercial academic-style project for educational purposes.

---

## Author

**Shachi**  · Environmental & Geospatial Data Analyst

> Geospatial project blending climate science, biodiversity, geospatial analysis, and visual storytelling.

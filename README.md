# GIS AHP Solar Farm Suitability Assessment in Bogatić Serbia

This repository presents a GIS based multicriteria suitability assessment framework developed for the identification of favorable locations for solar farm development in the Municipality of Bogatić, Serbia.

The project integrates Geographic Information Systems (GIS), multicriteria decision analysis (MCDA), Analytic Hierarchy Process (AHP), raster based spatial modeling, and weighted overlay analysis in order to evaluate spatial suitability for photovoltaic energy infrastructure.

The workflow demonstrates how GIS based spatial intelligence approaches can support renewable energy planning, environmental decision support, and sustainable land use management.

# Project Objective

The primary objective of the study was to identify and spatially evaluate areas suitable for solar farm development using environmental, topographic, infrastructural, and land use criteria.

The analysis aimed to:

- identify highly suitable areas for photovoltaic energy development,
- integrate multiple spatial datasets into a unified GIS framework,
- evaluate the relative importance of spatial criteria using AHP,
- and generate a final suitability model using weighted raster overlay analysis.

# Study Area

The analysis was conducted within the administrative territory of the Municipality of Bogatić, Serbia.

The study area is characterized by:

- predominantly flat terrain,
- favorable solar irradiation conditions,
- agricultural land dominance,
- and relatively accessible transport infrastructure.

These characteristics make the municipality suitable for evaluating spatial conditions for solar energy development.

# GIS AHP Methodology

The spatial suitability framework integrated four primary criteria layers:

- Global Tilted Irradiation (GTI),
- terrain slope,
- land use / land cover (CLC),
- and proximity to road infrastructure.

All criteria were spatially standardized, reclassified into suitability classes, weighted using AHP, and integrated through weighted raster overlay analysis.

# Spatial Criteria

## 1. Global Tilted Irradiation (GTI)

Global Tilted Irradiation (GTI) represents the total incoming solar radiation received on a tilted surface and served as the primary energy related criterion within the suitability model.

GTI was considered the dominant factor because solar radiation directly determines the long term energy production potential of photovoltaic systems.

### GTI suitability logic

- higher solar irradiation → higher photovoltaic potential,
- lower solar irradiation → reduced energy efficiency.

### GTI suitability classes

| Class | GTI Range (kWh/m²/year) | Suitability |
|---|---|---|
| 1 | 1544–1549 | Very unfavorable |
| 2 | 1549–1552 | Unfavorable |
| 3 | 1552–1555 | Moderately favorable |
| 4 | 1555–1558 | Favorable |
| 5 | >1558 | Very favorable |

## 2. Terrain Slope

Slope analysis was derived from the EUDEM digital elevation model.

Terrain slope directly affects:

- construction feasibility,
- installation stability,
- terrain preparation requirements,
- and long term maintenance costs.

### Slope suitability logic

- flat terrain → highly suitable,
- moderate slopes → conditionally suitable,
- steep terrain → unfavorable.

### Slope suitability classes

| Class | Slope (°) | Suitability |
|---|---|---|
| 1 | 10–90 | Very unfavorable |
| 2 | 6–10 | Unfavorable |
| 3 | 4–6 | Moderately favorable |
| 4 | 2–4 | Favorable |
| 5 | 0–2 | Very favorable |

## 3. Land Use Land Cover (CLC)

Land use suitability was evaluated using CORINE Land Cover (CLC) data.

The analysis considered physical, environmental, and functional compatibility of different land cover categories with photovoltaic infrastructure development.

### Highly suitable categories

- agricultural land,
- mixed agricultural areas,
- sparsely vegetated zones.

### Restricted or unfavorable categories

- forests,
- wetlands,
- urban areas,
- water bodies,
- recreational zones.

### Land use suitability logic

Land cover categories were evaluated according to:

- environmental compatibility,
- construction feasibility,
- land use restrictions,
- and spatial sustainability considerations.

## 4. Distance to Roads

Distance to state roads was included as an infrastructural criterion associated with:

- construction accessibility,
- transportation logistics,
- operational efficiency,
- and economic feasibility.

### Distance suitability logic

- shorter distance to roads → higher suitability,
- greater remoteness → increased infrastructure costs.

### Distance suitability classes

| Class | Distance (m) | Suitability |
|---|---|---|
| 1 | 5000–15000 | Very unfavorable |
| 2 | 2000–5000 | Unfavorable |
| 3 | 1000–2000 | Moderately favorable |
| 4 | 500–1000 | Favorable |
| 5 | 0–500 | Very favorable |

# Analytic Hierarchy Process (AHP)

The relative importance of all criteria was evaluated using the Analytic Hierarchy Process (AHP).

Pairwise comparison matrices were constructed in order to define criterion priorities within the final suitability model.

The weighting process enabled systematic integration of environmental, technical, and infrastructural criteria into a unified GIS based decision support framework.

## Final AHP Weights

| Criterion | Weight |
|---|---|
| Global Tilted Irradiation (GTI) | 56.71% |
| Terrain Slope | 26.51% |
| Land Use Land Cover (CLC) | 11.48% |
| Distance to Roads | 5.31% |

The consistency ratio (CR = 0.089) was below the accepted threshold of 0.1, confirming acceptable consistency of expert judgments within the AHP framework.

# Weighted Overlay Analysis

All criteria layers were:

- reclassified into standardized suitability classes,
- spatially aligned,
- weighted according to AHP coefficients,
- and integrated using weighted raster overlay analysis.

The final suitability model was calculated using the following equation:

Suitability =(GTI × 0.5671) + (Slope × 0.2651) + (CLC × 0.1148) +  (Roads × 0.0531)

The resulting raster identified areas ranging from highly suitable to unsuitable for solar farm development.

# Results

The analysis identified multiple spatial clusters with favorable conditions for photovoltaic energy development within the Municipality of Bogatić.

The most suitable areas were characterized by:

- high solar irradiation,
- flat terrain,
- compatible land use,
- and proximity to transportation infrastructure.

The final suitability model demonstrated that a significant portion of the municipality belongs to favorable and very favorable suitability categories.

The results also confirmed the dominant influence of solar irradiation and terrain morphology within the overall suitability framework.

# Software and Methods

## GIS and Spatial Analysis

- QGIS
- Raster analysis
- Weighted overlay analysis
- Terrain analysis
- Spatial reclassification
- Cartographic visualization

## Analytical Methods

- MCDA
- AHP
- Raster suitability modeling
- Spatial decision support analysis

# Repository Contents

- Solar suitability assessment maps
- Reclassified criteria layers
- Weighted overlay outputs
- AHP tables and charts
- GIS visualizations
- Spatial suitability analysis outputs

# Scientific and Practical Relevance

This repository demonstrates how GIS based multicriteria spatial analysis can support:

- renewable energy planning,
- environmental suitability assessment,
- spatial decision support,
- sustainable land use planning,
- and strategic photovoltaic infrastructure development.

The workflow may also serve as a methodological framework for future GIS based renewable energy and environmental planning studies.

# Contact

For additional methodological details, collaboration opportunities, or GIS related research inquiries, feel free to connect with me on LinkedIn.

[LinkedIn Profile](https://linkedin.com/in/jelena-lukic-bb84232b5)

# Author

Jelena Lukić  
Environmental Monitoring Specialist | GIS & Spatial Analytics

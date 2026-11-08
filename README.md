# river-proximity-settlement-analysis
Project overview

This project examines the spatial relationship between river networks and nearby settlements using QGIS. A 200 meter buffer was generated around river networks to identify settlement locations within the defined proximity zone.

Objectives
- Map river networks within the study area.
- Generate 200-meter river buffer zones.
- Identify settlements intersecting the buffer.
- Calculate administrative area.
- Examine settlement distances from the nearest river.
- Create a final map showing river proximity and settlement distribution.

Data sources
The project uses geographic datasets from:
- OpenStreetMap (OSM): River networks and settlement locations.
- Administrative boundaries: Used to define the study area.

Tools and Techniques
Software: QGIS
Spatial analysis tools:

- Buffer
- Clip
- Extract by Location
- Dissolve
- Join Attributes by Nearest
- Field Calculator
  
Methodology
1. Data acquisition and preparation.
2. Coordinate reference system transformation.
3. River network clipping.
4. Settlement clipping.
5. 500-metre buffer generation.
6. Settlement extraction by location.
7. Nearest-river distance calculation.
8. Cartographic visualization.

Results
The analysis produced a 200-meter river buffer and identified settlement locations falling within that zone. It also generated nearest-river distance information and administrative area measurements. The final map visualizes the spatial relationship between rivers and nearby settlements within the selected study area.

Limitations
The analysis identifies settlement locations near rivers but does not independently establish flood hazard or flood risk. The results depend on the completeness and accuracy of the available OpenStreetMap data.

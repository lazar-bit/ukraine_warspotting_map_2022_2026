# ukraine_warspotting_map_2022_2026

## Overview

This repository contains an **interactive Kepler.gl map** visualizing geolocated Russian equipment losses in Ukraine based on **WarSpotting OSINT data** during 2022–2026.  
The map aggregates confirmed losses into **3D Hexbin layers**, allowing users to explore spatial patterns and hotspots of equipment destruction during the ongoing war.

The purpose of this project is **academic, OSINT, and research-focused** visualization of visually confirmed equipment losses to support analysis of conflict dynamics, spatial intensity, and temporal trends.

---

## Features

- **Interactive 3D Hexbin map** of geolocated equipment losses  
- **Aggregated spatial visualization** highlighting loss concentrations  
- **Zoomable and interactive exploration** of battlefield destruction patterns  
- **Color and elevation** scaled by the number of confirmed losses  
- **Desktop-optimized view**  

---

## Usage

### 1. Live Map

Access the interactive map on GitHub Pages:

[Click here to view the WarSpotting Hexbin map](https://lazar-bit.github.io/ukraine_warspotting_map_2022_2026/warspotting_ukraine_hex.html)

> **Note:** For optimal performance, use a desktop browser. Mobile devices may not render large 3D Hexbin layers due to WebGL limitations.

---

### 2. Data

- **Source:** WarSpotting OSINT project  
- **Coverage:** Ukraine, 24 February 2022 – 2026  
- **Format:** Geolocated equipment loss dataset processed in Kepler.gl  
- **Visualization:** Hexbin layer with elevation and color scaled by confirmed loss counts  

WarSpotting compiles visually confirmed losses of military equipment based on photographic and video evidence collected through open-source intelligence.

---

## Technical Notes

- **Visualization tool:** Kepler.gl  
- **Map Hosting:** GitHub Pages  
- **Basemap:** Mapbox GL JS  
- **Browser Recommendations:** Desktop Chrome/Firefox/Safari for full 3D interactive experience  

---

## References

- WarSpotting: https://warspotting.net  
- Kepler.gl: https://kepler.gl  
- Mapbox GL JS: https://docs.mapbox.com/mapbox-gl-js  

---

## Disclaimer

This visualization is **for research and educational purposes only**.

WarSpotting data represent **visually confirmed equipment losses** based on open-source evidence. The dataset does not capture all battlefield losses and should therefore be interpreted as a **partial but verified record of destruction** rather than a complete inventory of military losses.

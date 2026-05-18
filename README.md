# drone-attacks-latin-america
Analysis of drone weaponization by non-state armed groups in Latin America (2021–2026)
# From Ukraine to the Favelas: Drone Weaponization by Non-State Armed Groups in Latin America (2021–2026)

## Overview
This project maps and analyzes the use of weaponized drones by non-state armed groups 
in Latin America, mostly Brazil, Mexico, and Colombia. It argues that drone 
adoption follows a traceable diffusion pattern that accelerates significantly from 2024 onward.

## Key Findings
- Security forces are the primary target, accounting for 15 of 30 documented incidents
- Mexico was the pioneer, with documented attacks from 2021 onward
- Brazil and Colombia appear in 2024, suggesting regional diffusion
- Incidents nearly double between 2023 and 2024, and spike further in 2025

## Data
Incidents were manually collected from open sources including InSight Crime, 
El Tiempo, Gazeta do Povo, and El Universal, among others. The dataset covers 
30 documented incidents across three countries.

## Files
- `incidentes_drones.xlsx` — incident database with sources
- `02_analysis.ipynb` — full analysis notebook
- `mapa_drones_en.html` — interactive map (open in browser)
- Charts available in English and Portuguese

## Methodology
This project uses Python (pandas, matplotlib, folium) for data analysis and 
visualization. Geocoding was performed with geopy/Nominatim.

## Reproducing the Analysis

```bash
pip install -r requirements.txt
jupyter notebook 02_analysis.ipynb


## Author
Lisiane Alves dos Santos — security analyst

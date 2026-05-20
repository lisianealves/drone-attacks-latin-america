# From Ukraine to the Favelas: Drone Weaponization by Non-State Armed Groups in Latin America (2021–2026)

## Overview
This project analyzes the growing use of weaponized commercial drones by non-state armed groups in Latin America between 2021 and 2026.
Using manually collected OSINT data, the project identifies emerging regional diffusion patterns, operational trends, and target preferences across Brazil, Mexico, and Colombia.

## Key Findings
- Security forces were the primary targets, representing 50% of documented incidents.
- Mexico emerged as the earliest adopter of drone-based attacks, with incidents documented since 2021.
- The appearance of incidents in Brazil and Colombia from 2024 onward suggests a regional diffusion process.
- Incident frequency accelerated significantly after 2023, indicating growing operational normalization among armed groups.

## Data
Incidents were manually collected from open sources including InSight Crime, 
El Tiempo, Gazeta do Povo, and El Universal, among others. The dataset covers 
30 documented incidents across three countries.

## Limitations
The dataset is based exclusively on publicly reported incidents and may underrepresent the true scale of drone weaponization in the region. Differences in media coverage, government transparency, and reporting standards between countries may affect incident visibility.

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
```

## Author
Lisiane Alves dos Santos — OSINT and security analysis researcher

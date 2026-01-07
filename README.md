# 🏛️The Roman Empire of Airbnb: A Spatial Analysis
An in-depth exploration of Rome's short-term rental market, price distributions, and geographic density.

## Project Overview
This project analyzes the Airbnb landscape in Rome, Italy, using a combination of spatial data science and market analytics. By overlaying individual listing data onto administrative choropleth maps, this study identifies the correlation between geographic density and pricing tiers across the city.

 ## Key Findings:
 ### The Price Gradient (Red to Blue)
* **The Blue Core:** High-density, premium pricing ($€€€$) concentrated in the *Centro Storico* and *Prati*.
* **The Red Frontier:** Budget-friendly clusters found in peripheral regions like *San Giovanni* and *Centocelle*.
### The Rise of the "Business Host"
While casual hosts exist, the data reveals a heavy professionalization of the market.
* **Consolidated Power:** There are significantly more listings owned by "Business Hosts" (those with 2+ properties) than by casual hosts. 
* **Inventory Control:** A minority of professional hosts control the majority of the city's inventory, moving the platform away from its "side-hustle" roots.

### The Death of the "Shared Room"
Airbnb’s original purpose was to share a spare room, but Hosts in Rome has moved in a different direction.
* **Whole Apartment Dominance:** Rentals for entire apartments vastly outnumber shared or private rooms.
* **Commercialization:** The market is now a decentralized hotel industry, with travelers and hosts prioritizing full-unit commercial rentals over shared living experiences.

 ## Data Pipeline
This repository contains the full end-to-end workflow:

### Data Cleaning
- Handling missing values in listing descriptions and pricing.
- Filtering outliers (Ghost Listings).
- Geocoding and administrative boundary mapping using GeoPandas.

### Exploratory Data Analysis (EDA):
- Distribution analysis of room types (Entire homes vs. Private rooms).
- Price volatility across Rome's 15 Municipi.

### Visualization:
- Choropleth Maps: Visualizing median prices with a Red (Cheap) to Blue (Expensive) divergent scale.
- Point Density Plots: Mapping individual listings to show urban saturation.
- Tools : Tableau and Python
# How a Phase Shift Reshaped Mo'orea's Fish Communities

An infographic and blog post exploring how fish functional group abundance changed at Mo'orea's LTER 1 backreef between 2006 and 2024, as coral cover declined and *Turbinaria ornata* emerged as the dominant benthic organism.

## About

Coral reefs worldwide are undergoing phase shifts from coral-dominated to macroalgae-dominated states. This project uses 20 years of long-term monitoring data from the MCR LTER to track benthic cover and fish functional group abundance at the LTER 1 backreef in Mo'orea, French Polynesia. The goal is to identify how fish community composition reorganizes in response to benthic change.

## Repository Structure

```
├── data/
│   ├── MCR_LTER_Annual_Fish_Survey_20250324.csv                  # MCR LTER fish functional group data
│   └── MCR_LTER_Coral_Cover_Backreef_Long_20260219.csv           # MCR LTER benthic cover data
├── img/
│   ├── infographic.png                                           # Final infographic
│   ├── benthic_plot.png                                          
│   ├── dumbbell_plot.png         
│   └── functional_groups_plot.png
├── index.qmd                      # blog post + design decisions
├── index.html                     # Rendered GitHub Pages output
└── README.md
```

## Data

Data are sourced from the **MCR LTER Long-term Population and Community Dynamics** program, ongoing since 2005:

- **Fish data:** MCR LTER Long-term Population and Community Dynamics: Fishes — annual survey of fish functional group abundance at LTER 1 backreef
- **Benthic data:** MCR LTER Long-term Community Dynamics, Backreef (Lagoon) Corals Annual Survey

Data are publicly available at the [MCR LTER Data Portal](https://mcrlter.msi.ucsb.edu/).

## Author

**Joaquin Sandoval**  
Master of Environmental Data Science Student UC Santa Barbara

## Acknowledgements

- Data provided by the [Moorea Coral Reef Long Term Ecological Research site (MCR LTER)](https://mcrlter.msi.ucsb.edu/), funded by the National Science Foundation
- Course: EDS 240 — Data Visualization & Communication, UCSB MEDS
- Infographic designed in [Affinity Designer](https://affinity.serif.com/en-us/designer/)

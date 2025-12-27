# Animal-Farming Climate Causal Framework — Code & Analysis Index

Index repository linking code and analyses supporting a causal framework
for animal-farming-driven climate, environmental, and health impacts.

---

## Overview
This repository serves as a central index to the original code and analyses
supporting a manuscript on causal attribution linking animal farming to
climate change, land-use change, biodiversity loss, and health risks.

Analyses are distributed across multiple dataset-specific repositories,
each containing its own data, scripts, outputs, and documentation.

The work integrates environmental, socio-economic, and health datasets
to support a systems-based and causal understanding of livestock-driven
impacts within coupled social–ecological systems.

---

## Causal framework
Analyses are organized around the following conceptual decomposition of
total climate-related impacts:

**E_total = E_enteric + E_manure + E_feed/soils + E_LUC + E_energy − R_sequestration/opportunity**

This expression represents a **causal accounting framework** rather than
the output of any single dataset. Individual components are informed by
distinct empirical sources, including land-use change, supply-chain
emissions, biodiversity indicators, and downstream health outcomes.

---

## Cross-reference summary

| Main-manuscript item | Framework component(s) | Scope / boundary | Primary data |
|--------------------|------------------------|------------------|--------------|
| Fig. 1 | E_LUC, E_feed/soils | Biodiversity impacts; 1970–2014 | NHM Biodiversity Trends Explorer (PREDICTS); FAO Livestock Landscapes (contextual) |
| Fig. 2 | Downstream health externality | EU/EEA confirmed cases; 2022–2024 | ECDC Surveillance Atlas |
| Fig. 3 | E_LUC | Trade-driven land-use change; 2018–2022 | Singh et al. (2024); FAOSTAT feed-use shares |
| Fig. 4 | E_energy (consumption-based) and aggregated E_feed/soils | Household + NPISH + Government; 2020–2022 | EXIOBASE 3; World Bank WDI |

---

## Mapping of analyses to framework components

### Biodiversity loss and land-use impacts
**Framework components:** E_LUC, E_feed/soils

**Repository:**  
https://github.com/GEC-Research/Biodiversity-loss-and-Land-use-due-to-Animal-Agriculture  

**Description:**  
Analysis of biodiversity loss and land-use impacts associated with animal
agriculture, integrating biodiversity intactness and agricultural land-use
datasets. These analyses provide biophysical evidence for land-based pressures
within the causal framework rather than direct emissions estimates.

**Key data sources:**  
- Biodiversity Intactness Index (NHM / PREDICTS)  
- FAO livestock and cropland statistics  

---

### Zoonotic and foodborne disease impacts
**Framework component:** Downstream health externality

**Repository:**  
https://github.com/GEC-Research/Zoonotic-foodborne-diseases-ECDC-Europe-data  

**Description:**  
Analysis of zoonotic and foodborne disease incidence in Europe, providing
evidence of downstream health risks associated with intensive livestock
systems, land-use change, and biodiversity disruption.

**Key data sources:**  
- European Centre for Disease Prevention and Control (ECDC) Surveillance Atlas  

---

### Land-use change emissions
**Framework component:** E_LUC

**Repository:**  
https://github.com/GEC-Research/Land-use-Change-Emissions-including-peat-drainage  

**Description:**  
Analysis of land-use-change emissions associated with commodity-driven
deforestation and peat drainage linked to agricultural production,
including livestock feed and pasture expansion.

**Key data sources:**  
- Commodity-driven deforestation and emissions (Singh et al., 2024)  
- FAOSTAT cropland and land-use data  

---

### Consumption-based supply-chain emissions
**Framework components:** E_energy (consumption-based) and aggregated E_feed/soils

**Repository:**  
https://github.com/GEC-Research/Consumption-Based-Emissions-due-to-Animal-Farming  

**Description:**  
Consumption-based accounting of supply-chain emissions associated with
animal farming, allocated to final demand using multi-regional input–output
analysis. Biological process emissions (e.g., enteric fermentation and
manure management) are not explicitly quantified here and are treated
conceptually within the framework.

**Key data sources:**  
- EXIOBASE 3 multi-regional input–output database  
- World Bank World Development Indicators  

---

## Data availability
All analyses rely exclusively on publicly available datasets. Each linked
repository contains detailed information on data access, processing,
and outputs.

---

## Code availability
All code used in the analyses is available via the linked repositories above
and can be accessed anonymously without login. Each repository includes its
own README with dataset-specific documentation.

---

## Notes for reviewers
Analyses are intentionally separated by dataset to reflect differences in
data structure, spatial and temporal coverage, and causal mechanisms. The
framework integrates heterogeneous evidence without implying that all
components are quantified within a single dataset.

# Homework 2 – Redlining and Biodiversity in Los Angeles 
*EDS 223: Geospatial Analysis & Remote Sensing*
*UCSB Masters of Environmental Data Science*

## Purpose  
This repository contains the workflow, data, and outputs for Homework 2 of EDS 223, completed by Melannie Moreno Rolón. The project explores environmental justice in Los Angeles, California, using the EPA EJScreen (2023), HOLC, and Biodiversity observations datasets. Specifically, it examines how Home Owners’ Loan Corporation (HOLC) grades from the 1930s spatially overlap with modern census block groups and explores disparities in environmental exposure and biodiversity sampling across these areas. The analysis was conducted in R using spatial data visualization tools and presented in a Quarto document.

## Description of Repository
This repository contains spatial and statistical analyses exploring links between redlining, pollution, and biodiversity in Los Angeles. 
It integrates environmental and socioeconomic datasets using R to examine the long-term impacts of historical housing policies on present-day environmental justice and ecological sampling patterns.

## Repository Structure
>C:.
│   .gitignore
│   .Rhistory
│   EDS223-2025-Homework-2.Rproj
│   ej_screen_patterns.qmd
|   ej_screen_patterns.pdf
│   HW2.rmarkdown
│   LICENSE
│   README.md
│
└───data
    ├───ejscreen
    │
    ├───gbif-birds-LA
    │
    └───mapping-inequality

## Repository Contents

- data/ (Contains the ejscreen geodatabase used for the assignment)
- HW2.qmd  (Quarto document with the code and interpretation)
- HW2.pdf (Rendered PDF output of Quarto document with maps and conclusions)
- README.md (This file)
- LICENSE (MIT License)

## Data Access

EJScreen 2023: Sourced from the U.S. Environmental Protection Agency. The geodatabase file EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb is stored locally in the data/ folder.

HOLC Redlining Data: Digitized by the Digital Scholarship Lab at the University of Richmond as part of the Mapping Inequality project. The Los Angeles HOLC dataset (mapping-inequality-los-angeles.json) is stored in the data/ folder.

Bird Biodiversity Observations: Sourced from the Global Biodiversity Information Facility (GBIF). The shapefile gbif-birds-LA.shp contains bird observations from 2021 onward and is stored in the data/ folder.

To run the code, ensure you have the required R packages installed (sf, tmap, tidyverse, here, tinytex).

## Acknowledgements
This project was made possible through the use of publicly available datasets and tools developed by leading organizations and researchers committed to environmental transparency and open science.

- EJScreen 2023 data was sourced from the U.S. Environmental Protection Agency. Although the official tool is no longer active, historical data remains accessible thanks to the Public Environmental Data Project’s unofficial EJScreen viewer.

- HOLC redlining maps were provided by the Mapping Inequality project, led by the Digital Scholarship Lab at the University of Richmond. Their work in digitizing and preserving historical redlining records has been instrumental in enabling spatial justice research.

- Bird biodiversity observations were obtained from the Global Biodiversity Information Facility (GBIF), the world’s largest aggregator of species occurrence data. We acknowledge the contributions of community scientists and institutions who continue to share biodiversity records.

Special thanks to the developers and maintainers of the R packages used in this analysis, including {sf}, {tmap}, {tidyverse}, {here}, and {tinytex}, which enabled spatial data processing, visualization, and reproducible reporting in Quarto.

Finally, this work was completed as part of EDS 223 at the University of California, Santa Barbara, under the guidance of course instructor Annie Adams and TA Alessandra Vidal Meza who provided valuable feedback and direction.

## Citations

Public Environmental Data Project. (n.d.). Unofficial EJScreen Viewer. Retrieved October 18, 2025, from https://pedp-ejscreen.azurewebsites.net/

Digital Scholarship Lab. (n.d.). Mapping Inequality: Redlining in New Deal America. University of Richmond. Retrieved October 18, 2025, from https://dsl.richmond.edu/panorama/redlining/#loc=5/39.1/-94.58

Global Biodiversity Information Facility. (n.d.). GBIF Home. Retrieved October 18, 2025, from https://www.gbif.org/

## Author  
- [Melannie Moreno Rolón](https://github.com/mmorenorolon)

## License
This repository is distributed under the [MIT License](LICENSE)

# Final-Project
This repository is for my final project for the CLMTG5053 Computing and Research Methods course

# Project Proposal:

## Scientific Question:
How does the rate of land use change vary by country and region between 2001 and 2021? Which countries are leading with regard to converting tree, shrub, and herbaceous land to 1) developed land and 2) sparsely vegetated land?

## Hypothesis:
Land use change has accelerated globally over the 2001 and 2021 period, with land use change increasing the fastest in Sub-Saharan Africa, Southeast Asia, and South America.  Ethiopia, Nigeria, South Africa, Tanzania, China, and Saudi Arabia will have the fastest rates of conversion to developed land in the last ten years (2011-2021), due to development pressures. Countries in the Sahel region of Africa (Mali, Niger, Chad, Sudan, and Mauritania), India, and Australia will have the fastest rates of conversion to sparsely vegetated land in the last ten years (2011-2021). 


## Links to Relevant Datasets:
[NASA GLanCE Yearly 30m Dataset](https://www.earthdata.nasa.gov/data/catalog/lpcloud-glance30-001)

[User Guide for GLanCE Yearly 30m Dataset](https://lpdaac.usgs.gov/documents/2401/GLanCE_UserGuide_v1.1.pdf) -> contains information about parameters in the dataset

Geopandas package Python -> I hope to use this package to allow me to clip the data to country boundaries for a country-level analysis

## Summary of Planned Analysis: 
I plan to use the NASA Global Land Cover Mapping and Estimation (GLanCE) annual global land cover and land cover change data to analyze country-level rates of change by clipping the dataset to country boundaries using geopandas. I will analyze rate of change by leveraging the land cover class and previous land cover class data to calculate the amount of area per year that has changed from vegetated land (tree, shrub, herbaceous) to 1) developed and 2) sparsely vegetated land. I plan to show rates of change over time by country and/or region in a line graph for both developed and sparsely vegetated land and a map of total country-level change to these two land types over the last ten years. I would also like to aggregate total change at the regional level in a bar chart to enable regional comparison. 


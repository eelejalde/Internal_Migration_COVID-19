# Internal_Migration_COVID-19
Data for the analysis of the social stratification of internal migration and daily mobility  during the COVID-19 pandemic

## Long-term relocation
We study the dynamics of internal migration within a country by analyzing eight months of anonymized eXtended Detail Records (XDRs) for three years (2017, 2020, and 2022) for approximately 1.3M mobile phones in Santiago de Chile (SCL, population: ~8.1M). For each device, we calculated its home location per week from Mar 1<sup>st</sup> until Nov 30<sup>th</sup> of each year. If the statistical model of home in the four weeks of November was in a different region than their March home, we assumed that the device had migrated.

The datasets shared in this repository contain the aggregated number of devices that emigrated from comunas in SCL (salientesRM_comunas_\[year\].csv) and devices that immigrated to comunas in SCL (entrantesRM_comunas_\[year\].csv).

## Daily mobility
For this short-term mobility analysis, we use a dataset of XDRs collected for the same population (i.e., comunas in SCL) in 2020 [1]. From the XDRs, the authors produce three epidemiologically relevant metrics: the Index of Internal Mobility, which quantifies the amount of mobility within each comuna of the country; the Index of External Mobility, quantifying the mobility between comunas; and the Index of Mobility (IM), which considers any movement, both within and between comunas. The data used to calculate the daily mobility index, as well as the active quarantine periods, are available for download from the general repository of the Ministry of Science of Chile
 - [Mobility per comuna](https://github.com/MinCiencia/Datos-COVID19/tree/master/output/producto33)
 - [Quarentine periods per comuna](https://github.com/MinCiencia/Datos-COVID19/tree/master/output/producto29)

[1] L Pappalardo, G Cornacchia, V Navarro, L Bravo, L Ferres, A dataset to assess mobility 655 changes in Chile following local quarantines. Sci Data 10 (2023)

## Socioeconomic aspects 
Our primary source for the socioeconomic metrics is the Socioeconomic Characterization Survey (CASEN) which is the main household survey in Chile. From the CASEN, we obtain estimates for the average income decile, the percentage of poverty per comuna, and the rurality index.
Additionally, we use the Index of Quality of Life in Urban Areas (ICVU). ICVU is a synthetic index employed to assess and compare the relative quality of urban life in Chilean comunas and cities.
 - [CASEN 2020](https://www.desarrollosocialyfamilia.gob.cl/informacion-social/casen-pandemia-2020)
 - [ICVU](https://estudiosurbanos.uc.cl/10-anos-calidad-de-vida-urbana-icvu-2020/)

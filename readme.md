# Covid 19 Clustering and Effects on Disabled Communities in August, 2020

## Contributors

- Lucas Nerbonne, lnerbonne@middlebury.edu, Middlebury College Earth and Climate Sciences Department

## Abstract

This is a attempted partial reproduction study of J. Chakraborty's 2021 study 'Social inequities in the distribution of COVID-19: An intra-categorical analysis of people with disabilities in the U.S.'. In it, I'll first copy Chakraborty's workflow extracting the covid incidence rate for different disability demographic groups, assessing the correlation between county-level case incidence and the population of these demographics. Then we'll deviate from Chakraborty's work by clustering county-level cases using kulldorf spatial filtering to generate case clusters to get a better idea of the spatial organization of disease spread at this point in the pandemic. 

## Study Metadata

- `Key words`: Covid19, Epidemiology, Disease Spread, Disabled Populations, Mobility
- `Subject`: Epidemiology, Demographic Research
- `Date created`: 2025-03-5
- `Date modified`: 2020-03-5
- `Spatial Coverage`: United States (Country)
- `Spatial Resolution`: Counties
- `Spatial Reference System`: EPSG:4269 NAD 1983 Geographic Coordinate System
- `Temporal Coverage`: August 2020
- `Temporal Resolution`: County-Level Incidence Rate, Averaged from Weekly Data

## Metadata for access

- `Rights`: [LICENSE](LICENSE): BSD 3-Clause "New" or "Revised"
- `Resource type`: Collection
- `Resource language`: English
- `Conforms to`: Template for Reproducible and Replicable Research in Human-Environment and Geographical Sciences version 1.0, DOI:[10.17605/OSF.IO/W29MQ](https://doi.org/10.17605/OSF.IO/W29MQ)

## Compendium structure and contents

This research compendium is structured with four main directories:

- `data`: contains subdirectories for `raw` data and `derived` data.
- `docs`: contains subdirectories for `manuscript`, `presentation`, and `report`
- `procedure`: contains subdirectories for `code` or software scripts, information about the computational `environment` in which the research was conducted, and non-code research `protocols`
- `results`: contains subdirectories for `figures`, formatted data `tables`, or `other` formats of research results.

The data, procedures, and results of this repository are outlined in three tables:
- Data: [data/data_index.csv](data/data_index.csv)
- Procedures: [procedure/procedure_index.csv](procedure/procedure_index.csv)
- Results: [results/results_index.csv](results/results_index.csv)

Important local **documents** include:
- Pre-analysis plan: [docs/report/preanalysis.pdf](docs/report/preanalysis.pdf)
- Study report: [docs/report/report.pdf](docs/report/report.pdf)
- Manuscript: [docs/manuscript/manuscript.pdf](docs/manuscript/manuscript.pdf)
- Presentation: [docs/presentation/presentation.pdf](docs/presentation/presentation.pdf)

#### Compendium reference

The [template_readme.md](template_readme.md) file contains more information on the design of this template and references used in the design.
The [Template_LICENSE](Template_LICENSE) file provides the BSD 3-Clause license for using this template.
To cite the template, please use [template_reference.bib](template_reference.bib) or:
> Kedron, P., & Holler, J. (2023). Template for Reproducible and Replicable Research in Human-Environment and Geographical Sciences. https://doi.org/10.17605/OSF.IO/W29MQ

# Transformative Change Assessment - Ch 3 - Clusters

[![DOI](https://zenodo.org/badge/DOI/99.9999/zenodo.9999999.svg)](https://doi.org/99.9999/zenodo.9999999)
[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC_BY--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

## Data Package
[![DOI Data Package](https://zenodo.org/badge/DOI/99.9999/zenodo.9999999.svg)](https://doi.org/99.9999/zenodo.9999999)

## Metadata
- **Assessment**: Transformative Change Assessment
- **Project name**:Transformative Change Assessment - Ch 3 - Clusters
- **Chapter**: Ch 3
- **Shortname**: IPBES_TCA_Ch3_clusters
- **Github Repo**: [github repository for the branch](https://github.com/IPBES-Data/IPBES_TCA_Ch3_clusters/tree/DMR_final)

- **Project leaders**

  - [Catherine Sabinot](mailto:catherine.sabinot@ird.fr)
  - [Rainer Krug](mailto:Rainer.Krug@senckenberg.de,Rainer@krugs.de)

- **Researchers**

  - [Andressa Mansur](mailto:andressavmansur@gmail.com)
  - [Maiko Nishi](mailto:nishi@unu.edu)
  - [Zühre Aksoy](mailto:zuhre.aksoy@boun.edu.tr)
  - [David Lam](mailto:david.lam@leuphana.de)

- **Data curator(s)**

  - [Camille Guibal](mailto:camille.guibal@umontpellier.fr)



## Folders

- **`data`**: data files created during the running of the `snowball.qmd` file and contains cached as well as final data files. The data folder can be downloaded from [10.5281/zenodo.11352062](https://doi.org/10.5281/zenodo.11352062)
  - `gdm`: Folder containing data for Maps
  - `cluster.rds`: Cluster data, including keypaper, snowball, etc
  - `snowball.rds`: Snowball data of the general snowball
- **`figures`**: figures created during the running of the `snowball.qmd` file in low-res as well as high-res.
  - `approaches_theories_*.*`: Sankeys of Theories -> Approaches in different formats and level 1, level two and both
  - `cluster_*.*`: Cluster citation networks  any are missing because they could not be plotted (to many nodes and edges)
  - `common_l3.*`: Common papers in Approaches between the snowball searches. the html is ionteractive.
  - `snowball_cited_*.*`: Snowball citation networks of the general snowball search
- **`maps`**: Maps created during the running of the `IPBES_TCA_Ch3_clusters.qmd` file
  - author distributions by country by first author and all authors for each Approach (cluster)
- **`input`**: input files for the `IPBES_TCA_Ch3_clusters.qmd` file
  - `key_papers`: folder containing the key papers for the Approach / cluster based snowball searches
  - `keypapers.csv` file with the key papers for the general snowball search
  - `T&F of TC from CA - chapter 3 - All theories from CA coded.csv` containing raw data for Approach based snowball searches as well as relationship between Theories and Approaches

### Description

TO BE ADDED

## Technical Reports

- [IPBES TCA Ch3 clusters](IPBES_TCA_Ch3_clusters.html) 

# Summary

Retrieval and analysis of metagenome data from public sources.
See https://researchparasite.com/ for why this repo is called **LLPAR**

* Authors
  * Jacobo de la Cuesta-Zuluaga (started December 2019)
  * Nick Youngblut
* Maintainers
  * Jacobo de la Cuesta-Zuluaga (started December 2019)
  * Nick Youngblut

# Description

This repo contains files and notebooks to i) retrieve publicly available sequence data ii) analyses the data 

## Data retrieval

Retrieve data of publicly available sequence repositories or packages containing such data. The `mgnify-metagenomes` folder contains code to retrieve environmental and host associated metagnomes from the MGnify platform of EBI-EMBL. The CurMetDat-metagenomes contains code and files to retrieve metagenomes from the `curatedMetagenomicData` package of `R` from the Waldron lab.

The data can then be formated and used with the Ley Lab Metagenome QC pipeline `LLMGQC` to download and quality check.

## Data analyses

* `./ipynb/01_data_explore/`
  * Initial exploration, pre-processing, and formatting of the data
* `./ipynb/02_comm_diversity/`
  * Main assessments of community diversity
* `./ipynb/03_ML/`
  * All machine learning analyses
* `./ipynb/04_tutorial/`
  * Tutorials on calculating diversity measures

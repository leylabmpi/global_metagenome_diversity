Global Metagenomes Diversity study
==================================

Code and notes associated with the study:

> Youngblut et al. Incorporating genome-based phylogeny and functional similarity into diversity assessments helps to resolve a global collection of human gut metagenomes. Submitted. 

## Data retrieval

./CurMetDat-metagenomes/ contains code and files to retrieve metagenomes from the
[curatedMetagenomicData](https://waldronlab.io/curatedMetagenomicData/) R package
from the Waldron lab.

## Data analyses

See ./notebooks/ for Jupyter notebooks on the data analysis

* `./notebooks/01_data_explore/`
  * Initial exploration, pre-processing, and formatting of the data
* `./notebooks/02_comm_diversity/`
  * Main assessments of community diversity
* `./notebooks/03_ML/`
  * All machine learning analyses
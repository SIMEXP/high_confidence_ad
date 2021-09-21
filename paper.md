---
title: 'NeuroLibre preprint (PDF) template'
tags:
  - Preprint
  - Jupyter Book
  - Reproducible article
  - Neuroscience
authors:
  - name: Agah Karakuzu
    orcid: 0000-0001-7283-271X
    affiliation: "1, 2"
  - name: Nikola Stikov
    orcid: 0000-0002-8480-5230
    affiliation: "1, 2"
affiliations:
  - name:  Centre de Recherche de l'Institut Universitaire de Gériatrie de Montréal, 4545 chemin Queen-Mary, Montréal, QC, H3W 1W4, Canada
    index: 1
  - name: Centre for the Studies on Prevention of Alzheimer's Disease, Douglas Mental Health University Institute Research Centre, 6875 Lasalle Boulevard, Montréal, QC, H4H 1R3, Canada
    index: 2
date: 26 March 2021
bibliography: paper.bib
---

This work is a reproducible companion to the following article: [A signature of cognitive deficits and brain atrophy that is highly predictive of progression to Alzheimer’s dementia](https://doi.org/10.1101/352344). The original data used in the publication, collected and shared by the Alzheimer's Disease Neuroimaging Initiative (ADNI), cannot be openly redistributed. Instead, we included simulated data which mimic the characteristics of the imaging and demographics sample used in the publication. All the necessary code for predictive modelling is also included, allowing to reproduce all key analyses and results. Although the results presented here do not strictly reproduce those found in the publication, as we are using simulated data instead, the notebooks shared here will allow readers to closely approximate all major figures in the paper.

Here is a brief description of each item in the repository:
* **Proteus** - a Python package by [Christian Dansereau](https://github.com/cdansereau). Proteus was built on [scikit-learn](http://scikit-learn.org/stable/#) and it offers machine learning tools to make highly confident predictions
* **vcog_hpc_prediction_simulated_data.ipynb** - a Jupyter notebook containing analyses that give a highly predictive signature (HPS) of Alzheimer's disease dementia from cognitive and structural features using *simulated data*
* **simulation_script.py** - a Python script that generates simulated data from raw data
* **simulated_data.csv** - a comma separated value file that contains simulated data
* **spm_container** - an Octave package containing wrappers for [SPM12](https://www.fil.ion.ucl.ac.uk/spm/software/spm12/) functions for segmentation and DARTEL

# Acknowledgements

NeuroLibre is sponsored by Canadian Open Neuroscience Platform (CONP), Brain Canada, Quebec Bioimaging Network, Cancer Computing and Healthy Brains & Healthy Life.

# References

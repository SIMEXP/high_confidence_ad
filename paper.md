---
title: 'Reproducible jupyter book for a highly predictive signature of cognition and brain atrophy for progression to Alzheimer\'s dementia'
tags:
  - Reproducible article
  - Alzheimer's Disease
  - Neuroimaging
  - Biomarkers
  - Precision medicine
authors:
  - name: Angela Tam
    orcid: 0000-0001-6752-5707
    affiliation: "1, 2"
  - name: Christian Dansereau
    orcid: 0000-0003-3363-1901
    affiliation: "1, 3"
  - name: Yasser Iturria-Medina
    orcid: 0000-0002-9345-0347
    affiliation: "4"
  - name: Sebastian Urchs
    orcid: 0000-0001-5504-8579
    affiliation: "1, 4"
  - name: Pierre Orban
    orcid: 0000-0003-3201-9614
    affiliation: "1, 5, 6"
  - name: Hanad Shamarke
    affiliation: "1"
  - name: John Breitner
    orcid: 0000-0003-4229-4687
    affiliation: "2, 7"
  - name: Pierre Bellec
    orcid: 0000-0002-9111-0699
    affiliation: "2, 7"

affiliations:
  - name:  Centre de Recherche de l'Institut Universitaire de Gériatrie de Montréal, 4545 chemin Queen-Mary, Montréal, QC, H3W 1W4, Canada
    index: 1
  - name: Centre for the Studies on Prevention of Alzheimer's Disease, Douglas Mental Health University Institute Research Centre, 6875 Lasalle Boulevard, Montréal, QC, H4H 1R3, Canada
    index: 2
  - name: Département d'informatique et de recherche opérationnelle, Université de Montréal, 2920 chemin de la Tour, Montréal, QC, H3T 1J4, Canada
    index: 3
  - name: Montreal Neurological Institute, McGill University, 3801 University Street, Montréal, QC, H3A 2B4, Canada
    index: 4
  - name: Centre de Recherche de l'Institut Universitaire en Santé Mentale de Montréal, 7331 rue Hochelaga, Montréal, QC, H1N 3V2, Canada
    index: 5
  - name: Département de psychiatrie, Université de Montréal, 2900 boulevard Édouard-Montpetit, Montréal, QC, H3T 1J4, Canada
    index: 6
  - name: Department of Psychiatry, McGill University, 1033 Pine Avenue West, Montréal, QC, H3A 1A1, Canada
    index: 7
  - name: Département de psychologie, Université de Montréal, 90 avenue Vincent d'Indy, Montréal, QC, H3C 3J7, Canada
    index: 8

date: 26 March 2021
bibliography: paper.bib
---

This work is a reproducible companion to the following [article](https://doi.org/10.1101/352344), "_A signature of cognitive deficits and brain atrophy that is highly predictive of progression to Alzheimer’s dementia_". The original data used in the publication, collected and shared by the Alzheimer's Disease Neuroimaging Initiative (ADNI), cannot be openly redistributed. Instead, we included simulated data which mimic the characteristics of the imaging and demographics sample used in the publication. All the necessary code for predictive modelling is also included, allowing to reproduce all key analyses and results. Although the results presented here do not strictly reproduce those found in the publication, as we are using simulated data instead, the notebooks shared here will allow readers to closely approximate all major figures in the paper.

Here is a brief description of each item in the repository:
  * **Proteus** - a Python package by [Christian Dansereau](https://github.com/cdansereau). Proteus was built on [scikit-learn](http://scikit-learn.org/stable/#) and it offers machine learning tools to make highly confident predictions
  * **vcog_hpc_prediction_simulated_data.ipynb** - a Jupyter notebook containing analyses that give a highly predictive signature (HPS) of Alzheimer's disease dementia from cognitive and structural features using *simulated data*
  * **simulation_script.py** - a Python script that generates simulated data from raw data
  * **simulated_data.csv** - a comma separated value file that contains simulated data
  * **spm_container** - an Octave package containing wrappers for [SPM12](https://www.fil.ion.ucl.ac.uk/spm/software/spm12/) functions for segmentation and DARTEL

# Acknowledgements

NeuroLibre is sponsored by Canadian Open Neuroscience Platform (CONP), Brain Canada, Quebec Bioimaging Network, Cancer Computing and Healthy Brains & Healthy Life.

# References

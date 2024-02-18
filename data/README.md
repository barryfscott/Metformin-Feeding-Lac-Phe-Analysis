# Data Directory

This directory contains the following data files used in the Jupyter notebooks for the analysis:


## Brigham_metabolomics_supplementary.xlsx
- **Description**: This file contains the metabolomics data for a cohort of 33 subject that we recruited at Brigham and Womens hospital. It includes data for  Obese T2D, Obese Non T2D and lean  volunteers.
- **Source**: Metformin and feeding increase levels of the appetite suppressing metabolite Lac-Phe
- **Preprocessing**: This dataset is the same dataset that was published in Nature Metabolism.


## Kannt_feeding_metabolomics.xlsx
- **Description**: This file contains the metabolomics data pre and post ingestion of a mixed meal. It includes columns for metabolite levels, patient IDs, and timestamps.
- **Source**: [Short-term variability of the human serum metabolome depending on nutritional and metabolic health status](https://www.nature.com/articles/s41598-020-72914-7#Sec26)
- **Preprocessing**: Prior to analysis, certain columns were removed using Excel for a streamlined data import process into a pandas DataFrame.

## Mathew_feeding_metabolomics.xlsx
- **Description**: This file contains the metabolomics data before and after a date fruit challenge or an oral glucose tolerance test. It includes columns for metabolite levels, patient IDs, and Timepoints.
- **Source**: [Metabolic changes of the blood metabolome after a date fruit challenge](https://www.sciencedirect.com/science/article/pii/S1756464618304699)
- **Preprocessing**: Prior to analysis, certain columns were removed using Excel for a streamlined data import process into a pandas DataFrame.

## unknown_Metabolon_metabolites_renamed.xlsx
- **Description**: List of metabolites that were initially reported as unknown metabolites by Metabolon but have since been identified.


## Usage
These data files, are used in Jupyter notebooks located in the `notebooks` directory of this repository. Each notebook will specify which data file(s) it utilizes.



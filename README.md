# RMDS 2020 Challenge

*Shravani Kasralikar, Julian Lehrer, Anders Poirel 28/05/2020*

RMDS Covid computational challenge

## Setup

Create a conda environment with all the required packages: 
```
conda env create -f environment.yml
```
Switch to the new environment:
```
conda activate rmds-covid-env
```

## Project structure
```
├── environment.yml          <- The conda file for reproducing the analysis
|                               environment. 
├── README.md                <- The top-level README
├── Snakefile                <- Script with options for running the final analysis.
├── data
|   ├── interim              <- Intermediate data that has been transformed.
│   ├── processed            <- The final, canonical data sets for modeling.
│   └── raw                  <- The original, immutable data dump.
├── notebooks                <- Jupyter notebooks.
├── output             
|   ├── models               <- Serialized models, predictions, model summaries.
|   └── visualization        <- Graphics created during analysis.
├── reports                  <- Generated analysis as HTML, PDF, LaTeX, etc.
└── src                      <- Source code for this project.
    ├── __init__.py          <- Makes this a python module.
    ├── data                 <- Scripts to download or generate data.
    |   └── make_dataset.py  
    ├── features             <- Scripts to turn raw data into features for modeling.
    |   └── build_features.py  
    ├── models               <- Scripts used to generate models and inference results.
    └── visualization        <- Scripts to generate graphics.
        └── visualize.py
```
    

# SIT HIV Modelling in Nigeria

This project presents a historical compartmental model developed during Nigeria’s 2013 HIV mathematical modelling programme. It examines HIV transmission among female sex workers, their clients, general males, and general females.

The model represents susceptible, undiagnosed, diagnosed, treated, and treatment-failure states. It uses 100 uncertainty simulations and extends the original projection from 2020 to 2030.

## Key results

Under the retained assumptions, average modelled prevalence in 2030 is:

* Female sex workers: 2.84%
* Clients: 0.63%
* General males: 0.30%
* General females: 0.38%

These are scenario projections based on the original assumptions, not current national HIV prevalence estimates.

## Notebook

Open `SIT_HIV_Modelling_Nigeria_2013_2030.ipynb` to view the model, results, tables, charts, calibration diagnostics, public indicators, references, and conclusion.

## Requirements

```bash
pip install numpy pandas matplotlib ipython jupyter
```

## Background

The work followed a World Bank-sponsored mathematical modelling programme delivered by the University of New South Wales and a six-month engagement with Nigeria’s Technical Working Group on Mathematical Modelling of HIV.

## Data sources

Public indicators used for context come from:

* [UNAIDS](https://www.unaids.org/en/regionscountries/countries/nigeria)
* [World Bank](https://data.worldbank.org/indicator/SH.DYN.AIDS.ZS?locations=NG)
* [CDC Nigeria HIV and TB Overview](https://www.cdc.gov/global-hiv-tb/php/where-we-work/nigeria.html)

## Author

Abiodun Alabi

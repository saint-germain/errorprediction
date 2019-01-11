# Repository for "Predicting extragalactic distance errors using Bayesian inference in multi-measurement catalogs" paper

https://arxiv.org/abs/1805.02578

G. Chaparro Molano, J.C. Cuervo, O.A. Restrepo Gaitán, S. Torres Arzayús

## Data tables

Pre-computed error tables for the redshift indepentent extragalactic distance catalogs in HyperLEDA, NED-D, and Cosmicflows-3.

- [HyperLEDA](hl_bootstrap_results.csv)
- [NED-D](ned_bootstrap_results.csv)
- [Cosmicflows-3](cf3_bootstrap_results.csv)

## Notebooks

- [Computing distance errors in Cosmicflows-3](errors_Cosmicflows-3.ipynb)
- [Computing distance errors in NED-D](errors_NED-D.ipynb)
- [Predicting missing TFR distance errors in NED-D](correctdiscrepancy.ipynb)
- [Computing distance errors and predicting missing TFR distance errors in HyperLEDA](errors_HyperLEDA.ipynb)


## Data files

Required data files (from outside this repo) for TF error predictive model are here:

- https://github.com/saint-germain/anisotropias/blob/master/bootstrap_results_2018.csv
- https://github.com/saint-germain/anisotropias/blob/master/bootstrap_results_wm_2018.csv
- https://github.com/saint-germain/anisotropias/blob/master/posterior_lh.txt
- https://github.com/saint-germain/anisotropias/blob/master/posterior_lm.txt

Original data files are here:

- [NED-D](https://github.com/saint-germain/anisotropias/blob/master/NED28.10.1-D-15.1.0-20181130.csv)
- [HyperLEDA](https://github.com/saint-germain/anisotropias/blob/master/HyperLeda_a007_full.txt)
- [Cosmicflows-3](https://github.com/saint-germain/anisotropias/blob/master/EDDtable14Mar2018170435.txt)

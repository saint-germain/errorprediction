# Repository for "Predicting extragalactic distance errors using Bayesian inference in multi-measurement catalogs" paper

#### Germán Chaparro-Molano, Juan Carlos Cuervo, Oscar Alberto Restrepo Gaitán, Sergio Torres Arzayús; Predicting extragalactic distance errors using Bayesian inference in multi-measurement catalogs, Monthly Notices of the Royal Astronomical Society, Volume 485, Issue 3, May 2019, Pages 4343–4358, https://doi.org/10.1093/mnras/stz615

- [Published Version](https://academic.oup.com/mnras/advance-article-abstract/doi/10.1093/mnras/stz615/5368374?redirectedFrom=fulltext)
- Preprint: https://arxiv.org/abs/1805.02578

## Data tables

Pre-computed error tables for the redshift independent extragalactic distance catalogs in HyperLEDA, NED-D, and Cosmicflows-3.

- [HyperLEDA](hl_bootstrap_results.csv)
- [NED-D](ned_bootstrap_results.csv)
- [Cosmicflows-3](cf3_bootstrap_results.csv)

## Notebooks

These notebooks are Binder-compatible [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/saint-germain/errorprediction/master)

- [Computing TFR distance errors in NED-D](computing_errors.ipynb)
- [Bayesian models for our pre-computed TFR distance errors for NED-D](bayesian_models.ipynb)
- [Predicting missing TFR distance errors in NED-D](prediction_errors.ipynb)

Notebooks with the computation of errors for the full HyperLEDA, NED-D, and Cosmicflows-3 catalogs:

- [Computing distance errors in Cosmicflows-3](errors_Cosmicflows-3.ipynb)
- [Computing distance errors in NED-D](errors_NED-D.ipynb)
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

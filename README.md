# White Dwarf Classification

Broad classification of White Dwarfs using various machine-learning techniques.


## Montreal White Dwarf Database (MWDD)

This section uses physical parameters (T_eff, log(g), mass) and SDSS *ugriz*
photometry to create a classification model for the broad spectral type (DA,
DB, etc.) of white dwarfs. Simple models are employed, such as Random Forest
and Gradient-Boosting algorithms.

The data collected for this section can be retrieved from
[the MWDD website](https://www.montrealwhitedwarfdatabase.org)
(Dufour, et al. 2017). Values to include in the data set (from the "Options"
selection on the website) include `Teff [k]`, `log(g)`, `Mass`, and the `SDSS
<filter>` photometry. This can be saved to a `./data` directory in the root of
this repository for use with the Python notebooks.

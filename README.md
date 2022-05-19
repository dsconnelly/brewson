# brewson

`brewson` is a set of notebooks wherein I use ERA5 data to compute and analyze the Brewer-Dobson circulation (the residual overturning circulation in the stratosphere). The code was written to be run on the UCAR supercomputer Casper.

The notebooks are
- `process.ipynb`, where I read in the full ERA5 dataset and compute the components of the Brewer-Dobson circulation, along with a few other useful diagnostics like the Eliassen-Palm flux divergence;
- `analysis.ipynb`, where I plot the data computed previously in various ways and compute a few statistics.

Throughout the repository, I make frequent reference to the paper of [Seviour et al. (2012)](https://rmets.onlinelibrary.wiley.com/doi/full/10.1002/qj.966), who performed similar analyses using ERA-Interim.
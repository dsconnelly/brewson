# brewson

In this set of notebooks, I use ERA5 data to compute and analyze the Brewer-Dobson circulation (the residual overturning circulation in the stratosphere) as well as the meridional overturning circulation in isentropic coordinates. The code was written to be run on the UCAR supercomputer Casper.

The notebooks are
- `process.ipynb`, where I read in the full ERA5 dataset and compute the components of the Brewer-Dobson circulation, along with a few other useful diagnostics like the Eliassen-Palm flux divergence
- `isentropic.ipynb`, where I compute the isentropic mass flux from ERA5
- `analysis.ipynb`, where I plot the data computed previously in various ways and compute a few statistics

Throughout the repository, I make frequent reference to the paper of [Seviour et al. (2012)](https://rmets.onlinelibrary.wiley.com/doi/full/10.1002/qj.966), who performed similar analyses using ERA-Interim. In computing the isentropic streamfunction, I also reference the formulation of [Held and Schneider (1999)](https://journals.ametsoc.org/view/journals/atsc/56/11/1520-0469_1999_056_1688_tsbotz_2.0.co_2.xml).
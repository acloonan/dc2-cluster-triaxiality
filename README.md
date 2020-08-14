# cluster-triaxiality
Calculating galaxy cluster orientation with DC2 simulation data.
## Project Overview
As of now, I'm interested in comparing different proxies for cluster orientation within the [cosmoDC2](https://github.com/LSSTDESC/cosmodc2) simulated dataset. I'll be starting with 2 proxies: cluster member distribution and central member (or, usually, brightest cluster galaxy) ellipticity. More could potentially be added later on.

Work currently in progress.

## Necessary Imports, Packages, Modules, etc.

Python, Numpy, Astropy, OS, Dask, matplotlib, [GCRCatalogs](https://github.com/LSSTDESC/gcr-catalogs), likely more

Also, a NERSC computing node is probably required.

## Notebooks

Run through `halo_redMcluster_matching.ipynb` first, as the FITS files produced in that notebook will be important in other notebooks.

## Misc. Notes

Pretty much everything here is only applicable to GCR datasets at the moment, maybe even only to cosmoDC2.

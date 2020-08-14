# dc2-cluster-triaxiality
Galaxy cluster orientation and ellipticity with DC2 simulation data.

Collaboration with [LSST DESC](https://github.com/LSSTDESC).

## Short Project Overview
As of now, I'm interested in comparing different proxies for cluster orientation within the [cosmoDC2](https://github.com/LSSTDESC/cosmodc2) simulated dataset. I'll be starting with two proxies: cluster member distribution and central member (or, usually, brightest cluster galaxy) ellipticity. More could potentially be added later on.

Work currently in progress.

## Necessary Imports, Packages, Modules, etc.

Jupyter Notebook or JupyterLab, Numpy, Astropy, OS, Dask, matplotlib, [GCRCatalogs](https://github.com/LSSTDESC/gcr-catalogs), [esutil](https://github.com/esheldon/esutil), likely more to be added.

Also, a NERSC computing node is probably required.

## Misc. Notes

Pretty much everything here is only applicable to GCR datasets at the moment, maybe even only to cosmoDC2.

The primary cosmoDC2 catalog is a dataset of galaxies. Clusters are identified using the [redMaPPer algorithm](https://github.com/erykoff/redmapper), the results of which can be found within GCRCatalogs.

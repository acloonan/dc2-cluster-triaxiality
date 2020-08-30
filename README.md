# dc2-cluster-triaxiality
Galaxy cluster orientation and ellipticity with DC2 simulation data. Collaboration with [LSST DESC](https://github.com/LSSTDESC).

July 2020 - Present

## Short Project Overview
I'm interested in estimating galaxy cluster ellipticity and orientation within the [cosmoDC2](https://github.com/LSSTDESC/cosmodc2) simulated dataset. I'd also be curious about utilizing and comparing different methods or proxies for such a task. I'll be starting by focusing primarily on cluster member distribution using quadrupole moment calculations. One other possible proxy for later on would be the shape and orientation of the brightest cluster galaxy (BCG).

Work currently in progress.

## Dependencies

* Jupyter Notebook or JupyterLab
* numpy
* scipy
* matplotlib
* astropy 
* dask
* h5py
* [GCRCatalogs](https://github.com/LSSTDESC/gcr-catalogs)
* [esutil](https://github.com/esheldon/esutil)

More to be added.

Also, a NERSC computing node might be necessary.

## Notes

Pretty much everything here is only applicable to GCR datasets at the moment, maybe even more specifically to cosmoDC2.

The primary cosmoDC2 catalog is a dataset of galaxies. Clusters were identified using the [redMaPPer algorithm](https://github.com/erykoff/redmapper), the results of which can be found within GCRCatalogs.

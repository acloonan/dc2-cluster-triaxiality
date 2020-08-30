# dc2-cluster-triaxiality
Galaxy cluster orientation and ellipticity with DC2 simulation data. Collaboration with [LSST DESC](https://github.com/LSSTDESC).

July 2020 - Present

## Short Project Overview
I'm interested in comparing different proxies for cluster ellipticity and orientation within the [cosmoDC2](https://github.com/LSSTDESC/cosmodc2) simulated dataset. I'll be starting by focusing primarily on cluster member distribution using quadrupole moment calculations, but I'm also curious about brightest cluster galaxy (BCG) ellipticity and orientation as a proxy. More could potentially be added later on.

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

## Misc. Notes

Pretty much everything here is only applicable to GCR datasets at the moment, maybe even more specifically to cosmoDC2.

The primary cosmoDC2 catalog is a dataset of galaxies. Clusters are identified using the [redMaPPer algorithm](https://github.com/erykoff/redmapper), the results of which can be found within GCRCatalogs.

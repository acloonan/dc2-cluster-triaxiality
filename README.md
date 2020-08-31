# dc2-cluster-triaxiality
Galaxy cluster orientation and ellipticity with DC2 simulation data. Collaboration with [LSST DESC](https://github.com/LSSTDESC).

July 2020 - Present

## Short Project Overview
[CosmoDC2](https://github.com/LSSTDESC/cosmodc2) is a simulated galaxy catalog, with some ~440 sq degrees of simulated sky and some ~2.3 billion synthetic galaxies. Within the dataset, the [redMaPPer algorithm](https://github.com/erykoff/redmapper) has been used to identify red sequence galaxy clusters.

My overarching goal is the development of a pipeline estimating ellipticity and orientation for identified clusters found in cosmoDC2. I'm currently focusing on using quadrupole moment calculations to profile the distribution of clusters' member galaxies.

I'm also curious about comparing different methods or proxies for such a task. The distribution of halo particles would be interesting to consider, if there are any accessible catalogs of such information. One other possible proxy would be the shape and orientation of the brightest cluster galaxy (BCG).

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

Pretty much everything here may only applicable to GCR datasets at the moment, maybe even more specifically to cosmoDC2.

Work currently in progress.

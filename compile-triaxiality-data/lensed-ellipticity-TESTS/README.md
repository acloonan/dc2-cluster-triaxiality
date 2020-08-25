# lensed-ellipticity-TESTS

This folder includes some ideas I tried or am currently trying out with regards to calculating BCG lensed ellipticity.

I had initially thought my matched halos could be considered the BCGs, hence the test on matched halos, but I realized that this is not the case.
I then started playing around with the `id_cen_0` galaxies. These IDs are found in the cosmoDC2 redMaPPer catalog, and the galaxies marked with these IDs generally are most likely to be their respective cluster's BCG.

As of now, I've been able to tentatively use GCRCatalogs, but I want to try to implement a method utilizing dask dataframes.

**Aug. 25**: Tests using dask dataframes went well, and now I'm writing a notebook applying that method to all ~3900 of them. I'd guess it will show up here on GitHub sometime this week, as I'll be looking into quantities within the HDF5 files.

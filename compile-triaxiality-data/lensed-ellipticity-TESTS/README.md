# lensed-ellipticity-TESTS

This folder includes some ideas I tried or am currently trying out with regards to calculating BCG lensed ellipticity.

I had initially thought my matched halos could be considered the BCGs, hence the test on matched halos, but I realized that this is not the case.
I then started playing around with the `id_cen_0` galaxies. These IDs are found in the cosmoDC2 redMaPPer catalog.

As of now, I've been able to tentatively use GCRCatalogs, but I want to try to implement a method utilizing dask dataframes.

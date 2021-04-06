# compile-triaxiality-data
Compile quantities that will be necessary for calculating orientation and ellipticity of galaxy clusters in [cosmoDC2](https://github.com/LSSTDESC/cosmodc2). Then, make those calculations.

## Notebooks and Folders
* `halo_redMcluster_matching.ipynb` matches clusters to individual galactic halos, and it might not be necessary for the other work at this point. 
* `get_member_quantities.ipynb` includes some initial testing of compiling quantities for individual members. 
* The bcg-lensed-ellipticity-TESTS folder includes some early attempts at finding BCG ellipticities. 
* The member-distribution folder includes an algorithm that compiles Cartesian coordinates for cluster members. I should probably rename this folder, as the quadrupole moment calculations are in a separate folder
* The fits_files folder includes output FITS files from all my work. I should maybe organize this a bit better.
* The quad-moment folder includes work on calculating quadrupole moments. This is what I'm working on right now.

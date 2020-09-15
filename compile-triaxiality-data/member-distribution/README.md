# member-distribution

Right now, I'm using this folder to store notebooks that test GCR and H5py methods of compiling cluster members' comoving Cartesian coordinates.

After a method has been selected with some confidence, I'll utilize member Cartesian data to calculate each cluster's quadrupole moment,
profiling the each cluster's member distribution. The notebook(s) with this method will be added to this folder as well.

**These are probably the most relevant programs I've added to the entire repository yet. So far, the H5py method has appeared to work properly.**

## Misc. Notes

Currently, the H5py notebook is over 1 MB, which seems to mean that collaborators cannot edit the document from within GitHub.

Note that it may be easier to run get_comoving_cartesian_coordinates.ipynb by connecting a NERSC computing node to your local system. To do this, open 2 command line windows and use the following linux commands:

1. **(first window)** Log into NERSC using `ssh <nersc_user>@cori.nersc.gov`.
2. **(first window)** `module load python`.
3. **(first window)** `jupyter notebook --no-browser --port=<some_number>`. The command line will give some instructions on how to access the notebook, including some URLs in the form of `http://localhost:<some_number>/?token=<some_token>`. The token `<some_token>`, a string of letters and numbers, may be important later.
4. **(second window)** Connect node to localhost using `ssh -N -f -L localhost:<some_other_number>:localhost:<some_number> <nersc_user>@cori.nersc.gov`.
5. Open a web browser and go to localhost:`<some_other_number>` or localhost:`<some_other_number>`/tree?. If it asks for a password, copy `<some_token>` and use it as the password. This should get you to a localhost notebook with your NERSC files.

This is a program that computes a source region impact factor using the outputs of the Hybrid Single Particle 
Lagrangian Integrated Trajectory model (http://ready.arl.noaa.gov/hypub-bin/trajtype.pl?runtype=archive). Trajpy v. 2.0 was
created as a result of an undergraduate thesis done at Reed College by Jonathan Tamsut under the advisement of Christopher Walsh.

This README provides information on how to run Trajpy v. 2.0! Trajpy v. 2.0 requires backwards trajectories generated by the Hybrid Single Particle Integrated Trajectory (HYSPLIT) model.

### Downloads and System Requirements

You need to have Python 2.7 installed onto your machine.

You must have internet access.

### Using HYSPLIT

Requesting archived (backwards) trajectories by HYSPLIT can be done at http://ready.arl.noaa.gov/hypub-bin/trajtype.pl?runtype=archive.

The trajectory output files should then be saved with a .csv filename extension. These output files should then be put into the same directory as Trajpy-v2.py. Moreover a separate text file is required that has the number of output files as its first line and the name and filename extension of the trajectory output files as each subsequent line.

### Using Trajpy v2

Once you have your trajectories configured correctly (they are all in the same directory, have their file names in a text file with the number of trajectory data dump files as the first item in this text file) you can use Trajpy v. 2.0 to compute an SRIF.
# Brain imaging data

This directory contains information about the location of each ECoG grid electrode.

The data for each subject consists of one .png image and one .mat file.

1. ECXXX_brain2D.png

    This image is a lateral view of a 3D brain, reconstructed from an MRI scan.

2. ECXXX_elec_pos2D.mat

    This .mat file contains a variable `xy`, which is a 2 x 256 ndarray containing the locations of each electrode on the 2D image. The locations are given by x and y pixel values.

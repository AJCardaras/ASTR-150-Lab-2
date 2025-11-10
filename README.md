# ASTR-150-Lab-2
Conversion from pixels to wavelength of spectra by using Kast Spectrum data and arc lamp data to create a linear least fit. This is done by finding the centroids of the arc lamp data, and comparing it to the peaks of the Kast spectrum, and using these values to create a linear line of best fit. Using this line you can then convert from pixels to wavelength, given that your data is the same dimensions.

This code makes use of numpy, matplotlib.pyplot, astropy, and glob to analyze the data. Ensure that you have read and write access to the directory that you are using.

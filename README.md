# dielectric_spectra
Dielectric Spectra computed using DFPT in CASTEP

This repository contains a collection of Dielectric Spectra I computed using CASTEP.

The development of Sternheimer DFPT has been carried out to compute the head (G=G'=0) 
component of the dielectric matrix at long wavelength (q=0.01, 0.0, 0.0).

A newly developed BiCGStab solver is responsible for computing the first-order response 
wavefunctions which in turn compute the response charge density which is directly 
related to the dielectric response. 

The .castep files are available along with eps.dat (raw files) as well as PNG's of the
spectra plotted along with spectroscopic ellipsometry data. 

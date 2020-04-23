# XSVS

Simulations of speckle patterns are generated from a random phasor field with a Gaussian probe. A predefined correlation as a function of time step is used to generate a temporal sequence of dynamic speckle patterns. The dynamic timescale can be extracted from measuring the contrast of the speckle pattern. In the low photon count regime, this can be done by coutning photon hits per pixel and fitting the statistics to a negative binomial distribution. 

The objective of these simulations is to model a double probe x-ray speckle visibility spectroscopy experiment (XSVS) that can be carried out at split-and-delay beamlines of free electron laser facilities. The code allows the user to generate two Gaussian probes with an angular misalignment and imperfect overlap that characterizes a realistic experiment. While the contrast is 'destroyed' when applying standard photon counting analysis, selective binning of the detector data can recover the contrast lost from angular misalignments. 







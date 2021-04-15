## Welcome to CRISP

CRISP is a multi-faceted project to study extinction towards supernovae and their environments though a variety of observational techniques including photometry,integral field spectroscopy and polarimetry of both SNe and their hosts, machine learning tools and theoretical 

<p align="center">
<img src="crisp_logo_cut.jpg" alt="alt text" width=300 height=200>
</p>


### Team and collaborators

Alessandro Razza (U.Chile)<br/>
Ana Mourão (CENTRA-IST)<br/>
Ana Paulina-Afonso (CENTRA-IST)<br/>
Antonia Morales-Garaffolo (U.Cádiz)<br/>
Alberto Krone-Martins (Irvine)<br/>
Beatriz Pereira (CENTRA-IST)<br/>
Claudia Gutiérrez (U.Turku)<br/>
Francisco Förster (U.Chile)<br/>
João Duarte (CENTRA-IST)<br/>
João Silvestre (CENTRA-IST)<br/>
Joe Anderson (ESO)<br/>
Lluis Galbany (U.Granada)<br/>
Marko Stalevski (O.Belgrade)<br/>
Majda Smole (O.Belgrade)<br/>
Pedro Garcia (CENTRA-FCUL)<br/>
Santiago González-Gaitán (CENTRA-IST)<br/>
Thomas de Jaeger (U.Hawaii)<br/>

### Projects


- **ARGAS: Artifically Redshifting of Galaxies (PI: A. Paulina-Afonso)**: <br/>
Recent studies have shown that type Ia supernova (SN) distance estimation improves when using an additional term related to the host galaxy mass. However, the bias and systematics of using a limited set of broad-band filters across a large redhift range has never been evaluated. With extensive simulations of nearby integral field spectroscopy (IFS) galaxies set at high redshifts, we study here the impact of effects like dimming, scaling and SED fitting in current and future SN surveys.
![Image](ARGAS.jpg)

- **Impact of varying colour-luminosity relation in type Ia supernova cosmology (PI: S. González-Gaitán)**:<br/>
Type Ia SN cosmology has been essential in determining the accelerated expansion of the universe. However, the standardization of their luminosity to measure distances relies on a color-luminosity calibration that generally assumes a constant factor throughout the SN Ia population. We investigate in this project the effect of letting this parameter vary. [Paper](https://ui.adsabs.harvard.edu/abs/2020arXiv200913230G/abstract) submitted.
<p align="center">
<img src="beta_color_value.jpg" alt="alt text" width=300 height=300>
</p>

- **Dust attenuation slopes of DES galaxies (PI: J. Duarte)**:<br/>
We are obtaining for the first time a set of dust attenuation slopes for a cosmological sample of SNe Ia from their host galaxies with broad-band photometry from the Dark Energy Survey ([DES](https://www.darkenergysurvey.org/)) complemented with available GALEX UV photometry. We use the SED fitter [prospector](https://prospect.readthedocs.io/en/latest/) and [FSPS](https://dfm.io/python-fsps/current/) population synthesis code. The method is tested with simulations.
<p align="center">
<img src="prosp.jpg" alt="alt text" width=250 height=250>
</p>

- **Dust attenuation slope maps of AMUSING galaxies (PI: A. Razza)**:<br/>
We will obtaining map of dust attenuation slopes across nearby galaxies observed with Integral Fiel Spectroscopy (IFS) galaxies from the [AMUSING](https://amusing-muse.github.io/) survey. Spectra are complemented with optical, UV and NIR broad-band photometry. The method uses the SED fitter [prospector](https://prospect.readthedocs.io/en/latest/) and [FSPS](https://dfm.io/python-fsps/current/) population synthesis and is being tested with large simulations.


- **Galaxy spatial field reconstruction with INLA (PI: S. González-Gaitán)**::<br/>
The spatial correlations of astrophysical quantities are normally poorly taken into account. As part of the [COIN](https://cosmostatistics-initiative.org/) collaboration, we use here the Integrated Nested Laplace Approximation ([INLA](https://www.r-inla.org/)) machinery to obtain meaningful spatial reconstructions of IFS galaxy properties. The algorithm is very powerful when there is sparsity of data. [Paper](https://ui.adsabs.harvard.edu/abs/2019MNRAS.482.3880G/abstract) published.   

<p align="center">
<img src="INLA.jpg" alt="alt text" width=200 height=200>
</p>

- **1.5D SED spatial fitting (PI: P. Garcia)**:
The next step of the INLA spatial fitting applied to galaxy IFS is to simulatenously fit the wavelength and the spatial dimension. In a first 1.5D approach, we iteratively fit SED at each spaxel with [prospector](https://prospect.readthedocs.io/en/latest/) while the spatial part is done with [INLA](https://www.r-inla.org/). 

- **Pilot project of polarimetric studies towards galaxies: the case of Circinus (PI: M. Stalevski, S. González-Gaitán)**:
Imaging polarimetry of the nearby Circinus galaxy, host of an Active Galactic Nucleus (AGN), taken with FORS2-VLT in multiple optical bands allows the study of the geometry and dust characteristics of the central object and its galaxy. 

<p align="center">
<img src="Circinus.jpg" alt="alt text" width=300 height=200>
</p>

- **Polarimetric studies towards galaxies (PI: J. Silvestre):<br/>
The first statistical study of multi-band imaging polarimetry with optical data from FORS2-VLT and CAFOS-CAHA will deliver nearby galaxy maps of various physical characteristics like dust and magnetic field alignment. The data will be compared with Monte Carlo radiative transfer simulations with the code [SKIRT](https://skirt.ugent.be/root/_landing.html).
![Image](galpol.jpg)




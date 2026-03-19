# obs_sofi

A Python package adapting the [LSST Software Stack](https://pipelines.lsst.io/) to the ESO-NTT SOFI near-infrared camera, enabling automated data reduction and source extraction for Ks-band astronomical imaging.

Developed as part of a Master's thesis in Astronomy and Astrophysics (University of Innsbruck / University of Belgrade, 2016). The package served as both a working instrument and a template for adapting the Stack to other near-infrared cameras.

---

## Overview

The LSST Software Stack was designed primarily for optical data reduction. This package extends it to handle the distinct challenges of near-infrared imaging — in particular the high and variable thermal background.

The package was validated against a Ks-band dataset from the [VIMOS VLT Deep Survey (VVDS) 02hr field](https://www.aanda.org/articles/aa/abs/2008/16/aa8526-07/aa8526-07.html), with results compared to reductions performed using the established IRAF and IRDR pipelines.

---

## Citation

If you use this package, please cite the original thesis:

> Khusanova, Y. (2016). *Adaptation of the LSST Software Stack to the ESO-NTT SOFI Camera and Application to the SOFI Ks-band dataset of the 02hr Deep Field from the VIMOS VLT Deep Survey for Data Reduction and Analysis.* Master's thesis, University of Innsbruck / University of Belgrade.

The data reduction builds on the IRDR pipeline [(Sabbey et al. 2001)](https://articles.adsabs.harvard.edu/full/2001ASPC..238..317S) and the SOFI calibration procedures described in [Lidman & Cuby (2002)](https://www.eso.org/sci/facilities/lasilla/instruments/sofi/doc/manual/sofiman_2p20.pdf).

---

## Author

**Yana Khusanova**  
Originally developed in 2016 at the [Astronomical Observatory Belgrade](https://www.aob.rs/en/) and the Institute for Astro- and Particle Physics, [University of Innsbruck](https://www.uibk.ac.at/en/), under supervision of Prof. Darko Jevremović and Mag. Dr. Sonia Giovanna Temporin.

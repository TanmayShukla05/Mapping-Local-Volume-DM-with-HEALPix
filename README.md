# Mapping Local-Volume Dispersion Measure with HEALPix

This repository contains a **physics-based, non-ML notebook** for constructing and visualizing **dispersion measure (DM) maps** of the local universe using **HEALPix**.  
The emphasis is on **astrophysical modeling, coordinate transformations, and all-sky visualization**, rather than machine learning.

---

## Overview

The notebook demonstrates how to:

- Model local-volume electron density contributions to DM
- Project 3D information onto the celestial sphere
- Generate **all-sky HEALPix maps**
- Visualize and annotate prominent nearby galaxies / structures
- Work with log-scaled DM maps and sky projections

The workflow is suitable for:
- FRB foreground DM studies  
- Local large-scale structure visualization  
- Testing DM prescriptions before extending to cosmological distances  

---

## Repository Structure


---

## Concepts and Tools Used

- HEALPix pixelization (`healpy`)
- Sky projections (Mollweide)
- Galactic / equatorial coordinates
- Toy electron-density → DM modeling
- Log-scaling and annotated sky maps

---

## Dependencies

Install the required Python packages:

```bash
pip install numpy matplotlib healpy astropy

# Project 1: Two-Rung H0 Distance Ladder

In this project, you will measure the Hubble constant (H0) using a simplified two-rung distance ladder:

1. **Rung 1 (Anchor)**: Use Cepheid variables in the Large Magellanic Cloud (LMC) with known geometric distance to calibrate the Period-Luminosity relation
2. **Rung 2 (Hubble Flow)**: Apply this calibration to measure distances to Type Ia supernova host galaxies and construct a Hubble diagram

## Learning Objectives
- Understand the Cepheid Period-Luminosity (Leavitt) Law
- Apply photometric calibrations and extinction corrections
- Query astronomical databases (SIMBAD) for redshift data
- Construct and fit a Hubble diagram using MCMC
- Understand correlated vs. uncorrelated systematic uncertainties
- Implement anchor marginalization for proper error propagation

## Files
- `H0_distance_ladder_simple_student.ipynb` - Main notebook with 12 tasks
- `data/cepheids_shoes.dat` - Cepheid photometry from SH0ES collaboration
- `data/extinction_curve.png` - Reference extinction curve

## Data Credits
Cepheid data from Riess et al. (SH0ES collaboration)
LMC distance from Pietrzynski et al. (2019): 18.477 +/- 0.026 mag

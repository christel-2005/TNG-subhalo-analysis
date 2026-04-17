# TNG Dark Matter Halo Visualization 🌌

This repository contains Python scripts for analyzing and visualizing dark matter halos using data from the **IllustrisTNG** cosmological simulation.

## Project Background
This work serves as an initial exploration into verifying recent observational claims regarding indefinitely flat circular velocities of isolated galaxies out to 1 Mpc (e.g., *Mistele et al., 2024*). 

The ultimate scientific goal is to analyze the 2-halo term and surrounding large-scale structures by performing spatial spherical cutouts around central isolated galaxies within the TNG100-1 simulation to trace the extended rotation curves.

## Current Contents
* `plot_suhalo_dark matter halo.ipynb`: A baseline Jupyter Notebook demonstrating the extraction of particle data via the TNG web API. It includes the code workflow to fetch subhalo cutouts and generate 3D spatial distribution visualizations of dark matter particles.

## Future Plans
Once access to the TNG JupyterLab is granted, this repository will be expanded with scripts utilizing the `illustris_python` library (specifically `il.snapshot.loadSubset`). This will allow for the processing of massive 1 Mpc environmental volumes directly on the remote servers, bypassing the current limitations of web API cutouts for large-scale structural analysis.

## Author
**Meixuan YANG** Undergraduate Student at **UCAS**

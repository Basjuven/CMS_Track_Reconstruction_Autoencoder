# CMS Track Reconstruction Using a Linear Autoencoder
 "Implementation of a Linear Autoencoder for Particle Track Reconstruction in CMS Open Data"

This repository contains a Python implementation of a Linear Autoencoder for reconstructing particle tracks using data from the Compact Muon Solenoid (CMS) experiment at CERN. The study aims to reduce noise and preserve essential features of high-dimensional track data for High Energy Physics (HEP) analysis.

## Dataset
The dataset used is CMS Open Data from [CERN Open Data Portal](https://opendata.cern.ch/record/7730).

## Outputs
The code generates:

Original and reconstructed track histograms. Reconstruction Mean Square Error (MSE) for validation

## Results
The model demonstrated an MSE of 264.15, 427.62, and 155.73 which reflects the model's capability to accurately reconstruct tracks despite the inherent noise in experimental data. The histograms visually compare original and reconstructed tracks.

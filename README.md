# Prediction of Inorganic ABX3 Perovskite Material Properties Using ML 
  
## Project Overview:
  This repository presents the code and data for a comprehensive machine learning (ML) study focused on the prediction a of key properties of ABX3 inorganic perovskite materials using regression models.The dataset, originally sourced from the Open Quantum Materials Database (OQMD), contains 16,323 samples of perovskite structures and is designed for use in ML models to predict deterministic target properties. These target properties include:

* Formation energy
* Band gap energy

The dataset has been preprocessed to include 61 input features that describe the physicochemical, stability/geometrical, and Density Functional Theory (DFT) properties of the material, making it suitable for benchmark analysis in ML-driven materials discovery.

## Dataset:
* Source: Open Quantum Materials Database (OQMD)
* Size: 16,323 samples
* Features: 61 input features, including descriptors related to elemental sites in the ABX3 polyhedral and DFT-calculated properties.
* Target Variables:
** Formation energy (eV/atom)
** Band gap energy (eV)

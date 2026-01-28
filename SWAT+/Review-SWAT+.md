# [Review] Introduction to SWAT+, a completely restructured version of the soil and water assessment tool
K Bieger, 2017, Wiley Online Library

---
## What is SWAT+? What is different comparing with SWAT2012?
- need to address water quantity and quality in terms of speed and accuracy (Katrin Bieger et al 2016, JAWRA)
- SWAT limitation: Using HRU (efficient) but, transport and deposition process in the landscape are not explicitly accounted for (Arnold and Fohere 2005), major challenge will be additional spatial complexity (Gassman 2007)
- SWAT+ is far more flexible than SWAT in terms of the spatial representation of interactions and processes within a watershed (Katrin Bieger et al 2016, JAWRA)
- Basic algorithms used to calculate the processes in the model have not changed.
- 
- 

---
## Major difference: HRUs
- subbasin, landscape units (LSUs), HRUs : SWAT+ allows the user to select a grid-based model setup.

- 
---
## List of researches were conducted for resolution
- SWAT+ code and input files are tested in several watersheds
- High resolution global SWAT+ hydrological model (CoSWAT Model v1: A high-resolution global SWAT hydrological model
CJ Chawanda, A van Griensven… - Hydrology and Earth …, 2025 - hess.copernicus.org)
- (A comparative study of the effects of input resolution on the SWAT model
J Earls, B Dixon - WIT Transactions on Ecology and the Environment, 2005 - witpress.com): main do: SWAT model, Resampling resolution, sensitivity about resolution, how sensitive the SWAT model was to resolution of input data : still left relationship with..
- DEM uncertainties (Effect of DEM resolution, source, resampling technique and area threshold on SWAT outputs
ML Tan, HP Ramli, TH Tam - Water Resources Management, 2018 - Springer)
- DEM uncertainties ([HTML] Uncertainty of SWAT model at different DEM resolutions in a large mountainous watershed
P Zhang, R Liu, Y Bao, J Wang, W Yu, Z Shen - Water research, 2014 - Elsevier)

---
## Gap
- Don't have enough research about SWAT+ of resolution: A lot of developed high-resolution models
- They have model for high-resolution: But don't have uncertainty analysis with relationship: They only focus on how to use high resolution data efficiently
- SWAT+ : 1) High resolution modeling, 2) Climate change, 3) land use, crop management, 4) Compare SWAT and SWAT+,
- Main gap: SWAT already have done a lot of analysis with resoltion, However, We are not simple comparison of resolution, I plan to make **resolution + modeling + Uncertainty -> Uncertain to Develop Surrogated model**
- **Internel Input differences <-> Make a relationship with outputs <-> Expected Uncertainty range of outputs <-> learned model**

---
layout: page
title: Coding
menu: research
lang: en
---

# Coding

In pre-processing inputs and post-processing outputs for Agricultural Catchments Research Unit (ACRU) model, individual and combination of VBA, Python and Fortran scripts were created at Kienzle Watershed Research lab in the University of Lethbridge.

<br />

## Partial list of tools:

###"CCDST: A free Canadian climate data scraping tool"

 - a VBA script automated to download Environment Canada data
 - creates a master file for all climate data downloaded
 - see publication for more information

 <br />

### ACRU Climate Composite Grid Macro

 - a combination of VBA and Python script were created and a Fortran script using Harmonic analysis (Fourier Transformation) was revised
 - the tool updates the original 10K grid text files that contain daily Precipitation, Max and Min temperature to include daily Solar Radiation, Relative Humidity, Sunshine Hour and Wind Speed data

 <br />

### Hydrological Response Unit Delineation Script

  - a Python script created to automate the delineation of hydrological response unit (HRU) using ArcGIS 10.X
  - script incorporates functions found within the ArcPy module

  <br />

### Regional Climate Grid Downscaling Script

 - a python script created to automate the downscaling of the daily RCM data to daily 10K spatial resolution using percent ratio
 - script incorporates functions found within the ArcPy module

 <br />

### ACRU Menu Generator

 - a Fortran script automated to create a menu file in distributed mode

 <br />

### ACRU Sub-Menu Generator

 - a Fortran script automated to create a sub menu file using the original menu file in distributed mode

<br />

### ACRU Menu Initialization Script

 - a Fortran script automated to initialize an empty menu file in distributed module
 - requires using a spreadsheet that contains all the necessary parameters needed to be initialized once

 <br />

### ACRU Menu Parameterization Script

 - a Fortran script automated to parameterize an already initialized menu file in distributed module
 - requires using a spreadsheet that contains all the necessary parameters for Temperature, Streamflow and Snow verification

 <br />

### ACRU Temperature Verification Macro

 - a VBA script automated to analyze output files, using OBS and SIM temperature variables
 - script also automates creation of line and scatterplot graphs on the basis of seasonal trends and other statistics

 <br />

### ACRU Streamflow Verification Macro

 - a VBA script automated to analyze output files, using OBS and SIM streamflow variables
 - script also automates creation of line, scatterplot and box graphs on the basis of seasonal trends and other important statistics such as Mean Flow, Sum of Flows, Variance, Standard Deviation, Slope and Y-Intercept, Coefficient of Determination, Pearson's Correlation Coefficient, Percent Bias, Root Mean Square Error (RMSE), RMSE-observations standard deviation ratio (RSR), Nash-Sutcliffee Efficiency Index and Index of Agreement (d).

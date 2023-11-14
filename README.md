# Introduction 
## Background
One of the long-term targets in the *Basin Plan 2012* is that there will be an improvement in ‘condition, diversity, extent and contiguousness of native water-dependent vegetation’. The Basin-wide environmental watering strategy (BWS) elaborates on this with a number of quantified expected environmental outcomes (QEOs) for non-woody vegetation.

For Basin-wide vegetation monitoring, satellite imagery is often used. However, non-woody vegetation are often small and difficult to detect using satellite imagery. Drones can provide a way of imaging vegetation for a wetland. 

Unique spectral signatures (to put it simply, their colour) of vegetation species can be used to develop algorithms (machine-learning models) that can detect species from multi- and hyper-spectral remote sensing imagery. Spectral signatures are collected through direct measurement using a spectrometer and can be collected in-field using a portable spectrometer. They can also be extracted from imagery where ground sampling has been done (matching GPS locations of known plant species to the imagery). Spectral signature libraries are databases of spectral signatures of vegetation and other elements in terrestrial or aquatic environments e.g. soil. Spectral libraries can be accessed repeatedly and reduce the need to conduct in field data collection. Therefore they can enable the quantitative, repeatable and automatic mapping of vegetation types.

## Aim
The aim of this project was to test for Gwydir Wetlands whether we can develop a repeatable method of detecting vegetation species that can be applied at other locations, and to assess the usefulness of the National Spectral Database (https://www.dea.ga.gov.au/products/national-spectral-database).

## Results
The project resulted in a machine learning model (a support vector machine) which was capable of distinguishing non-woody vegetation species with an overall accuracy of over 90%. The results from this project highlight the efficacy of the approach in accurately mapping non-woody vegetation species over different water levels, even when ground samples are limited. Using UAV-based multispectral sensors, we have been able to provide detailed and up-to-date vegetation maps for wetland ecosystems. 

This project highlighted challenges with collecting spectra in ephemeral reed beds and the suggests that hyperspectral aerial imagery may be useful. To demonstrate this, an upscaled study was conducted at 1-m spatial resolution which could be collected by aeroplane (overall accuracy of 85%) and compared with the output at 0.05 meter (overall accuracy of 90%), suggesting the feasibility of using such a spatial resolution and the potential for using higher spectral resolution images. 

The report also highlights a number of barriers preventing adoption of the current NSD. Improvements to the NSD could see this become a useful repository and source of spectral data to aid vegetation mapping across the MDB, and Australia.

For more information see the report *Mapping of non-woody vegetation in the Gwydir Wetlands using multispectral sensors onboard unmanned aerial platforms*.

## Notebook
This notebook:
1. Imports imagery and ground samples
2. (Optional) Creates a machine learning model
3. Imports an existing machine learning model and classifies the imagery by species

## Contacts
Gabrielle Hunt Gabrielle.hunt@mdba.gov.au 

## Acknowledgements
Yue Wang and Pablo J. Zarco-Tejada (University of Melbourne) developed the code and report.

# wind_turbines_and_playas
repository for data on our project identifying which playas are in close proximity to wind turbines

Repository includes GIS layers of playa basins (from the Playa Lakes Joint Venture), Christmas Bird Count circles (National Audubon Society), Breeding Bird Survey routes (USGS), and wind turbine and associated ancillary structure locations (Federal Aviation Administration).

All GIS data are in the playas_turbines_GIS folder EXCEPT for the playas layer, which was too large to upload. This layer was the Playa Lakes Joint Venture's Probable Playas V4 Dec 2010 layer, downloadable from https://www.sciencebase.gov/catalog/item/5106df7ee4b0f227c1e4da7d. 

Bird data - see newCBC-master folder. In it, an R script (3.6.1) was built to query the CBC bird data from http://netapp.audubon.org/cbcobservation/, click on Current Year, and Count by Species. Designate the year and species for which you are collecting data, and save. Follow the R procedures in CBC_cirds_18Oct2019.R to compile data for Sandhill Crane, Northern Shoveler, and Northern Pintail from the years 1984 to 2016 from just the CBC circles of interest in our focal area.

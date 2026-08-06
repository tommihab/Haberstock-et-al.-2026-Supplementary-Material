For context the following section on the input data sets is cited from Haberstock et al. 2026

### Data collection and data preprocessing section 

The discharge data from the analysed study area is available open access from OpenGeodata.NRW (Landesbetrieb für Information und Technik NRW, 2025). All seven precipitation data sets were requested from the State Office for Nature, Environment, and Climate North Rhine-Westphalia (LANUK). The study period spans from 01.01.2007 to 01.01.2024, for which data from all mentioned stations are available in hourly resolution.
The original discharge data, recorded in 15-minute intervals, was averaged to create hourly values. Because missing values in time series data can cause model failure, data gaps in both discharge and precipitation records had to be addressed. Missing values in the hourly discharge data set were filled using linear interpolation. For the precipitation data, the availability of seven distinct measurement stations allowed for the use of Inverse Distance Weighting (IDW) to interpolate missing values more accurately based on spatial relationships.


Landesbetrieb Information und Technik Nordrhein-Westfalen. (2025). OpenGeodata.NRW: Hydrologische Daten (geprüft) [Data set].
https://www.opengeodata.nrw.de/produkte/umwelt_klima/wasser/oberflaechengewaesser/hydro/


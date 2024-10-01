# Validating wind data from the Ocean Observatories Initiative in high-latitude deployments

Author: Aaron Wickware (California State University, Monterey Bay)

2024 Woods Hole Partnership Education Program (PEP)

Mentors: Dr. Andrew Reed and Dr. Stace Beaulieu (Woods Hole Oceanographic Institution)

The Ocean Observatories Initiative (OOI) deploys meteorological instruments to perform ocean observations in high-latitude environments where collecting in situ observations has historically been challenging. OOI makes long-term quality observations of air and sea fluxes through these high-latitude deployments. Previous data analysis from multiple sensors has suggested that one type of the various sensors deployed, the Gill WindObserver II, has been under-recording wind speeds at higher magnitudes. This package will analyze wind sensor data acquired from buoy deployments and shipboard sensors during the Irminger Sea 11 Cruise. I compared wind data collected from two Gill WindObserver II 2-axis anemometers ("2-axis"), an R.M. Young Wind Monitor anemometer (RM Young), and a Gill R3 3-axis anemometer ("3-axis"), all mounted on OOI buoys, with two Vaisala WXT520 anemometers mounted on the bow of the R/V Armstrong.

METBK 1 deployment 10 (Instrument: Gill 2-axis - new firmware)
METBK 1 deployment 11 (Instrument: Gill 2-axis - old firmware)
METBK 2 deployment 11 (Instrument: RM Young)
FDCHP deployment 11 (Instrument: Gill R3 3-axis)
Ship Port and Starboard Sensors (Vaisala WXT520)

The underway.py file includes the code needed to parse the ship data.

The parse-wind-modules.py file is the script to parse the wnd.mat files into nc files.

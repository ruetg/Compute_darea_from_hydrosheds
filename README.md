A self-contained notebooks which shows how to compute stream networks, drainage area and other metrics from hydrosheds highest-resolution flow direction data (90m), over entire continents.  For all of Australia, the below notebook ran in about 20 minutes on a macbook with 16gb ram.

The hydrosheds data is available from their website: https://www.hydrosheds.org/downloads.

Note that some merging of tiles may need to be done in Arc or QGIS beforehand - seems more efficient than doing it in rasterio anyways

More information on the algorithms shown here are found in the simplem github repo guide: github.com/ruetg/SimpLEM

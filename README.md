# noaatsi
noaatsi is a PyPI package application to scrape the daily updated data from NOAA on TSI and to display the TSI graph.
Data is stored in the following site which will be automatically scraped by noaatsi:

https://www.ncei.noaa.gov/data/total-solar-irradiance/access/yearly/tsi_v02r01_yearly_s1610_e2021_c20220202.nc

NOAA file is based on netCDF4.
In order to read .nc file, netCDF4 library is needed to install by the following command.

$ pip install netCDF4

In order to install noaatsi, run the following command.

$ pip install noaatsi

To generate TSI file and the graph on the screen, run the following command.

$ noaatsi


noaa.png is finally generated.

<img src='noaa.png' height=400 width=600>

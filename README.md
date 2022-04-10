# noaatsi
noaatis is a PyPI package application to scrate the daily updated data from NOAA on TSI and to display the TSI graph.
Data is stored in the following site:

https://www.ncei.noaa.gov/data/total-solar-irradiance/access/yearly/tsi_v02r01_yearly_s1610_e2021_c20220202.nc

NOAA file is based on netCDF4.
In order to read .nc file, you can use netCDF4 library to read.

<pre>
$ pip install netCDF4

$ pip install noaatsi

To generate TSI file and the graph on the screen, run the following command.

$ noaatsi
</pre>

noaa.png is finally generated.

<img src='noaa.png' height=400 width=600>

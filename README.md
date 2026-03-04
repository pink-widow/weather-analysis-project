# Weather Analysis Project
In this project, I analyzed ERA5 reanalysis data from the Copernicus Climate Change Service for my birth date over a selected region. I processed pressure-level and surface data using Python, converted units, and generated five synoptic maps to study wind, temperature, pressure, and precipitation patterns.

-----

This project is a meteorological data analysis and visualization study based on ERA5 reanalysis data obtained from the Copernicus Climate Change Service through the Climate Data Store. In this project, I analyzed atmospheric conditions on my birth date at 12:00 UTC over the region 10°N–55°N and 25°W–75°W. I downloaded both pressure-level and single-level datasets in NetCDF format and processed them using Python.

I worked with geopotential, temperature, and wind components (u and v) at the 1000 hPa, 500 hPa, and 250 hPa pressure levels, as well as 2 m temperature, 10 m wind, mean sea level pressure, and total precipitation at the surface. I used xarray to read and explore the datasets, converted all variables to appropriate physical units (°C, mbar, mm, and meters), and prepared the data for visualization.

For mapping, I used matplotlib and cartopy with a geographic projection to generate five synoptic maps: upper-level wind at 250 hPa, temperature and geopotential height at 500 hPa, near-surface temperature at 2 m, smoothed mean sea level pressure with surface wind vectors, and total accumulated precipitation. I applied Gaussian smoothing to the pressure field to reduce small-scale noise and improve clarity.

Finally, I interpreted the synoptic situation of that day by identifying large-scale atmospheric features such as high- and low-pressure systems, troughs, ridges, circulation patterns, and precipitation distribution. This project demonstrates practical skills in atmospheric data handling, unit conversion, scientific visualization, and basic synoptic meteorological analysis using reanalysis datasets.


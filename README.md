# INTGRIDThesis
Modelling redispatch in the European power grid using PyPSA-Eur

The repository's jupyter notebooks are meant to be run in numerical order. The four files beginning with index (4) can be run in any order, but all four must be run before Analyses (5) can be run. The projected processing times for an 8GB RAM machine are listed below:

(1) ~3 hours
(2) ~48 hours
(3) ~72 hours
(4_1) ~4.5 hours
(4_2) ~30 minutes
(4_3) ~30 minutes
(4_4) ~72 hours
(5) ~5 minutes

Before running file (1), 'elec_s.nc' must be downloaded from https://zenodo.org/record/3601882#.X56rVohKi00 and added to the Network_Data folder. This file is not included with the rest of the data files due to size. Similarly, 'renewable_power_plants_EU.csv' must be downloaded from https://data.open-power-system-data.org/renewable_power_plants/ (must first be filtered for 'WIND' and 'SOLAR' tags) and added to Network_Data.

# Exploring Dataset "LDQUANTS: Laser Disdrometer Quantities"
### About LDQUANTS
Disdrometers are precipitation instruments that measure drop size distributions (DSD) and associated rainfall rates/accumulation as those raindrops fall to the ground. These DSDs are a quantity of interest to modeler and observational communities. However, use of disdrometer data for model evaluation, radar monitoring, or other activities requires careful quality control and processing for key DSD properties of interest (e.g., the number concentration of drops) to ensure appropriate physical (scattering, fall speed) assumptions. LDQUANTS uses standard methods from Tokay et al. (2013 and 2014) to filter drops with unrealistic fall speeds. Further, it estimates several microphysical/geophysical quantities of parameterized DSDs (gamma or exponential assumption type fitting methods) as in following previous disdrometer studies and ARM long-term efforts.

Disdrometers are also beneficial for cross-checks with other instrumentation, including rain gauges and radars. To support research interests and related radar monitoring activities, this product calculates radar-equivalent quantities, including dual-polarization radar quantities and additional wavelength, temperature, and drop shape assumptions. Key derived properties include:

- Liquid water content
- Hydrometeor size
- Precipitation
- Radar reflectivity

The LDQUANTS dataset includes data collected over the following locations and time ranges:



| site | facility | start_date | end_date   |
| :--- | :------- | :--------- | :--------- |
| guc  | M1       | 2021-09-01 | 2023-06-15 |
| guc  | S2       | 2021-09-03 | 2023-06-15 |
| ena  | C1       | 2014-02-27 | 2023-12-18 |
| hou  | M1       | 2021-08-05 | 2022-09-30 |
| hou  | S1       | 2021-08-18 | 2022-10-01 |
| hou  | S2       | 2022-04-12 | 2022-05-12 |
| hou  | S3       | 2022-05-05 | 2022-09-30 |
| epc  | M1       | 2023-01-15 | 2023-12-10 |
| epc  | S2       | 2023-01-15 | 2023-12-10 |
| mao  | S10      | 2014-09-24 | 2015-12-01 |
| sgp  | C1       | 2016-11-02 | 2023-12-18 |
| sgp  | E13      | 2016-11-04 | 2023-09-28 |
| sgp  | I10      | 2016-11-28 | 2023-09-28 |
| sgp  | I8       | 2016-12-05 | 2023-09-28 |
| sgp  | I9       | 2016-11-28 | 2023-09-28 |

### Exploring Variables
To explore plots of this dataset's variables for a specific location and specified time range, please open the Data Analysis Notebook

### Downsampling the Data
To downsample this dataset for a specific location, time range, and set of variables, please open the Downsampling Notebook

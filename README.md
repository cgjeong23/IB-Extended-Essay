# IB-Extended-Essay

This is a data processing space for my IB extended essay. The topic of my research is "To what extent does the diffusion rate of COVID-19 in Seoul reflect the socio-economic status of particular districts?"

### COVID-19 Data
COVID-19 data for daily number of newly infected individuals was sourced from Seoul Open Data portal.
The number of newly infected individuals in a district was divided by the population census of the district to calculate the diffusion rate for each district.

The diffusion rate in the time period of Fifth Wave of COVID (omicron) was plotted using plotly library

### Socioeconomic Data
Socioeconomic data for districts were sourced from Seoul Open Data Portal. These include GDP per capita, social trust, education finance, number of medical facilities
and beds for each district. These variables were collected and processed into a dataframe. Then cumulative rank of socioeconomic development was calculated from the dataframe.

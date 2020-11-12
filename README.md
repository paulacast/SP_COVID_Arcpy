# SP_COVID_Arcpy

COVID-19 in Sao Paulo State, Brazil: Automating Thematic Map & Chart.

To be used inside ArcGIS Pro version 2.5 or above. 

Scheme:

Daily CSV tables with COVID-19 data are published everyday on the Sao Paulo State Health Department website.

User downloads the csv file at https://www.seade.gov.br/coronavirus/

Script in ArcGIS Pro Notebook:
  Reads the CSV file
  Performs a table join operation to merge the CSV data to a Sao Paulo State shapefile that contains the state cities 'limits
  Performs operations to obtain the Death Rate of each city
  Generates a bar chart displaying the COVID-19 death rate by city
  Generates a thematic map of the cities’ death rate
  Exports a layout containing the chart and the thematic map to a PDF file

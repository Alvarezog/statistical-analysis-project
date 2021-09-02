# statistical-analysis-project

## Introduction

This project uses the most recent gas prices for Mexico City to calculate the potential savings when a driver decides to drive a few miles to a gas station that has a lower price. This experiment is repeated for all the gas stations in Mexico City and for different max distances the driver is willing to drive.

## Workflow

1 - `xml_to_pandas.ipynb` - This notebook transforms the gas station locations, and gas prices in XML files to a pandas data frame for later use.\
2 - `filtering_cdmx_gas_stations.ipynb` - The data frame created in the previous notebook contains all the gas stations for Mexico. This notebook filters only the gas stations located in Mexico City using an shp polygon.\
3 - `fuel_savings_calculations.ipynb`- This notebook makes all the calculations and statistical analysis needed to obtain the potential savings.

All the files with the raw data needed for this project are located in the main project folder.
# StClairCovid
### St Clair County IL Covid infection and vaccination tracking

The St Clair County (IL) Health Department offers daily Covid numbers to the public, but are consistently asked for information they don't provide:
 - Historical infection rates
 - Vaccination percentages

Some residents do manual tracking, but the State of Illinois makes the data available on the [Covid Portal](http://www.dph.illinois.gov/covid19/data-portal).  Illinois provides dashboards, but focuses on current day numbers.  It's difficult to see the larger picture of infection and vaccination.

This project gathers information about county infection rates and county/state vaccination efforts over time.

## Data Included

### Vaccination Rates
 - St Clair county
https://idph.illinois.gov/DPHPublicInformation/api/COVIDExport/GetVaccineAdministration?format=csv&countyName=St.%20Clair

 - Illinois
https://idph.illinois.gov/DPHPublicInformation/api/COVIDExport/GetVaccineAdministration?countyname=&format=csv

### Infection Rates - St Clair County
https://idph.illinois.gov/DPHPublicInformation/api/COVID/GetCountyHistorical?countyName=St.%20Clair

### Population Data
http://www.dph.illinois.gov/covid19/vaccinedata?county=Illinois

### Additional Data
Information added to original data sets:
 - Day of Week and Percentage Fully Vaccinated (Vaccination Data)
 - New Daily Infections (Infection Rates)

## Running the Project
This project can be run in Jupyter Notebooks.  Data is pulled directly from the Illinois Covid Portal so will be current.

## Sample Figures
Sample figures from this project are storied in /notebooks.

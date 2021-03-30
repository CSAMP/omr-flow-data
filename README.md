# Old and Middle River Flow Data
This repository contains flow data at the old and middle rivers to describe flow in the delta. 

# Data Format 
The `OMR_daily.txt` is a matrix containing daily flow of the OMR.  Old and Middle River flow has dimensions year _y_ and month _m_. 

# Methods for Preparing OMR Data for MOdel Input
by Will Smith 

OMR<sub>ym</sub> was the monthly average of the daily sum of tidally filtered flows from two adjacent channels 
of the San Joaquin River basin, Old and Middle Rivers (Fig. 2). OMR data were available from US Geological Survey 
(USGS) [streamflow databases](https://waterdata.usgs.gov). Much of the daily streamflow gauge data was missing. 
If data for one river was missing, daily OMR was predicted from a linear model of the flow in the remaining river, 
and if data for both rivers was missing, the model proposed by Andrews et al. (2016) was used to estimate missing 
OMR from San Joaquin River flows and exports from South Delta water diversions. Daily San Joaquin River flow and 
export data were available from the [Dayflow database](https://data.cnra.ca.gov/dataset/dayflow).

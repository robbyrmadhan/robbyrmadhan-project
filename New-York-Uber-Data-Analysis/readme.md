# Analysis Uber data in New York City
**Team member:**

***Abdulrahman Alsalamah***


 
## Problem statement 

In the new york city There are a lot of people using Uber and a taxi to get around the city and go to work, It is important for companies to know the movement of people in order to deal with the time of the traffic and to increase the company's profits and serve customers better and right in time.


## Audience

Traffic congestion analysis is important for companies to serve customers in the right time to increase Customer Satisfaction
and an increase in revenue.
It is also important for the police department to manage traffic congestion in a better way.

## Success Metric

Discover address has the most requested order.
reduce traffic congestion by mange Uber drivers

## Data-Set 

dataset contains, roughly, four groups of files:

- Uber trip data from 2014 (April - September), separated by month, with detailed location information
- Uber trip data from 2015 (January - June), with less fine-grained location information
- non-Uber FHV (For-Hire Vehicle) trips. The trip information varies by company, but can include day of trip, time of trip, pickup location, driver's for-hire license number, and vehicle's for-hire license number.
- aggregate ride and vehicle statistics for all FHV companies (and, occasionally, for taxi companies)
### Uber trip data from 2014
There are six files of raw data on Uber pickups in New York City from April to September 2014. The files are separated by month and each has the following columns:

`Date/Time` : The date and time of the Uber pickup

`Lat` : The latitude of the Uber pickup

`Lon` : The longitude of the Uber pickup

`Base` : The TLC base company code affiliated with the Uber pickup
These files are named:


- `uber-raw-data-apr14.csv`
- `uber-raw-data-aug14.csv`
- `uber-raw-data-jul14.csv`
- `uber-raw-data-jun14.csv`
- `uber-raw-data-may14.csv`
- `uber-raw-data-sep14.csv`
- `Uber trip data from 2015`

Also included is the file `uber-raw-data-janjune-15.csv` This file has the following columns:

`Dispatching_base_num`: The TLC base company code of the base that dispatched the Uber

`Pickup_date` : The date and time of the Uber pickup

`Affiliated_base_num` : The TLC base company code affiliated with the Uber pickup

`locationID` : The pickup location ID affiliated with the Uber pickup

The `Base` codes are for the following Uber bases:

`B02512` : Unter `B02598` : Hinter `B02617`: Weiter `B02682` : Schmecken `B02764` : Danach-NY `B02765` : Grun `B02835` : Dreist `B02836` : Drinnen

For coarse-grained location information from these pickups, the file `taxi-zone-lookup.csv` shows the taxi `Zone` (essentially, neighborhood) and `Borough` for each `locationID`.

Non-Uber FLV trips
The dataset also contains 10 files of raw data on pickups from 10 for-hire vehicle (FHV) companies. The trip information varies by company, but can include day of trip, time of trip, pickup location, driver's for-hire license number, and vehicle's for-hire license number.

These files are named:

- `American_B01362.csv`

- `Diplo_B01196.csv`

- `Highclass_B01717.csv`

- `Skyline_B00111.csv`

- `Carmel_B00256.csv`

- `Federal_02216.csv`

- `Lyft_B02510.csv`

- `Dial7_B00887.csv`

- `Firstclass_B01536.csv`

- `Prestige_B01338.csv`

### Aggregate Statistics
There is also a file `other-FHV-data-jan-aug-2015.csv` containing daily pickup data for 329 FHV companies from January 2015 through August 2015.

The file `Uber-Jan-Feb-FOIL.csv` contains aggregated daily Uber trip statistics in January and February 2015.


## Challenge

working with huge data is required a huge process

## Time constraint

Two weeks for work in this project

I will do analysis then I will work in Time series



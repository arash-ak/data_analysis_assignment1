# Sporametri Air Quality data

This directory contains data of Sporametri Air Quality sensors. Total 4 sets of measuring
devices were used. Three of them were installed on trams driving on the streets of Helsinki.
One set was located on HSY Mäkelänkatu (supersite) measuring station.

The data collected from the sites moving with trams are named sporametri-movingsites-data*.
And those collected at Mäkelänkatu supersite sporametri-supersite-data*.

Data has been collected between February 2019 and August 2019.
Data has been divided in files based on month of timestamp.

All data is in gzipped CSV format sporametri-movingsites-data0419.csv.gz, which looks like this sample below:

timestamp,spora-id,latitude,longitude,NO,NO2,O3,CO,BME680_pressure,BME680_humidity,BME680_temperature,comment
1554085919,2,0.0,0.0,,,,,101672.0,45.637,18.56,
1554085919,2,0.0,0.0,4.59344,-0.43572799999999995,,,101671.0,45.655,18.66,
1554085920,2,0.0,0.0,4.5344,-0.397408,,,101667.0,45.571000000000005,18.65,
1554085921,2,0.0,0.0,4.4319999999999995,-0.481392,,,101667.0,45.53,18.65,
1554085922,2,0.0,0.0,4.37784,-0.4968,,,101671.0,45.486999999999995,18.67,
1554085923,2,0.0,0.0,4.30096,-0.54952,,,101670.0,45.431000000000004,18.69,
1554085924,2,0.0,0.0,4.23808,-0.40257600000000004,,,101670.0,45.375,18.71,
1554085925,2,0.0,0.0,4.17208,-0.457136,,,101669.0,45.306999999999995,18.72,
1554085926,2,0.0,0.0,4.08016,-0.467712,,,101667.0,45.25,18.73,

The columns are:

timestamp = time in seconds (starting from '1970-01-01 00:00:00')
spora-id = specifying the tram in which the devices were installed
latitude = latitude coordinate
longitude = longitude coordinate
NO = nitric oxide
NO2 = nitrogen dioxide
O3 = ozone
CO = carbon oxide
BME680_pressure = air pressure measured using BME680 sensor
BME680_humidity = humidity measured using BME680 sensor
BME680_temperature = temperature measured using BME680 sensor
comment

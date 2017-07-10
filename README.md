# Timeseries-for-S-P-500-DowJones-Nasdaq
This project contains advanced visualizations using Processing for the famous market indices S&amp;P 500, DowJones and Nasdaq 

## Introduction:
In this project we implemented a time series visualization with the help of Processing. The goal of this project is to show the closing prices for each of the benchmark indices i.e., S&P 500, DowJones and Nasdaq. We found these datasets from Yahoo’s finance website. 

## Examining the datasets:
The initial datasets have 7 columns which include Date, Open, High, Low, Close volume and adj close. This data begins from the year 1985 to 2016. In this project we mainly concentrated on visualizing the closing of the value i.e., “Open” column with respect to the date.  As our code is mostly inspired from the Ben Fry’s text we had to make some changes for our datasets. 

## Preparing the data:
As the initial data contains lot of noise we had to clean the data. We used Excel with KUTools for this. We removed the N/A values. We transformed the three datasets into one which is similar to the one mentioned the text book. Due to limited amount of time we selected one data point in Date column of each dataset which is Nov 1 of all the three datasets beginning from 1985 to 2016. We prepared the data into tab separated value. Which has following columns: Date, DowJones, Nasdaq and S&P500. 

## Processing code:
In the attached file you can see the processing code which contains 3 .pde file which includes codes. The main file is Time_series which dependent on FloatTable and Integrator. The floattable class which contains some of the main methods like floattable, scqrubqotes, getrowindex, getcolumncount. The main file contains some important methods like draw, drawtitletabs,  drawdataarea etc., 

## Result:
Below is the output of the time series visualization with the above processing code. On the Y axis we have the open value column and on Y axis we have years ranging from 1985 to 2015 with 5 years interval.

<b> Output of Open DowJones: </b>
![openouput](https://user-images.githubusercontent.com/20802996/28037994-5876732a-658b-11e7-9387-03257cd26e10.jpg)



<b> Output of Open Nasdaq: </b>
![outputnasdaq](https://user-images.githubusercontent.com/20802996/28038033-7d50180e-658b-11e7-9b35-72685fe8ee59.jpg)



<b> Output of Open S&P 500: </b>
![s poutput](https://user-images.githubusercontent.com/20802996/28038078-a4b0d384-658b-11e7-8a97-4bf7c0fc4924.jpg)



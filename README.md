# Module 11 Challenge

## Overview

The goal of this project is to analyse Mercado Libre's financial and user data to predict search traffic and translate that into the ability to successfully trade the stock. This was done using timeseries data and Prophet forecasting.

## Technology

Python 3.9.7 was used to code this challenge. The below libraries were required:
- numpy
- pandas
- hvplot
- prophet

## Usage

Google Collab was used instead of Jupyter Lab. More information on Google Collab can be found using [here](https://www.geeksforgeeks.org/how-to-use-google-colab/).

## Findings

Search Traffic vs Released Financial Results

* Google search traffic increased during the month that Mercado Libre released its financial results.

Search Traffic During the Day

* There is a significant increase in searches towards the beginning and end of the day rather than the middle of the day.

**Holiday Search Traffic**

* Search traffic tends to increase during the winter holiday period and then drops after week 51, during Christmas and New Years Eve.

**COVID-19 Impact on Closing Prices and Searches**

* There tends to be a sharp decline in stick closing prices and searches in March - at the start of the COVID-19 pandemic. Search trends and stock prices gradually recovered over the next couple of months.

**Lagged Search Traffic vs Stock Volatility & Stock Price Return**

* There is little correlation between lagged search traffic and stock volatility. The same can be said for the correlation (or lack of) between lagged search traffic and the stock price return.

**Calendar Search Traffic**

* Midnight exhibits the greatest popularity for search traffic.
* Tuesday gets the most search traffic.
* Mid-October is the lowest point for search traffic in the calendar year.

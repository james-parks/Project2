---
title: "Capstone Project 2 Proposal"
author: James Parks
output: html_document
---




# Predicting Ontario energy demand with historical weather data

### The Problem

It's clear that weather plays a huge influence in energy demand and monitoring and energy companies need to be able to anticipate large spikes in demand byt playing close attention to the weather. In this project we look at the historical hourly energy demand of Ontario, Canada from 2002- July 2017 along with the historical hourly weather data for Toronto from the same time period. 

### The Client
The client in this case is the Ontario Energy Board, which monitors energy usage for the province of Ontario. Having a more robust model for determining just how much changes in weather affect energy demand can be extremely beneficial in saving money and preventing blackouts. Based on this analysis they will be better able to adjust supply to meet expected demands with the changes of seasonal weather.
Note that although this data is only for Ontario, the analysis may also be of benefit to other regions with similar weather patterns and populations. 


### The Data
The Data comes from two sources.

- Independent Electricity System Operator, http://www.ieso.ca/power-data which has a .csv file for the hourly energy demand for the province of Ontario from 2002-July 2017.
- Environment Canada, which has .csv files for the hourly weather data for many locations in Ontario for the same time period. To start with we choose the data for Toronto, since its urban area accounts for a large percentage of the population of Ontario and make the assumption that its energy demand will contribute to the largest demand in the province.



### Approach Outline
- Download the data. This step has already been performed.
- The hourly energy demand dataset is available in two separate files so joining them together will be relatively easy. Each month of the weather data is contained in its own .csv file so it will require more data wrangling to combine.
- Perform exploratory data analysis on the time series weather data. Look for outliers in different categories and see if these correspond to extremes in energy demand.
- Look at a heatmap of variable correlation to investigate the relationship between energy demand and temperature, precipitation and humidity. 
- Use regression machine learning algorithms for modeling.

### Deliverables
The analysis will be delivered in a jupyter iPython notebook on github along with a Powerpoint presentation and project report of the most interesting trends and most accurate models found in the analysis. 

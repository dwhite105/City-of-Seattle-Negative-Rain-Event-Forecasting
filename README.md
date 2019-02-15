# City-of-Seattle-Negative-Rain-Event-Forecasting
Daniel White, City of Seattle Innovation and Performance Team
November 2018 - December 2018

## Motivation

This repository contains the work I performed during an internship with the City of Seattle Innovation and Performance Team. The objective of the project was to develop a model that can help the city better predict "negative rain events". A negative rain event is loosely defined as rain that results in a high number of maintenance work orders, sewer overflows, etc.

## Data
The primary data used for the project is proprietary and has not been included. However, I have provided a brief description of the datasets below:

* **Seattle Historical Hourly Precipitation** - Contains the precipitation by the hour for several rain gauges across the city dating back to 2003.

* **Maximo Work Orders Data** - Contains all maintenance order requests filed from the city system since 2006

The repo also contains a sample file from the NAEFS precipitation forecast. The model can take in new forecast files and make predictions for the upcoming days.

## Overview of Notebook

The Jupyter Notebook provides the code used to clean the data, train the logistic regression model, and assess its performance. The output of the model includes a threat level (Low, Medium, High, Very High) for a particular day. The Jupyter Notebook includes extensive comments and visualizations to help users better understand the process. 
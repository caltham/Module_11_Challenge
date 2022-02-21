# Module_11_Challenge

UNCC Online FinTech Bootcamp Module 10

-----

## Executive Summary

As a growth analyst at MercadoLibre, I've been tasked with analyzing the company's financial and user data in clever ways to make the company grow. In a bid to drive revenue, I’ll produce a Jupyter notebook that contains the data preparation, analysis, and visualizations for all the time series data that the company needs to understand.

-----

## Technologies / Installation Guide

This application is written in Python 3.7 using JupyterLab version 3.0.14.

Import the following libraries:

- pandas (an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.)
- Pathlib (a library that enables consistent input and output of files from the main app.)
- hvPlot (a high-level plotting API for the PyData ecosystem built on HoloViews.)
- scikit-learn (an open source machine learning library that supports supervised and unsupervised learning.)
- plotly (an interactive, open-source, and browser-based graphing library for Python.)
- seaborn (a visualization library that provides a high-level interface for drawing attractive and informative statistical graphics.)
- prophet (a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects)

-----

## Usage

The `forecasting_net_prophet.ipynb` notebook will be used to complete the following tasks:

- Find unusual patterns in hourly Google search traffic
- Mine the search traffic data for seasonality
- Relate the search traffic to stock price patterns
- Create a time series model with Prophet
- Forecast revenue by using time series models

-----

## Forecast Visualizations

<img width="642" alt="forecast_1" src="https://user-images.githubusercontent.com/94569323/154889137-8ccd3fa3-6c24-4939-a689-7d2530407fe7.png">

<img width="673" alt="forecast_2" src="https://user-images.githubusercontent.com/94569323/154889151-8de742bd-8ab0-481b-b97f-d5067e781463.png">

-----

## Results

- Given that the monthly value of May was 108% of the median monthly value, it clear that the Google search traffic increased during the month of May.
- According to the hvplot, it appears as if the traffic concentrates between the hours of 10 pm and 1 am.
- According to the hvplot it is clear that the traffic tends to increase between months 40 and 52.
- According to the hvplots, both time series indicate a trend that is consistent with the narrative.
- The correlation between lagged search traffic and stock volatility is -0.12, whereas the correlation between lagged search traffic and stock price returns is 0.018.
- It looks like it's in for a little dip in the near-term.
- According to the visualizations, it appears as if midnight exhibits the greatest popularity.
- According to the visualizations, Tuesday gets the most search traffic.
- According to the visualizations, October is the lowest point for search traffic.

-----

## Contributors

Chancie Altham

-----

## License

MIT License
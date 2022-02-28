# Outlier_detection

This repository contains code that funcitons to detect outliers in a large time series data set. Specifically, data has been imported from a mooring station in the Baynes Sound region with a time series of CO2 concentrations. The aim of this project is to accurately identify all outliers from the CO2 remote sensor using the Local Outlier Funciton (LOF; similar to K-nearest neighbours in its funcitoning). Essentially, it groups the data into "K" amount of groups, and calculates relative distances between each points and groups in order to identify outliers. 

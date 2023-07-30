# ANN-Regression-Model
Building an ANN Regression Model to Predict Electrical Energy Output of a Combined Cycle Power Plant

## Dataset info

The dataset comprises 9568 data points gathered from a Combined Cycle Power Plant in operation at full capacity for six years (2006-2011). The features include hourly averages of ambient variables such as Temperature (T), Ambient Pressure (AP), Relative Humidity (RH), and Exhaust Vacuum (V), which can help predict the net hourly electrical energy output (EP) of the power plant.

A power plant that operates on a combined cycle (CCPP) consists of gas turbines (GT), steam turbines (ST), and heat recovery steam generators. This type of power plant generates electricity by using both gas and steam turbines, which work together in a cycle and transfer energy from one turbine to the other.

The dataset used in this study is sourced from the UCI Machine Learning Repository and is licensed under a Creative Commons Attribution 4.0 International (CC BY 4.0) license. 

Citation details are as follows
Tfekci, Pnar and Kaya, Heysem. (2014). Combined Cycle Power Plant. UCI Machine Learning Repository. https://doi.org/10.24432/C5002N

## Objective

Our main objective for this project is to create a regression model using ANN that can predict the hourly net electrical energy output of the CCPP with high accuracy. To achieve this, the model will consider variables such as temperature, ambient pressure, relative humidity, and exhaust vacuum.

The process of building the ANN regression model involves several steps
* Data Preprocessing
* Building an ANN
* Training the ANN

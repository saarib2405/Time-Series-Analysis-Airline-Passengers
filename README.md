# AirPassengers ARIMA Forecasting

This repository contains a Python script for forecasting the number of airline passengers using the ARIMA (AutoRegressive Integrated Moving Average) model. The dataset used is the classic "AirPassengers" dataset, which contains monthly totals of international airline passengers from 1949 to 1960.

## Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)

## Introduction

The goal of this project is to demonstrate how to use the ARIMA model for time series forecasting. The script performs the following steps:
1. Loads the AirPassengers dataset.
2. Visualizes the time series data.
3. Fits an ARIMA model to the data.
4. Makes predictions for the next 24 months.
5. Visualizes the forecast along with confidence intervals.

## Requirements

To run this script, you need the following Python libraries:
- `pandas`
- `matplotlib`
- `statsmodels`

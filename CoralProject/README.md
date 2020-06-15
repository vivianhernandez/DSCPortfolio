README-Coral Project

Coral reef structures are extremely important to marine biodiversity, accounting for a home for about a quarter of all marine life. U.S. coral reef sites are currently dealing with unprecedented declines. Ocean stressors like ocean acidification, rising temperatures and lower pH temperatures all negatively affect corals. This project created a model that categorizes regions of the U.S. coral reef system as at risk or not. 
I used water composition data collected and coral mortality data from the U.S. Reef structures to build the model. The model is able to take in data from datasets with 37 different factors and classify risk with 98% precision. 
Pinpointing high risk sections of the US coral reef sites can allow scientist to preserve the remaining sites through conservation measures. 

Getting Started

This program uses a Random forest model to predict risk level. The dataset that I will be analyzing for my project is from the National Oceanic and Atmospheric Administration’s (NOAA) Nation Center for Environmental Information.This data set includes data collected between mid-2013 to mid-2014 separated by region and location. This dataset includes key ocean stressors dissolved CO2, pH and temperature. The data frame selected has 232 observations of 37 variables (https://doi.org/10.7289/v5d50k2g). 

Prerequisites

The following packages are needed
import pandas as pd
import numpy as np
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestClassifier

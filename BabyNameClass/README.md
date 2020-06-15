README-Baby Names Classifier

This project is a binary logistic regression model in PySpark.

Getting Started

This program was created on Databricks Community Edition. This program uses data from Bellevue University’s DSC 650 class. This data was accessed through GitHub (https://github.com/vivianhernandez/dsc650). 

Prerequisites

The following packages are needed
from pyspark.sql import SparkSession
from pyspark.ml import Pipeline
from pyspark.ml.feature import OneHotEncoderEstimator, StringIndexer, VectorAssembler
from pyspark.ml.classification import LogisticRegression

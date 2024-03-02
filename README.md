# Machine Learning Indicator Project!
## Project Description
In this Project we incorporate SMA (Simple Moving Average), Force Index, and RSI (Relative Strength Index) with machine learning.  The intention here is to build a trading strategy or model that uses historical price data along with these technical indicators, to make predictions about future price movements. The required data, which in this case is the NASDAQ 100 (QQQ), is extracted using Y-Finance (API).  The top 100 most traded and significant companies listed on the Nasdaq stock exchange make up the Nasdaq 100 Index. Companies from many areas, including manufacturing, technology, healthcare, and others, are included in the index. Nevertheless, financial institutions such as commercial and investment banks are not included in this particular index.  As demonstrated in this project, the RSI Indicator has continuously demonstrated its ability to correctly predict future profits when it comes to the QQQ. For traders hoping to increase their profit margin and attain more financial success, this is crucial.
## Required Imports
import pandas as pd
,from pandas.tseries.offsets import DateOffset
,import yfinance as yf
,from datetime import datetime
,from sklearn.model_selection import train_test_split
,from sklearn.ensemble import RandomForestClassifier
,from pandas.tseries.offsets import DateOffset
,from sklearn.impute import SimpleImputer
,import numpy as np
,from sklearn import svm
,import holoviews as hv
,hv.extension('bokeh')
,import hvplot.pandas
,import matplotlib.pyplot as plt
,from sklearn.preprocessing import StandardScaler
,from sklearn.linear_model import LogisticRegression
,from sklearn.metrics import accuracy_score
,from sklearn.metrics import classification_report
,from sklearn.metrics import accuracy_score, classification_report, confusion_matrix
,from finta import TA
,import warnings
,warnings.filterwarnings('ignore')

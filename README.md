# BTC-Predictor
Predicting BTC prices to USD with RNN, FFNN and AutoTS etc.

import yfinance as yf
import pandas as pd
from autots import AutoTS
from sklearn.neural_network import MLPRegressor
from sklearn.neighbors import KNeighborsRegressor
import matplotlib.pyplot as plt
from datetime import datetime, timedelta
import numpy as np

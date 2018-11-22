# MSBD5001-individual-kmkwongaa-
MSBD5001-individual(kmkwongaa)

Programing Language: Python
--------------------------------------------------------------------------------

Required package:
import numpy as np
import pandas as pd
from keras.models import Sequential
from keras.layers import Dense
from keras.wrappers.scikit_learn import KerasRegressor
from sklearn.model_selection import cross_val_score
from sklearn.model_selection import KFold
from sklearn.preprocessing import StandardScaler
from sklearn.pipeline import Pipeline
import tensorflow as tf
from tensorflow import keras
from keras.constraints import non_neg
import matplotlib.pyplot as plt
import seaborn as sns
from keras import regularizers

from pandas import read_csv
from sklearn.metrics import mean_squared_error
from matplotlib import pyplot

from keras.layers.normalization import BatchNormalization
from keras import optimizers
----------------------------------------------------------------------------

How to run it:
Complile it on Jupyter Notebook
----------------------------------------------------------------------------

(1) Please specify it when running your jupyter notebook directly will do. 
1. Read train.csv
2. Feature engineering: create and drop some features
3. Get dummy for the categorical features
4. Set n_jobs to 16 for -1
5. Join the dataframe
6. Find correlation and plot graph
7. Read the my submitted csv with best result in public ranking
8. Read test.csv and create / drop features
9. Create Keras model
10 Use the model to predict the result
11. Import the result into csv
12. Cross check with the best result
13. Please note that you need to add "Id" in the csv before submitting the result
----------------------------------------------------------------------------

(2) Windows users may be required for demo, if you don't know how to run it on Linux.
OK



# Module-13-Neural-Network
Venture Funding with Deep Learning
Given  a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. I will use machine learning and neural networks and use the features in the provided dataset to create a binary classifier model that will predict whether an applicant will become a successful business. The CSV file contains a variety of information about these businesses, including whether or not they ultimately became successful.

the following libraries were imported to complete the task:
import pandas as pd
from pathlib import Path
import tensorflow as tf
from tensorflow.keras.layers import Dense
from tensorflow.keras.models import Sequential
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler,OneHotEncoder

The steps for this challenge are broken out into the following sections:
- Prepare the data for use on a neural network model
-compile and evaluate a binary classification model using a neural network
-Optimize the neural network model

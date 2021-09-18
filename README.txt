## Project Introduction
In this Classification Machine Learning Project, we will be analysing the dataset taken from www.kaggle.com related to details of credit card owners. This data consists of features like Gender, Income type, House type, marital status and many more. Our focus will be on analysing the data, getting the insights related to these features and there role in affecting the target, we will perform feature engineering, feature selection and develop a Classification model that will predict whether it is a Fraud or not based on the new data.

## Important Libraries required for the Classification Model

-import numpy as np
-import pandas as pd
-import seaborn as sns
-import matplotlib.pyplot as plt
-from imblearn.combine import SMOTETomek
-from sklearn.preprocessing import MinMaxScaler
-from sklearn.model_selection import train_test_split
-from sklearn.neighbors import KNeighborsClassifier
-from sklearn import metrics

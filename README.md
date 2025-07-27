# Geol_logging_dataset

## Introduction

I put into practice what I learned in the Statistics and Machine Learning training organized by Oracle Next Education and AluraLatam. 
I used data from a production oil well log from the public Kaggle database (https://lnkd.in/gk6XanEY).

Supervised learning techniques (linear regression) and unsupervised learning techniques (clustering) were used.

Data were added to the DataFrame based on available data, for example, VP from DTC, and VS derived from VP.

## Used libraries
### Exploratory analysis
* import pandas as pd
* import numpy as np
* import matplotlib.pyplot as plt
* import seaborn as sns
* import plotly.express as px

### Machine learming
* import statsmodels.api as sm
* from sklearn.cluster import KMeans
* from sklearn.preprocessing import StandardScaler
* from sklearn.linear_model import LogisticRegression
* from sklearn.ensemble import RandomForestClassifier
* from sklearn.model_selection import RandomizedSearchCV,train_test_split
* from sklearn.metrics import accuracy_score
* from sklearn.impute import SimpleImputer

### Dataset
* Density (gr/cm³) [RHOB] from 1.40 to 2.92
* Gamma rays (API) [GR] from 6.19 to 499.02
* Depth_MD ( feet) [DEPTH_MD] from 494.52 to 3272.02
* Neutron  (fraction) [NPHI]  from 0.02 to 0.80
* Photoelectric factor (barns/electron) [PE] from 1.01 to 66.03
* Compresional sonic ($\miu$/feet)

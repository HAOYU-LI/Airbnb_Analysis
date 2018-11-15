# Airbnb_Analysis

Use Airbnb Inside dataset from Boston and Seattle area to do renting price prediction.

# Motivation
This project aims to answer three questions:
- Is there any difference in average price between Boston and Seattle area?
- Can we predict price in Boston and Seattle Airbnb using this dataset?
- What are the top important features when predicting the price in two cities?


# Library usage
This project used python to conduct data modeling. Visualization abd machine learning libraries in python are applied.
```
import numpy as np
import pandas as pd
import mplleaflet
import seaborn as sns
from tqdm import tqdm
from xgboost import XGBRegressor
from matplotlib import pyplot as plt
from xgboost import plot_importance
from sklearn.model_selection import GridSearchCV
from sklearn.model_selection import train_test_split
```

# Result:

## Renting price prediction
<img src="./results/boston-prediction.png"><br>

<img src="./results/seattle-prediction.png"><br>

## Top important features

<img src="./results/boston-features.png"><br>

<img src="./results/seattle-features.png"><br>


# Useful links
* [Blog](https://medium.com/p/4f73ab8981d8/edit) - A blog to introduce this analysis.

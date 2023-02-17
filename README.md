# ML-HW1-data

PART 1:
In part 1, we have created a LinearRegressionModel class, where we adjust the w and b values according to the gradient descent formulas discussed in class. In order to build and run this code, sklearn and pandas must be installed in order to utilize the library functions. Each section must be compiled and run  in chronological error for the latter code to work properly. 

PART 2:
!pip install sklearn
  We used sklearn throughout part 2 for multiple functions and packages.

import pandas as pd
  The panda library was used in the pd.read command in order to create the dataframe.

from sklearn.metrics import r2_score, mean_squared_error
  Both of these functions were used to calculate our evaluation statistics. 

from sklearn.preprocessing import StandardScaler
  Used to standardize the dataframe.

from sklearn.model_selection import train_test_split
  Function used to split the dataframe into test and train data.
    
from sklearn.linear_model import SGDRegressor
  Package used for the linear regression model using gradient descent.

# temp-remedy-for-pandas_datareader-v0.6.0
remedy  for trouble when importing pandas_datareader v0.6.0

import packages like below:

import pandas as pd

pd.core.common.is_list_like = pd.api.types.is_list_like

import pandas_datareader as web


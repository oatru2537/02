#IPython is what you are using now to run the notebook
import IPython
print("IPython version:      %6.6s (need at least 5.0.0)" % IPython.__version__)

# Numpy is a library for working with Arrays
import numpy as np
print("Numpy version:        %6.6s (need at least 1.12.0)" % np.__version__)

# SciPy implements many different numerical algorithms
import scipy as sp
print("SciPy version:        %6.6s (need at least 0.19.0)" % sp.__version__)

# Pandas makes working with data tables easier
import pandas as pd
print("Pandas version:       %6.6s (need at least 0.20.0)" % pd.__version__)

# Module for plotting
import matplotlib
print("Matplotlib version:    %6.6s (need at least 2.0.0)" % matplotlib.__version__)

# SciKit Learn implements several Machine Learning algorithms
import sklearn
print("Scikit-Learn version: %6.6s (need at least 0.18.1)" % sklearn.__version__)

# Requests is a library for getting data from the Web
import requests
print("requests version:     %6.6s (need at least 2.9.0)" % requests.__version__)

#BeautifulSoup is a library to parse HTML and XML documents
import bs4
print("BeautifulSoup version:%6.6s (need at least 4.4)" % bs4.__version__)

import seaborn
print("Seaborn version:%6.6s (need at least 0.7)" % seaborn.__version__)

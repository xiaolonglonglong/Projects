# Projects
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
%matplotlib inline
color = sns.color_palette() 
sns.set_style('dark')
import warnings
def ignore_warn(*arg,**kwargs):
    pass
warnings.warn = ignore_warn 
from scipy import stats
from scipy.stats import norm,skew
pd.set_option('display.float_format', lambda x: '{:.3f}'.format(x))

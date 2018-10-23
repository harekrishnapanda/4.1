'''
You survey households in your area to find the average rent they are paying. Find the
standard deviation from the following data:
$1550, $1700, $900, $850, $1000, $950.
'''

# 4.1

import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import math
from scipy import stats
np.random.seed(1)


data1 = [1550, 1700, 900, 850, 1000, 950]
print("Variance of data1 = ", np.std(data1))

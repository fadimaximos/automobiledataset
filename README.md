# automobiledataset

# README

## Introduction

This report will include some efforts to infer some data about cars from 1985 Ward's Automotive Yearbook.

## Requirements

### Libraries

You will need to install the `word2number` [module](https://pypi.org/project/word2number/) using the below command<br>
`pip install word2number`

The below are the libraries used
```
import numpy as np
import pandas as pd
import random
import matplotlib.pyplot as plt
import seaborn as sns
from scipy import stats
import statsmodels.api as sm
from statsmodels.stats.outliers_influence import variance_inflation_factor
from patsy import dmatrices
from statsmodels.stats.proportion import proportions_ztest
from word2number import w2n
```

### Files

The .csv file needed is included in the repo.

## Scientific Basis

In this report, we will try to perform a full data analysis procedure.<br>
We will:
1. Discover the data and perform some data wrangling. We might deduce some conclusions from our exploratory data analysis, but this is not our ultimate target.
2. We will perform some simple probability calculations to infer some conclusions.
3. We will use some hypothesis testing to check some hypotheses we might have.
4. We will finally build regression models to tie it all up.

We will assume that the symboling, price and the mileage of the car are our dependant variables that we are trying to link with other variables.

## Licenses

This is an open source project. Please feel free to build on it.

## Contact information

Please contact me at fadi.maximos@live.com for any inquiries.

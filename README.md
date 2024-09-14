# Data Loading
import numpy as np

# Load male and female datasets
male = np.loadtxt('nhanes_adult_male_bmx_2020.csv', delimiter=',')
female = np.loadtxt('nhanes_adult_female_bmx_2020.csv', delimiter=',')

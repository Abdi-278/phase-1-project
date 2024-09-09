# phase-1-project

Overview

the company needs to understand which aircraft models present the lowest risk in terms of safety, reliability, and overall performance. By examining data from the aviation sector, such as accident rates, aircraft maintenance records, and safety trends, your company can make informed decisions about which aircraft models to invest in. The ultimate goal is to ensure the company's new aviation division starts with the safest and most reliable aircraft fleet, minimizing risk while maximizing operational efficiency.


Business Problem

Your company is expanding in to new industries to diversify its portfolio. Specifically, they are interested in purchasing and operating airplanes for commercial and private enterprises, but do not know anything about the potential risks of aircraft. You are charged with determining which aircraft are the lowest risk for the company to start this new business endeavor. You must then translate your findings into actionable insights that the head of the new aviation division can use to help decide which aircraft to purchase.


Questions to consider:
1. What is the safety record of each aircraft model?
2. What are the maintenance and operational costs associated with different aircraft?
3. How each make was involved in accidents?
4. The accident happened across the years?

Description of data

#numpy for high level mathematical functions and working with Arrays import numpy as np #pandas data manipulation and analysis for tablular data import pandas as pd #seaborn and matplotlib for data visualization import seaborn as sns import matplotlib.pyplot as plt %matplotlib inline


loading data

#loading the data
df_original=pd.read_csv('AviationData.csv',encoding='mac_roman')
df_1_original=pd.read_csv('USState_Codes.csv')

cleaning data

cleaned(AviataionData)

Visualizations

![image](https://github.com/user-attachments/assets/34ed2006-97be-4bb6-a9f2-b2d00cd8ca13)

![image](https://github.com/user-attachments/assets/4dec7712-2624-4ef8-8dd4-ff73b160dbc0)


![image](https://github.com/user-attachments/assets/c22eb152-6899-41cc-a286-511bfe906273)

















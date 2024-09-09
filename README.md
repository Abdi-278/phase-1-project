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

Visualizations:

![image](https://github.com/user-attachments/assets/34ed2006-97be-4bb6-a9f2-b2d00cd8ca13)

![image](https://github.com/user-attachments/assets/4dec7712-2624-4ef8-8dd4-ff73b160dbc0)


![image](https://github.com/user-attachments/assets/c22eb152-6899-41cc-a286-511bfe906273)

Conclusion:
> The bottom line for the "success" of a the company purchasing Aircrafts with the lowest risk is going with the aircraft involved with the least accidents
> Variables that may influence the "success" of a Safe  Aircraft:


1. Make
2. Model
3. weather condition
4. Engine type
5. Injury severity


Findings:

The decrease in aviation accidents since 1982 is encouraging, but it's clear that certain states, such as California, Texas, and Florida, still experience significantly higher accident rates. To address this issue, it is imperative to continually enhance safety protocols, regulations, and procedures. Regular reviews and updates of these measures are essential to stay ahead of emerging risks. In high-accident states, there should be a concerted effort to increase surveillance and regulatory enforcement activities to mitigate the risks associated with aviation accidents.
Most accidents happen in good weather conditions. In good weather conditions, pilots may become complacent, assuming there are fewer risks compared to poor weather conditions. This can lead to a lax attitude toward safety protocols and potentially risky behaviors, such as low-level flying, excessive speed, or aerobatics, which increase the likelihood of accidents. To address this issue, it is recommended to promote responsible flying and discourage risky behaviors through training and awareness campaigns. Reinforcing the importance of flying within established safety parameters is crucial to preventing accidents.
. Personal flights are responsible for big portion of aviation accidents. For personal flights, comprehensive education and training programs should be promoted for pilots. Encouraging a safety-first culture within the personal aviation community is essential. Making safety a top priority in all personal flight activities is crucial to reducing accidents. Pilots must be well-prepared and aware of the potential risks associated with personal aviation, regardless of the weather conditions

To further enhance aviation safety, rigorous maintenance and inspection programs should be implemented for specific makes and models that have shown a higher accident rate. Collaboration with aircraft manufacturers is vital to identify any design or manufacturing issues that may contribute to accidents. This proactive approach to maintenance and collaboration can help identify and rectify potential safety hazards before they lead to accidents, thus improving overall aviation safety












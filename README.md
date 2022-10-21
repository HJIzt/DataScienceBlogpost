# DataScienceBlogpost
First project for Udacity nanodegree

This is an analysis of the ["Seattle Airbnb Open Data" dataset](https://www.kaggle.com/datasets/airbnb/seattle) from Kaggle. 

# Questions analyzed
1. Which months have the greatest number of units available?
2. How do prices vary through the year?
3. Do individual listings change price, or does the entry and exit of units cause average prices to change?

# Results summary:
I find that summer months have slightly lower availability, but higher prices than winter months. Prices are roughly hump-shaped, 
with the lowest prices in the beginning of the year, the highest in the summer, and prices falling again in autumn but remaining above the beginning 
of the year. There is evidence that this shift is caused both by individual units changing price over the year, and the entry of differently-priced
units onto the market. My blog post can be found [here](https://medium.com/@h.j.izatt/whens-the-best-time-for-a-vacation-in-seattle-e035f17800e2), 
with questions 1 and 2 answered. 

# Libraries used:
- numpy (as np)
- pandas (as pd)
- matplotlib.pyplot (as plt)
- seaborn (as sns)
- os
- statsmodels.api (as sm)

# Repository Organization
The zipped and unzipped dataset files are kept in the `data` directory. Of these, only `calendar.csv` is used. Analysis is done in `seattle_airbnb_analysis.ipynb`

# Acknowledgements:

Kaggle. June 25, 2018. "Seattle  Airbnb Open Data." Kaggle. https://www.kaggle.com/datasets/airbnb/seattle. Accessed October 13, 2022.
# Nobel_Prize_Analysis

Setup and Context

Introduction
On November 27, 1895, Alfred Nobel signed his last will in Paris. When it was opened after his death, the will caused a lot of controversy, as Nobel had left much of his wealth for the establishment of a prize.

Alfred Nobel dictates that his entire remaining estate should be used to endow “prizes to those who, during the preceding year, have conferred the greatest benefit to humankind”.

Every year the Nobel Prize is given to scientists and scholars in the categories chemistry, literature, physics, physiology or medicine, economics, and peace.


Let's see what patterns we can find in the data of the past Nobel laureates. What can we learn about the Nobel prize and our world more generally?

Upgrade plotly (only Google Colab Notebook)
Google Colab may not be running the latest version of plotly. If you're working in Google Colab, uncomment the line below, run the cell, and restart your notebook server.

learnings:

1. Create a Choropleth to display data on a map.
2. Create bar charts showing different segments of the data with plotly.
3. Create Sunburst charts with plotly.
4. Use Seaborn's .lmplot() and show best-fit lines across multiple categories using the row, hue, and lowess parameters.
5. Understand how a different picture emerges when looking at the same data in different ways (e.g., box plots vs a time series analysis).
6. See the distribution of our data and visualise descriptive statistics with the help of a histogram in Seaborn.



# required libraries
Import Statements

1. import pandas as pd 
2. import numpy as np
3. import plotly.express as px
4. import seaborn as sns
5. import matplotlib.pyplot as plt

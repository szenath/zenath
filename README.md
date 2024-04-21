Stock Market Analysis project
-This small project essentially helps to understand movements of particular stock in
the market.
-This code will provide technical analysis of any given particular stock over a period of
time.
-It helps an individual/business decide whether it is a good decision to invest in a company or not.
-It also helps the business or individual decide when is the best and worst time to invest in.
-Therefore,this code helps investors to decide if they should invest in the business or not,and prevents them from making wrong decisions.


Python modules Used in Stock Price Analysis
-import pandas as pd {To handle data frames in python}
-import csv {To read comma separated file.}
-import matplotlib.pyplot as plt {To Plot graphs}




-This script will basically read trade data from csv file (stored locally) into Pandas data
frame.
-Remove rows having nulls in column “Volume”
-Select sample data to be analysed (by providing start and end dates of data to be
analysed).
-Select sample data to be analysed (by providing start and end dates of data to be
analysed).
-Plot graph on stock price analysis.
-The plotted graph is the combination of volume traded for selected stock and also
trending of open, min and max prices for the selected range of dates.
-From the graph, we can clearly figure out that open price is increasing every day (which
it means stock prices are performing well). Also, low spread between min and max
points clearly indicates product is quite stable in the market as there are no huge gaps
in min and max prices thought out the selected range of dates.

# Walmart Sales Analysis


## Overview and Scope
One of the leading retail stores in the US, Walmart data has been used to obtain an insight of Weekly Sales at forty-five different locations over the years from January,2010 to December,2012. There are several factors that impact the weekly sales of a store in which Store Location, Holiday Week Markdowns, Fuel Price, Consumer Price Index (CPI) and Unemployment Index are taken into account.
Hypothesis Analysis will be used to conclude the impact of above mentioned factors on sales.


### Sale
Walmart's monthly sales are analyzed over three years and the plot is shown below. The plot shows overall similar monthly sales across *45* stores except some outliers.

**monthly sale image**

In order to get an insight for the scope of improvement, semesterly and quarterly sales were analyzed per store. The plots are shown below respectively.
**semester and quarterly sale images**

It was noticed that second semester of 2012 had minimum sale and in that year, forth quarter had drastically low sale.


### Location of the stores
It is interesting to see how different locations change the sales of the stores. A graph was plotted for all the stores against their total sales for two years as shown below.

**image**

Out of all the locations under analysis, *40%* of the stores (18 of 45) have their sales below *60%* of the highest sale obtained by store with store ID *14*. It was interesting to notice that hightest selling store (store ID: 14) also has highest standard deviation from its average weekly sale.


### Holiday markdown week VS Non-Holiday week sale.
To have an insight of how holiday markdown week sales do with respect to non-holiday weeks, a graph is shown below. There are 10 holiday markdown sale weeks (for each location of the store)  and 133 non-holiday weeks (for each locations of the store) for a duration of three years.

It was observed that the average sale of a holiday markdown week is $81,000 more than the average non-holiday week sale. 

### Impact of Unemployment on Sales
In order to test the impact of Unemployment on Sales, Welsch's Hypothesis testing is used. Unemployment Indices varied between 3.88 to 14.31 over the years of interest (2010-2012). <br/> For the testing, below given hypothesis was defined:

**H0: There is no impact of Unemployment on sales** <br />
**H1: There is an impact of Unemployment on sales** <br/>

Rejection threshold for the test is selected as 0.05 and p-value for sale is calculated against all unique Unemployment Indices. <br/> Below is the obtained graph:

**image**

As seen above, there is an impact from Unemployment Index on sales for the range 3.8 to 6.2 and 7.9 to 14.3.<br/> Therefore, **Null hypothesis is rejected**

### Impact of Consumer Price Index (CPI) on Sales
For testing the impact of CPI on sales, Welsch's Hypothesis is used. 

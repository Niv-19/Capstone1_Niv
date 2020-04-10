# Walmart Sales Analysis


## Overview and Scope
One of the leading retail stores in the US, Walmart data has been used to obtain an insight of Weekly Sales at forty-five different locations over the years from January,2010 to December,2012. There are several factors that impact the weekly sales of a store in which Store Location, Holiday Week Markdowns, Fuel Price, Consumer Price Index (CPI) and Unemployment Index are taken into account.
Hypothesis Analysis will be used to conclude the impact of above mentioned factors on sales.

---

### Sale
Walmart's monthly sales are analyzed over three years and the plot is shown below. The plot shows overall similar monthly sales across *45* stores except some outliers.


![Monthly_Sale](WalmartSaleImages/monthly.png)

In order to get an insight for the scope of improvement, semesterly and quarterly sales were analyzed per store. The plots are shown below respectively.<br/>

![Semester_wise_sale](WalmartSaleImages/semester.png)

![Quarterly_sale_2012](WalmartSaleImages/quarterly.png)


**semester and quarterly sale images**

It was noticed that second semester of 2012 had minimum sale and specially forth quarter of 2012 had drastically low sale.<br/>

---

### Location of the stores
It is interesting to see how different locations change the sales of the stores. A graph was plotted for all the stores against their total sales for two years as shown below.<br/>

![Sales_per_location](WalmartSaleImages/location.png)


Out of all the locations under analysis, *40%* of the stores (18 of 45) have their sales below *60%* of the highest sale obtained by store with store ID *14*. It was interesting to notice that hightest selling store (store ID: 14) also has highest standard deviation from its average weekly sale.<br/>

---


### Holiday markdown week VS Non-Holiday week sale.
To have an insight of how holiday markdown week sales do with respect to non-holiday weeks, a graph is shown below. There are 10 holiday markdown sale weeks (for each location of the store)  and 133 non-holiday weeks (for each locations of the store) for a duration of three years.

![Holiday_non_holiday_companisor](WalmartSaleImages/holiday.png)



It was observed that the average sale of a holiday markdown week is $81,000 more than the average non-holiday week sale. <br/>

---

### Impact of Unemployment on Sales
In order to test the impact of Unemployment on Sales, Welch's Hypothesis testing is used. Unemployment Indices varied between 3.88 to 14.31 over the years of interest (2010-2012). <br/> For the testing, below given hypothesis was defined:

**H0: There is no impact of Unemployment on sales** <br />
**H1: There is an impact of Unemployment on sales** <br/>

Rejection threshold for the test is selected as 0.05 and p-value for sale is calculated against all unique Unemployment Indices. <br/> Below is the obtained graph:

![Unemployment_Impact](WalmartSaleImages/unemployment.png)


As seen above, there is an impact from Unemployment Index on sales for the range 3.8 to 6.2 and 7.9 to 14.3.<br/> Therefore, **Null hypothesis is rejected**<br/>

---

### Impact of Consumer Price Index (CPI) on Sales
For testing the impact of CPI on sales, Welch's Hypothesis is used. Below defined is the Null hypothesis and the Alternate Hypothesis: <br/>

**H0: There is no impact of CPI on sales** <br/>
**H1: There is an impact of CPI on sales** <br/>
The rejection threshold for the test is selected as 0.05. Below is the obtained graph for different p-values over the range of CPI.

![CPI_Impact](WalmartSaleImages/CPI.png)


CPI impacts the sales when in range 139 to 142 and 182 to 227. Therefore, Null hypothesis is rejected for these ranges.<br/>

---

### Impact of Fuel Price on Sales
Again, Welch's hypothesis testing is utilized to inspect the impact of different fuel prices. Fuel price ranged between 2.47 to 4.45 and p-value is calculated over all different values of fuel.<br/>
The rejection threshold is selected as 0.05. Below is the defined Null Hypothesis and Alternate hypothese:<br/>
**H0: There is no impact of fuel price on sales.**<br/>
**H1: Fuel price impacts sales.**<br/>

The observed plot is shown below. Obtained p-value is way above than the alpha. Therefore, this test **fails to reject Null Hypothesis.** <br/>

![Fuel_Price](WalmartSaleImages/Fuel.png)


---

## Conclusion
Based on all the impact analysis, it is concluded that:<br/>
> Sales change as per the location of the store.<br/>
> Holiday markdown week sales are highter than non-holiday week sales.<br/>
> There is an impact of Unemployment Index on sales.<br/>
> There is an impact of CPI on sales.<br/>
> There is no impact of fuel price on sales.<br/> 

---

## Suggestions
> Relocate stores which are below 60% of highest sales.<br/>
> Increase Markdown weeks.<br/>
> There is an impact of Unemployment Index on sales, so prices and inventory should be changed accordingly.<br/>
> There is an impact of CPI on sales, markdown weeks should be increased in high CPI times.<br/>
> There is no impact of fuel price. <br/>


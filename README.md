# Baltimore-Morris County, NJ- Income Data
Comparing High and Low Income Levels in Baltimore City and Morris County, NJ

## Background
Baltimore City and Morristown, New Jersey (a suburb located just outside of NYC) have incredibly different economic situations.  In northern New Jersey, the median income is relatively high, and a very low percentage of residents are below the poverty level.  However, in Baltimore City the situation is very different.  Poverty is rampant, and the median income is low.  However, as with any population, there is a significant amount of variance between individual incomes.  Thus, the high income residents of Baltimore and NJ have drastically larger incomes than the low income residents.

While it is easy to explain in numerical terms the differences between Morristown and Baltimore, fully comprehending the data and its implications is a much more difficult task.  This project aims to process high and low income (marked by the 25th and 75th percentile) values between New Jersey and Baltimore and present findings in an easily comprehensible visual.  Using Opportunity Atlas, income data from numerous towns throughout the Morristown and Baltimore area were used to create this graphical representation of income data.

## Business Question 
How do high and low income levels between Baltimore and Morristown, NJ compare?

## Data Question - Open Data
Data source: Opportunity Atlas

- [Morristown](https://github.com/AdamShmanske/Baltimore-Morris-County-NJ-Income-Data/blob/master/Income%20Comparison%20Baltimore%20Data.xls): Downloaded all available open data on income levels in Morristown and surrounding towns.  Separated this data collection into high income raw data and low income raw data from towns for analysis.
- [Baltimore](https://github.com/AdamShmanske/Baltimore-Morris-County-NJ-Income-Data/blob/master/Income%20Comparison%20Baltimore%20Data.xls): Downloaded all available open data on income levels in Morristown and surrounding towns.  Separated this data collection into high income raw data and low income raw data from towns for analysis.  Further separated data by sorting by "Baltimore" to remove any unwanted neighboring towns from the city data.
- High income in this data set is defined by the 75th percentile of income.
- Low income in this data set is defined by the 25th percentile of income.

## Data Question and Graphical Answer

### How much do NJ and Baltimore high and low income values differ?

### Comparison between Low and High Income in NJ and Baltimore
It is clear from both of the graphs posted below that NJ generally has a large advantage over Baltimore in both high and low incomes.  Aside from a few noticeable outliers from Baltimore, nearly all NJ data points were greater than all Baltimore data points.  This is expected, as the median income for NJ is greater than that of Baltimore.  There were less NJ towns as data points to analyze, but the general trend is still very clear that NJ has a greater income in almost all cases (high and low) than in Baltimore.

![alt text](https://github.com/AdamShmanske/Baltimore-Morris-County-NJ-Income-Data/blob/master/Low%20Income%20Comparison.png)

![alt text](https://github.com/AdamShmanske/Baltimore-Morris-County-NJ-Income-Data/blob/master/High%20Income%20Comparison.png)

### How large is the income discrepancy between NJ and Baltimore?

### Comparison between Low Income NJ and High Income Baltimore
The graph below is the most clear representation of how drastic this income discrepancy truly is between NJ and Baltimore.  In this graph, 39 low income NJ datapoints are displayed alongside 39 Baltimore high income datapoints.  The previous graphs above clearly showed that NJ largely has an advantage over Baltimore in terms of income when holding income quartile (high vs low) constant.  However, this graph shows that even when comparing the lower quartile of NJ datapoints and the upper quartile of Baltimore datapoints, very few Baltimore values are greater than NJ values.  This is surprising and shows the true wealth difference between these communities.  The bottom 25% of NJ datapoints are mostly still greater than the top 75% of Baltimore datapoints, which is inidicative of a large wealth gap between these two areas.

![alt text](https://github.com/AdamShmanske/Baltimore-Morris-County-NJ-Income-Data/blob/master/Low%20NJ%20High%20Baltimore%20Graph.png)

## Business Answer
When comparing
- High incomes in NJ and Baltimore- NJ has a much greater overall value.
- Low incomes in NJ and Baltimore- NJ has a much greater overall value.
- Low incomes in NJ and high incomes in Baltimore- On average, NJ still has a greater overall value.

These results can be used to truly illustrate the wealth differences between even the lowest quartile of NJ residents and the highest quartile of Baltimore residents.  This graphically represented wealth difference can be used for a wide range of purposes.  An example of how this type of data analysis could be useful would be in the decision making for government agencies. When deciding how to allocate government funds for social programs, this representation that even high earning Baltimore residents are generally worse off than low earning NJ residents is important information to utilize.

# Python Analysis

## Python Data Cleaning


## Python Visualizations
### 25th Percentile Baltimore Boxplot
![alt text](https://github.com/AdamShmanske/Baltimore-Morris-County-NJ-Income-Data/blob/master/25th%20Percentile%20Incomes%20Baltimore.png)
### 75th Percentile Baltimore Boxplot
![alt text](https://github.com/AdamShmanske/Baltimore-Morris-County-NJ-Income-Data/blob/master/75th%20Percentile%20Incomes%20Baltimore.png)
### 25th Percentile NJ Boxplot
![alt text](https://github.com/AdamShmanske/Baltimore-Morris-County-NJ-Income-Data/blob/master/25th%20Percentile%20Incomes%20NJ.png)
### 75th Percentile NJ Boxplot
![alt text](https://github.com/AdamShmanske/Baltimore-Morris-County-NJ-Income-Data/blob/master/75th%20Percentile%20Incomes%20NJ.png)

## Excel Directions
- [Excel Directions](https://github.com/AdamShmanske/Baltimore-Morris-County-NJ-Income-Data/blob/master/Income%20Comparison%20Baltimore%20Data%20Excel%20Instructions.xls) for this project are embedded within this link.  This provides a step-by-step guide on the data analysis performed in this project.

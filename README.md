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

## Excel Directions
- [Excel Directions](https://github.com/AdamShmanske/Baltimore-Morris-County-NJ-Income-Data/blob/master/Income%20Comparison%20Baltimore%20Data%20Excel%20Instructions.xls) for this project are embedded within this link.  This provides a step-by-step guide on the data analysis performed in this project.

# Python Analysis
Using Python, further data analysis was performed on the 4 data sources: NJ 25th Percentile Income, NJ 75th Percentile Income, Baltimore 25th Percentile Income, and Baltimore 75th Percentile Income. The initial data visualization created using excel was not sufficient enough to compare the overall trends of the data, as these visualizations compared all of the neighborhoods on the same plot.  With Python, a may useful boxplot representation of the data was created in order to compare the general trends of the data, and eliminate the confusion of representing individual neighborhood data.  These graphs allow us to compare the range, quartiles, and any outliers for our 4 data sources on the same scale of $15,000 to $80,000.  Comparing any of these graphs side by side creates allows the data to be easily understood and analyzed with just a quick glance.

## Python Visualizations
### 25th Percentile Baltimore Boxplot
![alt text](https://github.com/AdamShmanske/Baltimore-Morris-County-NJ-Income-Data/blob/master/25th%20Percentile%20Incomes%20Baltimore.png)
For the 25th Percentile of Incomes from Baltimore neighborhoods, the minimum average income was $16,364.  The median income of these neighborhoods was $23,612, and the upper fence was $36,568.  There were numerous outliers in this dataset, and the maximum income was $53,687.
### 75th Percentile Baltimore Boxplot
![alt text](https://github.com/AdamShmanske/Baltimore-Morris-County-NJ-Income-Data/blob/master/75th%20Percentile%20Incomes%20Baltimore.png)
For the 75th Percentile of Incomes from Baltimore neighborhoods, the minimum average income was $17,305.  The median income of these neighborhoods was $38,520, far greater than the median income of the 25th percentile dataset.  The maximum income was $72,321, and there were no outliers in this data set
### 25th Percentile NJ Boxplot
![alt text](https://github.com/AdamShmanske/Baltimore-Morris-County-NJ-Income-Data/blob/master/25th%20Percentile%20Incomes%20NJ.png)
For the 25th Percentile of Incomes from NJ neighborhoods, the minimum average income was $34,487.  The median income of these neighborhoods was $46,582, and the upper income fence was $61,023.  There was a singular outlier in this dataset, at $64,276.

### 75th Percentile NJ Boxplot
![alt text](https://github.com/AdamShmanske/Baltimore-Morris-County-NJ-Income-Data/blob/master/75th%20Percentile%20Incomes%20NJ.png)
For the 75th Percentile of Incomes from NJ neighborhoods, there was one outlier for the minimum average income at $51,344.  The lower fence was $57,946, and the median was $64,604.  The maximum of the 75th Percentile Incomes in NJ was $71,655.


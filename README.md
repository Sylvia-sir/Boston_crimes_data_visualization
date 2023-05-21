# Boston_crimes_data_visualization
How can visualization help us when it comes to a real and critical case like crimes!? Is it possible to track and find pattern and detect a crime before it happens? 
In this project we're using the visualization tools to find patterns.

Python and it's libraies pandas and numpy are used for organizing the data set and for calculations. Different kinds of plots are used for convenience in analysis and for visualization. For this reason plotly and follium are used.

The data is provided in csv format. It is imported and read by using pandas.

The Records begin in June 22, 2015 and continue to October 3, 2018. So, there are missing months in 2015 and 2018.
Column names and missing data counts were checked.

The data has 6 colums with missing values. For shooting colums missing values are replaced with N to indicate there is no shooting. For missing location informations in Lat and Long column colums missing values are replaced with -1. These location values neglected during analysis.

From the figure 'Distributions of Total Number of Crimes Between 2015-2018' following inferences can be made;

Yearly:
The is a drastic increase in crime rate between 2015-2016. It can be seen that in 2017 crime count is slightly higher than 2016. Most likely the reason is missing months in 2015 and 2018.

Monthly:
The crime count varies thorugh year between 2015-2018.In spring and summer periods crime count is relatively high compare to winter sesion. 7th,8th and 9th months (July, August and September) are the top three months of the year for crime counts.

Daily:
There is also a variation in the crime numbers during a week. Crime numbers see the bottom in the weekends where they have the highest value in Friday. Except Friday, there is no significant difference in the crime number during the weekdays.

Hourly:
'Number of crimes per hour' graph shows hourly changes in crime rate. Crime number changes a lot throughout the day.It has the highest values between 10 am - 8 pm and lowest values between 1 am - 7 am.

District
There is no homogenous distribution of crime between districts. The first five district has almost twofold crimes compare to rest of the districts.

Street
Change in the crime number between streets are much more higher compare districts. Most of the streets the crime rate is under 1000 for a year. The Washingthon street has the hisghest crime number.

After seeing the general trend in crimes, now different crime types are also considered. To categorize crimes different offense codes and groups are used in the data frame. The most general one between these categories is the UCR Parts. Now take a look in the crime numbers in UCR Parts to see if they follow the same trend with the general one.

It can be seen from the figures that all the UCR parts follow the general trend but minor changes occur in Part One crimes. Crimes cathegorized under "Other" doesn't change much between 2015-2018. When compare to other UCR parts, Part One type crime rates vary less monthly and weekly. No matter when or where Part three is the most committed crime part among all.

There is a significant difference between Top 25 crimes and least committed 25 crimes. From the graph 'Least Committed 25 Crimes in Boston' we can see that some crimes categories has value lower than 100. To see the over all situation crimes with lower occurancey than 1000 is printed.

Conclusion

How has crime changed over the years?

Crime number is the hghest in 2017 and lowest in 2015. There is a significant decrese in the crime numbers in 2018. However, the records begin in June 22, 2015 and continue to October 3, 2018. So there are 6 missing months in 2015 and 3 months for 2018. So, the significant decrease in this year is most probably cause by these missing values.

Is it possible to predict where or when a crime will be committed?
It is possible to next crime occur near the city center where the districs with higher crime rates are located. Also, next crime might occur in the summer months, during day time because most of the crimes happend at that times. So, if we assume that next crimes follow the same pattern with the ones from 2015-2018, we can preapere a list for where and where will next crime committed.

### dstarobin - plot review

![Image of Citibike chart](https://dl.dropboxusercontent.com/u/58178372/citybike_plot_DS.jpg)

##### Clarity
Overall very clear for amount of information displayed, but a little hard to interpret time of ride metric

##### Esthetic
Perfectly functional, only thing is a couple of the dots are hard to tell between lowest and middle average time bucket

##### Honesty
Very honest, only slight potential issue in "average time" dots: does the analysis exclude rides under 10 mintues, 13-14 minutes, 18 minutes, and over 22 minutes or were there simply no rides of those lengths?

##### Suggestions
+ something different with non-subscriber rides, ideas either
  * remove completely: it clutters up the graph and doesn't add new information (could add a little annotation that there are *some* January rides but ever day is under X, or something like that)
  * shade region between subscribers and total, then add a legend off to the side which includes all elements instead of in place labels
+ put average time travel on a 2nd y-axis to more easily compare between months and allow for continuous scale instead of bucketed values - for example red circles for July and purple circles for January
+ *maybe* title could reflect what you want viewer to take away from the chart? For example if purpose is to identify outliers (via the cool little arrow callouts) then potentially could be something like "visual outlier analysis of the... (rest of title)"

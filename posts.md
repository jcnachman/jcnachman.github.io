```
---
Analyzing NYC's MTA Turnstie Data for Optimizing Placement of Street Teams
---
```

In week 1 at Metis, we were tasked with helping a fictional non-for-profit company, WomenTechWomenYes (WTWY), with analyzing NYC's MTA data to optimize the placement of their street teams.

###MTAcular Group:
Eric Bassett
Erik Anderson
Eli T. Drumm
Joanna Nachman

###The Premise:

WTWY hosts an annual gala at the beginning of each summer and they need attendees.

By optimizing their street team work, they can gather the most emails. 

Those who sign up are sent free tickets to the gala.

In turn, his will increase the participation of women in tech and simultaneously build awareness and reach at WTWY.


In order to do this, we analyzed individual turnstile data from NYC subway stations to discern the busiest stations across the city and track their daily patterns.


###Our Methodology:

We used data from the MTA turnstile data retrieved from the MTA developer site here:

[NYC MTA Turnstile Data](http://web.mta.info/developers/turnstile.html)

We used Exploratory Data Analysis as our approach to analyze these data sets.

We employed Python and Pandas as our data analysis tools and used Matplotlib to publish our figures. 

We downloaded and cleaned the MTA data sets from March, April, May of 2018 & 2019.

We then grouped and sorted our data by certain columns, like entries, date, time, etc.

The columns “CA", "UNIT", "SCP", "STATION" were keys to the individual turnstiles.

We aggregateed the MTA data by station to calculate the busiest stations per day.


###Results:

Ridership across weekdays was similarly comparable, with Mondays being slightly less.

Ridership on weekends is between roughly 40 and 60 percent that of weekdays.

Table Pic here:
![Image test]({{ site.url }}/images/AlanLeeShireGandalf.JPG)


“INS” represents average entries per day across all stations.
“OUTS” represent average exits per day across all stations

Average Daily MTA Entries pic here:


This lovely bar plot shows the average daily MTA entries. 

As you can see, Mondays are slightly less busy than the rest of the week days, with the majority of the hump taking place Tuesday, Wednesday, and Thursday.

And then we see a significant drop on the weekends. This makes sense as there should be less commuters on Saturday and Sunday.


###Busiest Stations on Weekdays:

Table pic here

All of our busiest stations are located in Manhattan, with the majority in Midwtown.

Midtown:
Time Square, Broadway, Madison Square Garden, Empire State Building

34th St Penn Station:
Pennsylvania station, which is across the street, is the busiest railroad station in the country. 


###MTA Mean Across Weekends:

Bar chart here

In the case that WTWY is only able to send out their street teams on weekends, we’ve conveniently included this bar chart, which shows the average busiest MTA stations across weekends.

The ordering of the stations is similar to those we saw during weekends as well


###Conclusions:

Table pic here

We recommend placing street teams at these top 10 busiest stations Tuesday, Wednesday, Thursday, & Friday.

Intuitively, we think the best times would be during peak hours, i.e. rush hour.

###Next Steps to Continue Helping WTWY:

Analyze Additional Data:

	- NYC Census Data:
		- Higher income residents
		- Higher concentrations of women (ideally ages 25 – 40) 

	- NYC business data for higher concentrations of tech companies

Marketing beyond subway station outreach:

	- Social media advertising and email marketing


###Reference:

Our github repository for the project can be found here:


[MTAcular Github](https://github.com/ekand/mtacular)



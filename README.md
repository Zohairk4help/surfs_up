# ***Surfs_up -- module 9 with Advanced Data Storage and Retrieval***
--
## Overview of the analysis: 
In this Module, I learned and applied the knowledge on SQLite, SQLAlchemy, and Flask. I learned that SQLite is a near equivalent to PostgreSQL. The only difference is that it is a local database storage file. In addition to that, SQLAlchemy, which is a type of pgAdmin, but it lacks server and it is local, is also used to when creating Flask app. Flask is the other area that this module focused on. I came to know that the app is created because of some audience who just want to see our results in webpages. Then using these new knowledges, I performed my statistical analysis on the data provided. 

The following is an example of the flask-app created URL that has welcome-webpage and its trailing routes: <img src="png-modules\welcomeroute.PNG" width="20" height="20"> -> <img src="png-modules\preciproute.PNG" width="20" height="20"> -> 
<img src="png-modules\stationsroute.PNG" width="20" height="20"> -> <img src="png-modules\tempoutput.PNG" width="20" height="20"> -> <img src="png-modules\stationsroute.PNG" width="20" height="20"> -> <img src="png-modules\tobs'output.PNG" width="20" height="20">

. 

The Module challenge is focused on finding the statistical analysis and results on the temperature data for June and December for the years 2010-2017. This was done because W-Avy is keen to know the sustainibility of his surf and ice cream shop business year-round. 

--

## Results: 
* Deliverable 1: The 2010-2017 June-temp's data:
1. The max temperature recorded:  85°C on 2010/06/20
2. The min temperature recorded: 64°C on 2016/06/01
3. The average and standard deviation of the years' temp: 74.72 ± 3.24 °C. 

<img src="png-modules\statsdel1.PNG" width="70" height="70">| <img src="png-modules\deliv1juneplot.PNG" width="70" height="70">
---
* Deliverable 2: The 2010-2016 Dec -temp's data:
1. The max temperature recorded:  83°C on 2013/12/08
2. The min temperature recorded: 56°C on 2014/12/31
3. The average and standard deviation of the years' temp: 71.04 ± 3.75 °C. 

<img src="png-modules\Dec-deliv2plot.PNG" width="70" height="70">| <img src="png-modules\statsdel2.PNG" width="70" height="70">
* Key difference between the two months (June and Dec): coldest month in Ohua is Dec though ; however, the temperature in Ohua is constant all year. 

## Summary: 
After statiscally analysing the data, it is concluded that W-Avy has taken a wise decision to open and run his surf-and-icecream business in Ohua. It is because the temperature of that place is constant throughout the span of years (2010 to 2017) of the months (June and December).

After calculations and querrying the data, I think it is better to have the conclusion of two more random months for 2010-2017 years. With this, our results for the data will have more confidence. Secondly, we need to have a querry that puts x and y's labels in the plots. 


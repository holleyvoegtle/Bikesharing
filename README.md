# Bikesharing

## Overview/Background
During a recent visit to New York City, two friends rented bikes and got to see the city in a unique way. These bikes were through a ride sharing company and the friends felt that the concept could be used in their hometown of Des Moines, Iowa. In order to gain investor interest, data from the NYC was obtained to draw comparisons and information. Once the data was analyzed, it needed to be presented in visibly pleasing manner. This was accomplished through the use of Tableau. 


## Results
The entire module with worksheets and stories can be seen here. The final challenge results are also included in this link. (https://public.tableau.com/profile/holley2560#!/vizhome/CitiBikemodule14/TopEndingLocations?publish=yes)

The first thing that was needed was to use Python and the pandas library in Jupyter notebook to change the trip duration time to a Datetime Format. This information was used for the first graph. As illustrated in the graph, the most rides were mostly an hour long and in the mornings. 
![](https://github.com/holleyvoegtle/Bikesharing/blob/main/Analysis%20graphs/Checkout%20time%20users.png)



The second graph is checkout times by gender. The same trend as we saw with the first graph is illustrated with males and females, with less numbers but similar trend. Trips are about an hour with morning times being more popular. 
![](https://github.com/holleyvoegtle/Bikesharing/blob/main/Analysis%20graphs/Checkout%20times%20by%20Gender.png)

The third graph is a heat map which illustrates the most popular trips according to which day of the week. Thursday seems to be the most amount of trips with an increase in the morning and in the evening. These times seem to correspond with rush hour.
![](https://github.com/holleyvoegtle/Bikesharing/blob/main/Analysis%20graphs/Trips%20by%20Weekday.png)

The fourth graph takes the previous information and splits it into gender. This is also a heat map. The same trend is seen as previously but this time more men are using the bikes. 
![](https://github.com/holleyvoegtle/Bikesharing/blob/main/Analysis%20graphs/Trips%20by%20Gender.png)

The fifth graph the was created was comparing genders, days of the week and if the user is a one time customer or an annual subscriber. It is clearly seen that the Males, who are subscribers, use the bikes the most on Thursday and Fridays. 
![](https://github.com/holleyvoegtle/Bikesharing/blob/main/Analysis%20graphs/User%20Trips%20by%20Gender%20by%20Weekday.png)

Further information that was included in the Tableau story (NYC Citibike Analysis), was the amount of users in August and what time of the time was most popular. This graph backed up the previous claim of the bikes being used around 5-6pm followed by the next popular time of around 8am. 
![](https://github.com/holleyvoegtle/Bikesharing/blob/main/Analysis%20graphs/August%20Peak%20Hours.png)

Finally, the last graphs that were included in the analysis with the top location for starting and ending locations of the bikes. Interestingly enough, these locations seem to be very similar and are concentrated in the mid to lower west side of Manhattan. 


## Summary/conclusions

Overall, studying the data that came out of New your City bike sharing can help guide the friends in convincing investors to buy into the big sharing program in Des Moines. Although the population is quite smaller than NYC, some important take-aways can help. One of the conclusions is that bikes are mostly used by men around rush hour. Also, pickup and drop-off locations are very similar which can either illustrate that riders take the bikes close to home or close to work. A recommendation for Des Moines would be to run an analysis of where people work and if they live close to their jobs. If there is an abundance of bike to use, people will more likely use them so accessibility would be a big factor. 

If more information was needed for the investors, I would suggest looking into other cities using the bike sharing programs and if there is data available. Are there similar trends? Are men more likely to use the bikes in these places too? What is the age range of usage? Pin-pointing exact locations could also help with setting up beta testing for Des Moines. This way, you can see if there are trends similar to NYC and other places. Maybe even around university areas. 

More information that I personally would like to see is getting more data over a longer period of time. Are the summer months the peak time? Are bikes still used in the winter or does weather play a part in bike usage? How often do the bikes need repair and if they are repaired more than a few times, are they replaced? What about theft? When and where are bikes mostly likely to be stolen? 

Overall this exercise is a comprehensive analysis of bike sharing and a good practice for data visualization techniques.

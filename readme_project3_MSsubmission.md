# (Dataset Exploration Title)
## by (your name here)


## Dataset

> The data set consist of bike trip data from the Ford Go bike transportation system/network. It consists of the distance and duration of bike trip indicating lat, long of starting and arrvinng locations as well as the gender and age of the bike rider and whether or not he/she is a customer or not.

> A total of 183,412 data entries are provided inthe data frame; most of which have 16 features reflecting specifics about bike trips. Trip duration is the only quantitative variables. User age is a discreet variable. Time variables are continuous variables. Most of the remaining variables are categorical. 

> After cleaning, a total of 174,952 data entries. 

> Three features were generated: trip time differences, bikers' age in years, and trip duration in hours. 


## Summary of Findings

#### The main findings of the data set are:
> The distribution of user_age is a log-normal/right-skewed distribtion. the distribution shows few outliers of bikers with age > 80 years. This can be either be actual outliers or wrong entries into the data set.  Also, unreasonable ages reaching 142 years are reported. Also, there are bikers with gender reported as others; these were not included in any statistics. 

> The majority of the bikers are 20-60 years old with the mean age of bikers is 35 years. the standard deviation of skewed distribution is 10 yaers. 

> The trip duration follows a log normal distribution. the mean trip duration is 0.1955 hours or ~ 11.7 minutes. Few trips reached up to 1.5 horus. 
  
> 23.3% of riders are females while 74.6% are males. Mean age of bikers per gender is more or less the same, 34.2 and 35.5 years, respectively for female and males.  

> Average trip duration done by female is slightly longer than males. 

> 90% of the bike users are subscribers that use the bikes for regular trips. The mean trip duration of subscribers is 0.17 horus. 

> ~ 10% of the users are customers that might either be tourists and/or people who need bike rides sporadically. The mean trip duration of customers is 0.36 hr (more than double that of regular users and subscriber).

> Females constitute 27.9% and 22.7% of the customer and subscriber bike users, respectively. 

> Males constitute 69.4% and 75.1% of the customer and subscriber bike users, respectively. 

> Mean age of user types is more or less the same, 34.6 and 35.3 years, respectively for customers and subscribers.

> The most popular bike trips and active stations leave from Very St at 4th st and arrives at the Ferry Buildg. 

> We have no map inforamtion to analyze trip distances (even with having latitudes and longitudes of stations.)


## Key Insights for Presentation

> 23.3% of riders are females while 74.6% are males. Mean age of bikers per gender is more or less the same, 34.2 and 35.5 years, respectively for female and males.  

> Bikes are used for commute and short trips in general with mean trip duration ~12 minutes. > Average trip duration done by female is slightly longer than males. 

> > We have no map inforamtion to analyze trip distances (even with having latitudes and longitudes of stations.). Trip distances are impportant to recommend denser bike stations, more bikes/stations, and/or maintenance schedules to attract more cutomers with all the advantages of doing so (more exercise, greener activity, etc.)
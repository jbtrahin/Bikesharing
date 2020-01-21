# Bikesharing
Create worksheets, dashboards, and stories from New York City bike-sharing data using Tableau.

## Module Overview
In this module, you’ll work with data visualization software called Tableau to present a business proposal for a bike-sharing company. First, you’ll learn how to import, style, and portray data accurately. Then, you’ll create worksheets, dashboards, and stories to visualize key data from a New York Citi Bike dataset.

## Project Overview
In this challenge, you will put together your final presentation and analysis for investors. You'll select the questions you want to answer, conduct independent research, craft your story in Tableau, and then create your written analysis.

The goals for this challenge are to:
1. Display data professionally and accurately.
2. Professionally style a Tableau story.
3. Utilize previously created Tableau worksheets to create a new story.
4. Create a Tableau story based on starting a bike-sharing company in Des Moines.

## Resources
- Software: Visual Studio Code 1.39.0, Tableau Desktop 2019.4 
- Data Sources:
  1. CitiBike Dataset (August 2019): https://s3.amazonaws.com/tripdata/201809-citibike-tripdata.csv.zip
  2. Census Data: https://www.census.gov/quickfacts/fact/table/newyorkcitynewyork,desmoinescityiowa/PST045219
  3. City Facts: https://github.com/jbtrahin/Bikesharing/blob/master/city_facts.csv

## App Preview
You'll find the final visualization of our Tableau Story here:[Des Moines Bike-Sharing Analysis](https://public.tableau.com/profile/jb2456#!/vizhome/DESMOINESABIKE-SHARINGSUCCESSSTORY/DesMoinesCitiBike?publish=yes)

## Analysis

### Summary
The goal is to convince investors that a bike-sharing program in Des Moines is a solid business proposal.

Using New York City (NYC) as our baseline, we put together a few different analysis in order to make useful recommendations. Our work is broken down in 5 dashboards:

1. City Facts: we used census data to illustrate key differences between New York City and Des Moines.
2. Riders Metrics: we used Citi Bike dataset to surface riders' trends in NYC.
3. Usertype Metrics: we used Citi Bike dataset to compare behaviors between subscribers and one-off customers.
4. Age and Gender Metrics: we used Citi Bike dataset to compare behaviors between riders of different age range and gender.
5. Stations Metrics: we used Citi Bike dataset to map the most used start and end stations.
6. Maintenance Metrics: we used Citi Bike dataset to provide insights on bike usage intensity and potential need for maintenance.

We assembled all learnings to provide a series of recommendations in the final tab.

### Walking through the Tableau Story dashboards

1. **City Facts Dashboard learnings:**
* NYC's population is significantly larger than Des Moines.
* It takes twice as much time to commute in NYC.
* Income per capita is 38% higher in NYC.
* We observed that Des Moines' population is slightly younger  than NYC.
* We observed no significant difference in gender breakdown.

2. **Rider Metrics Dashboard learnings:**
* We observe that most days are in the same number of trips' range. We notice some outliers with lower number. These days map to an episode of rain during commuting hours, which would prompt users to avoid biking.
* The majority of bike rides don't exceed 20 minutes. 
* We observe 2 usage peaks, in the morning and in the late afternoon. This would indicate that bikes are being used to commute.

3. **Usertype Metrics Dashboard learnings:**
* We observe that the majority of riders are subscribers.
* Customers' average ride duration is twice as long as subscribers which leads to believe that it include leisure rides.
* Trip duration is consistent for subscribers throughout the day which indicates the most subscribers have the same transportation pattern day-to-day. We observe an increase in trip duration for customers from late morning to late afternoon which coincide with our leisure ride assumption.
* Subscribers are mostly millenials.

3. **Age and Gender Metrics Dashboard learnings:**
* Riders from 25-34 years old range have the most trips taken followed by the 45-54 years old range. We notice that the 45-54 years old range has an average trip duration of almost 25 minutes, 5 more minutes than the 25-34 years old range for the same average distance.
* The largest majority of rides is taken by Male that are subscribers.

4. **Stations Metrics Dashboard learnings:**
* The most used start and end stations are close to busy neighborhoods where people go to work, as well as where tourist attractions are concentrated. 

5. **Maintenance Metrics Dashboard learnings:**
* Some bikes have up to 2.8x the average mileage of all bikes, which indicates that they might be up for maintenance or should be replaced. Bikes with 0 miles in August should also be looked at as they might be in need of maintenance. 

### List of Observations:
1. The population of Des Moines is significantly smaller than New York City, which means less volume of riders overall.

2. We observe that Des Moines commute time coincide with the average trip duration in NYC, which leads us to think that promoting biking as an additional commute option could work (i.e. Public transportation in Des Moines is not optimal).

3. Getting riders to become monthly subsribers is huge factor of success in NYC as it provides consistent revenue and encourages users to use the service. Des Moines should go the same route.

4. Des Moines population is slightly younger than NYC and we know that NYC riders tend to be amongst that age range. It's a good sign for business as it might be easier to attract riders.

5. We learned from analyzing NYC data that popular stations are close to popular businesses and touristy areas. Des Moines should position its strategy with the same amgle to maximize utilization.

6. We learned from the maintenance data that bikes can run well all the way up to 500 miles and more. Des Moines is 3x smaller than NYC when we look at square miles. The robustmess and reliability of the bikes should help keep maintenance costs low.


### Further Analysis
To take our analysis further, it would interesting to get more details on each riders in New York City to determine which social/professional category they fall into. That would help us map the Des Moines rider potential more precisely. We would also want to look at weather patterns to identify and predict the impact of rain on bike utilization.

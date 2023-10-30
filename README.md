# Final-Project-Tableau

## Project/Goals
In this Project I will explore the data fom AirBnB New york in tableau to see if we can gain any insights into the market.   I used the  dataset available here: (https://docs.google.com/spreadsheets/d/1BJWyZpZrrRUla_EQ6Pnusy0KH31UMGf2/edit?usp=sharing&ouid=108445376648788204707&rtpof=true&sd=true)

The tableau sheets and dashboard can be viewed here and is much nicer than the pdf:
https://public.tableau.com/app/profile/david.ormsby5889/viz/Tableau_Project_16985236841750/Dashboard1?publish=yes

## Process
### Exploring
While exploring the data I came up with some questions I wanted so see if I could answer.
1. Do reviews affect what price you can charge for your rental
2. What is the supply and demand like in the different neighborhoods
3. If i want to airBnB my apartment, what price should I list?

I also saw that we are unfortunately missing any data on the time and amount of bookings made.  We have data of when each host joined airbnb but we don't have the same info for specific properties.

### Analyzing
- A scatter plot of review scores and price shows that that there is a slight correlation, but a box and whisker plot shows that the review scores are very positively skewed which could be making our price/review correlation hard to see.  In addition I cant be sure if this is causation or just correlation. 

- The majority of listings are in Manhattan and Brooklyn, and of those listings, about 2/3 are for entire homes and 1/3 for are for private rooms.

- A graph of how many hosts joined and when shows an increase every year with no signs of slowing down.

## Results
1. Inconclusive - The review score does seem slightly correlated to price but more info would be needed on whether there is causation or just correlation.  Higher priced units being better quality could lead to better reviews, or hosts could be charging more becuase they a higher review score
 
2. The majority of listings are in Manhattan and Brooklyn, but they also have the highest average prices, which indicates demand is strong too.  Although we dont have any info on bookings, we can probably say that those are the most popular areas for people to stay.

3. Using the dashboard, someone can inspect details of all listings in their zip code, as well as the trend line for new hosts joining and the distribution of review scores.  They can then use this info to set a competitive market price for their rental.

## Challenges 
The data set was not super detailed, and alot of the columns were not very useful, such as property type or unique host_id.  In addition, the only time column was host_since which tells us a little, but cant be used to track bookings over time for example. We also cannot see anything about bookings, so the best we can do is use the number of reviews to estimate the popularity of each property.

## Future Goals
- If no time series data is available then I would see if i could create my own by web scraping over a month or two.  It would also be useful to be able to see how many bookings get made and where, because this is not in the data either.
- Because the review scores are so positively skewed, maybe we could take the log of it or transform it in some way so that it can be a better predictor.  
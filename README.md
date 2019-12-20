# 

This project used the Yelp API to find gas stations and liquor stores locations within the STL metro area and compared their locations to STLPD crime database (https://www.slmpd.org/crime_stats.shtml). We were looking to see if the number of liquor stores in or around a zip code had a correlational relationship with crimes commited within a zip code.

We found the lat/long of the center of each zip code and made a 5000m radius search for all liquor stores.  We then reviewed the number of crimes in the zip code and looked for any correlational relationship.

We expected to see a generally upward trend of more liquor stores close to a zip code resulting in more crime reported.  Using filtered data (to remove the outlier zip codes) we actually found a slightly negative relationship of -0.135, disproving our hypothesis of more liquor stores within or near a zip code would result in higher reported crime rates.  We also found that as a population within a zip code increases, the overall reported crimes also reduced (-0.48) using all of the data.  When filtered, population increases shows an increase in reported crimes (0.10).

Due to the abnormally high reported crimes in zip code 63101, we omitted its data in our filtered dataset.

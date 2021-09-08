# Project-2

Background:
Beer is one of the oldest drinks humans have produced. The first chemically confirmed barley beer dates back to the 5th millennium BC in Iran, and was recorded in the written history of ancient Egypt and Mesopotamia and spread throughout the world.
The word beer comes from old Germanic languages, and is with variations used in continental Germanic languages, bier in German and Dutch, but not in Nordic languages. The word was imported into the British Isles by tribes such as the Saxons. It is disputed where the word originally comes from.

Potential Questions:
	Which type/style of beer is most favored around the world and which have the top ratings?
	Which beer brand/style have the good quality (taste reviews) irrespective of the popularity of beer as number of reviews?
	Does the aroma of the beer is also proportionally related to its higher ratings?
	What is the overall list of Best quality beer to be selected?

# Purpose of Project

The purpose of this project is to analyze the data from various types of beers sold to study them based on characteristics such as taste, aroma, appearance, strength, and palate as well as their overall rating. A sample set of 1,048,575 data points, which is contained in the file beer_reviews.csv, was cleaned up and analyzed. In the end, the top five highest-ranking beer styles were selected. 

# Data Source
This is the dataset originally has disccused in the talk " How to hire and test for data skills: A one-size-fits-all interview kit" from https://conferences.oreilly.com/strata/strata-ny-2017/public/schedule/detail/59542

However, we have gotten the data set from Kaggle at https://www.kaggle.com/rdoume/beerreviews

# Kaggle Dataset Beer Review.ipynb

The goals of this jupyter notebook file are as follows:
Selecting the top-rated beers from around the world.
Selecting the highest quality beers, irrespective of popularity and number of reviews, based on taste ratings.
Analyzing the strength of the correlation between beer aroma and overall ratings.
Selecting the top ten recommended beers.

These questions are further explored in Untitled.ipynb. 

# Untitled.ipynb

In this file, first, the file beer_reviews.csv is called and grouped by the brewery. The code then looks for the strongest beer, as classified by its alcohol by volume, or abv%. From the data, it was found that the strongest beer was from the brewery Schorschbräu, which has an abv% of 57.7%, has an id of 73368. 

Next, the code looks for the top-ranked beer types based on the overall review as well as the beer’s aroma, appearance, palate, taste, and abv%. The results show that the top-ranked beer ids, which are 55451, 75956, and 48325, have a ranking of 5.0 in all the abovementioned categories. The beer with the id of 55451 has an abv% of 13.0%, the beer with the id of 75956 has an abv% of 11.0%, and the beer with the id of 48325 has an abv% of 10.5%. 

The code then evaluates how characteristics other than abv% have the most impact on the beer’s overall ranking. This was done by evaluating the correlation between the overall ranking with the value given for the beers’ characteristics. This information is both communicated via table and via heatmap. From this information, it is found that the overall review most strongly correlates with the ranking of taste (correlation = 0.789816), followed by that of the palate (correlation = 0.701914), aroma (correlation = 0.616013), and appearance (correlation = 0.501732).

Lastly, the five most popular beer styles were evaluated by grouping by the data frame by beer style and taking the mean of the aroma and appearance as well as the number of available reviews and maximum value in each category. This data is then organized by the number of ratings for aroma and appearance followed by average value and maximum value for both categories. In doing so, it was found that the most popular beer styles were, in descending order, American IPA, American Double / Imperial IPA, American Pale Ale (APA), Russian Imperial Stout, and American Double / Imperial Stout. 

# Conclusion

# Link






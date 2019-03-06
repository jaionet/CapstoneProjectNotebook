# Week 4: 
# Capstone Project - The Battle of Neighborhoods Project:

## Title:  Comparing Neighborhoods in LA to SF an NY

### 1- Problem Description and Background Discussion 
A producer of deli meat located in California supplies various types of cured meat to restaurants, supermarkets and coffee and sandwich shops located in the Los Angeles metropolitan area. His business is thriving and is considering expanding to another populous city with a similar profile of business distribution and people preferences. This producer’s business takes advantage of the appetite for cured meats in Mexican and Italian restaurants and would benefit from expanding to a city with a similar distribution of venues.

To help this producer decide between San Francisco and New York City, we will carry out an analysis of the type of venues and their distribution in each city and determine which of the two shares more similarity with Los Angeles, hence presenting a better chance of success.

We will first collect data on the neighborhoods of all three cities, including name, zip code and geographical coordinates. Then we will extract information on the venues located within each neighborhood. A clustering of the neighborhoods based on the type of venues they host will follow, together with analysis of the types of venues and the cluster distribution on the map. Finally we will estimate the similarity between cities to provide a recommendation. 

### 2- Data Description and Application for Solving the Problem

The extraction and processing of the source data followed several steps:

####	2.1- Web data scraping:
To obtain geographical information from each city, one web site was selected in each case that included a table with at least zip-codes and neighborhood names for that city. 


The data was scraped using the library requests to grab html data and the library BeautifulSoup to scrape html data. 
The data for each city was wrangled separately according to the characteristics of the URL source and converted to a dataframe with the columns ‘Neighborhood’ and ‘Zip Code’. 




| Los Angeles        | San Francisco           | New York City  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

	 	 
 	 	 

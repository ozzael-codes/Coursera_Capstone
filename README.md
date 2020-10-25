# Coursera_Capstone

Final Report | Capstone Project – The Battle of Neighborhoods Finding a Better Place in Scarborough, Toronto
### Introduction:
The purpose of this Capstone Project is to help people explore better facilities around their neighborhood. Since many people are migrating to various states of Canada and tons of research is needed for good housing prices and reputed schools for their children. 
We aim to create a comparative analysis of neighborhoods for people migrating to Scarborough to search for the best neighborhood. The features include median housing price and better school according to ratings, crime rates of that particular area, road connectivity, weather conditions, good management for emergency, water resources etc


### Data Section
Data: https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M
Foursquare API Data:
The data retrieved from Foursquare contained information of venues within a specified distance of the longitude and latitude of the postcodes. The information obtained per venue as follows:
1. Neighborhood
2. Neighborhood Latitude
3. Neighborhood Longitude
4. Venue
5. Name of the venue e.g. the name of a store or restaurant
6. Venue Latitude
7. Venue Longitude
8. Venue Category


### Map of Scarborough

Map%20of%20Scarborough.png

### Methodology Section
Clustering Approach:
To compare the similarities of two cities, we decided to explore neighborhoods, segment them, and group them into clusters to find similar neighborhoods in a big city like New York and Toronto. To be able to do that, we need to cluster data which is a form of unsupervised machine learning: k-means clustering algorithm.

Using K-Means Clustering Approach

Using%20K-Means%20Clustering%20Approach%20-%2010th%20Most%20Common%20Venue.png

Most Common venues near Neighborhood

Most%20Common%20venues%20near%20neighborhood.png

Work Flow:
Using credentials of Foursquare API features of near-by places of the neighborhoods would be mined. Due to http request limitations the number of places per neighborhood parameter would reasonably be set to 100 and the radius parameter would be set to 500.

4. Results Section
Map of Clusters in Scarborough

Map%20of%20Clusters%20Scarborough.png

Average Housing Price by Clusters in Scarborough

Average%20Housing%20Price.png

School Ratings by Clusters in Scarborough

School%20Ratings%20by%20Clusters.png



### Foursquare API:
This project have used Four-square API as its prime data gathering source as it has a database of millions of places, especially their places API which provides the ability to perform location search, location sharing and details about a business.

### Discussion Section
Problem Which Tried to Solve:
The major purpose of this project, is to suggest a better neighborhood in a new city for the person who are shiffting there. Social presence in society in terms of like minded people. Connectivity to the airport, bus stand, city center, markets and other daily needs things nearby.

Sorted list of house in terms of housing prices in a ascending or descending order
Sorted list of schools in terms of location, fees, rating and reviews
6. Conclusion Section
In this project, using k-means cluster algorithm I separated the neighborhood into 10(Ten) different clusters and for 103 different lattitude and logitude from dataset, which have very-similar neighborhoods around them. Using the charts above results presented to a particular neighborhood based on average house prices and school rating have been made.

### Future Work:
This project can be continued for making it more precise in terms to find best house in Scarborough. Best means on the basis of all required things(daily needs or things we need to live a better life) around and also in terms of cost effective.


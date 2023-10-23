# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
My goal with this project is to be able to navigate through different public APIs from multiple areas from the internet. Then import, clean, and organize the data so that it is readable and ready for analysis.
Then I would like to be able to create a database of this compiled data and then visualize trends within the data which will give me insights about bike stations and restaurants in the city of Hamilton to potentially drive business decisions and increase profit.
## Process
Step 1 - Acquire API data from city bikes api and parse the json data for latitude longitude and number of bikes in the city of Hamilton 
Step 2- Acquire API data from Foursquare and Yelp for restaurants in the city of Hamilton and query every restaurant within 1km of each bike station in the city of HAmilton 
Step 3- Join the data to create a main dataframe and then use bar chart to visulize some of the data 
Step 4 - Lastly, build a linear regression model that summarizes the relationship between the number of bikes in a particular location and the rating of the restaurants in that location 


## Results
my results showed a really small positive correlation which may indicate that there is NO relationship or this may even indicate a negative relationships caused by the theory that people who use city bikes are of lower socioeconomic status and retaurants that are highly rated are more expensive to dine at. The theory could be derived that there is a inverse relationship between city bike amount within 1000m of each retaurants and their relationship with restaurant ratings.

## Challenges 
main challenges i faced were trying to acquire the API data, it seemed that i ran into some bug that wouldnt accept my API key which delayed my progress
## Future Goals
If i had more time i would spend more time getting more data from different APIs to get more accurate models about bike station numbers and restaurant ratings

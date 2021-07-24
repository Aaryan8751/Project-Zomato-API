# Project-Zomato-API
## Description
### Part I
Zomato APIs give you access to the freshest and most exhaustive information for over 1.5 million restaurants across 10,000 cities globally.
Zomato API documentation link
Note: Currently, the official Zomato API documentation is down. As a replacement, to understand the documentation refer to the following link

Since you would not be able to use the official website to generate your own access key, for now use any of the following user keys: <br>

    ```
    627c28c07ad221c65491bbffea6f5d54
    68a952b60155797d28def1585d888b9f
    a1460684c45b3ba1a38a6b1473597055
    399720f6f904f106e162cd2bd0011a6f
    816c8c7a9e52da5bd2dcc0446558288d
    ```


By Collecting the data using Zomato API one can recommend restaurants on the basis of user’s affinity to specific cuisines, establishment types, locations, and price bands.
We can find out whether restaurant support online reservation or not.
We can find what is the most popular and/ or exclusive/new at a given location & time.

### Part II
Dataset Collection -
Due to Zomato API Basic Plan restriction, we cannot collect enough data for analysis. To overcome this problem ‘Zomato.csv’ file is provided to analyse the data deeply and to get useful inference.
Data has been collected from the Zomato API in the form of .json files(raw data) using the following url and stored in CSV file -
https://developers.zomato.com/api/v2.1/search?entity_id=1&entity_type=city&start=1&count=20  <br>
Download [Link](https://drive.google.com/file/d/1FSa_x3COvCoMODa44qXufO9CQb3ydqKw/view)


Details of zomato.csv -

```
Restaurant Id : Unique id of every restaurant across various cities of the world
Restaurant Name : Name of the restaurant
Country Code : Country in which restaurant is located
City : City in which restaurant is located
Address : Address of the restaurant
Locality : Location in the city
Locality Verbose : Detailed description of the locality
Longitude : Longitude coordinate of the restaurant's location
Latitude : Latitude coordinate of the restaurant's location
Cuisines : Cuisines offered by the restaurant
Average Cost for two : Cost for two people in different currencies
Currency : Currency of the country
Has Table booking : yes/no
Has Online delivery : yes/ no
Is delivering : yes/ no
Switch to order menu : yes/no
Price range : range of price of food
Aggregate Rating : Average rating out of 5
Rating color : depending upon the average rating color
Rating text : text on the basis of rating of rating
Votes : Number of ratings casted by people
```

Country Codes :

| Country Codes | Country |
| ------------- | ------------- |
| 1  | India  |
| 14  | Australia  |
| 30  | Brazil  |
| 37  | Canada  |
| 94  | India  |
| 148  | New Zealand  |
| 162  | Phillipines  |
| 166  | Qatar  |
| 184  | Singapore  |
| 189  | South Africa  |
| 191  | Sri Lanka  |
| 208  | Turkey  |
| 214  | UAE  |
| 215  | United Kingdom  |
| 216  | United States  |
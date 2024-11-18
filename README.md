# Final-Project-Statistical-Modelling-with-Python

## Project/Goals

1. Connecting to CityBikes API and retrieving data.
2. Connecting to Foursquare and Yelp APIs and retrieving data.
3. Joining collected and transforming collectd data.
4. Building a Model and further evaluation of the data.

## Process

### 1. Connecting to and utilizing FourSquare & Yelp APIs

### 2. Data transformation and cleanup

## Results

Both Foursquare and Yelp APIs are popular platforms for accessing data about local businesses, places, and user reviews.

- Both APIs are developer-friendly and use RESTful interfaces with JSON responses.
- Foursquare: Easier to integrate for venue searches and location features.
- Yelp: Slightly more complex due to detailed business and review data.

Foursquare API provides data on venues, places, and categories globally.
Focuses on location-based exploration, check-ins, and venue data.
Used to for finding nearby venues, creating location-aware apps.

Yelp API focuses on business information, reviews, adn ratings.
Business listings with detailed reviews and ratings.
Used to access reviews, ratings, and detailed business data.

## Challenges

Integrating and using Foursquare and Yelp APIs comes with its own set of challenges.
Here's a comparison of the common issues developers may face with each API:

- Authentication and Rate Limits - using the services is costly
- Data Completeness - each API has its own scope, combination of both brings more choices
- Data Structure and Usage - complex and nested, handling pagination and response size limits

Summary of Key Challenges

| Category            | Foursquare API                        | Yelp API                                  |
|---------------------|---------------------------------------|-------------------------------------------|
| Missing Features    | Reviews and ratings                   | Non-business venues                       |
| Coverage            | Uneven rural or remote area data      | Weak international presence               |
| API Call Complexity | Nested data fields                    | Multiple calls for complete business info |
| Rate Limits         | Generous but may still be restrictive | Lower free-tier limits                    |
| Documentation       | Incomplete or outdated examples       | Sparse advanced use-case examples         |

## Future Goals

I would need more time to explore all available combination of search criteria.

I would explore documentation and support option.

I would choose Foursquare focusing on location-based services, venue exploration, or global coverage.

I would use Yelp for detailed business reviews, ratings, and customer insights, especially in the U.S.
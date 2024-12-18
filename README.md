# Final-Project-Statistical-Modelling-with-Python

## Project/Goals

- Accessing data using APIs (CityBikes, FourSquare, Yelp)
- Cleaning and transforming data using Python
- Loading data into a database using Python
- Performing EDA, including using both statistics and visualizations
- Identifying trends and patterns in data using statistical models
- Building a Model and further evaluation of the data.
- Interpreting the results of the statistical models

## Process

### 1. Connecting to and utilizing CityBikes, FourSquare & Yelp APIs

- Create accounts online and obtain API Keys
- Prepare queries for the APIs
- Query and store the data for further usage

### 2. Data transformation and cleanup

- Review and analyze the data
- Create data storages
- Clean up and store the data

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
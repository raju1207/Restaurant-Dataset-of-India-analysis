# Restaurant-Dataset-of-India-analysis
The dataset contains information about restaurants in India, structured across 11 columns and 10,728 entries. Here’s a quick breakdown of the dataset:
Dataset Overview

### Columns:

**Restaurant**: Name of the restaurant.

**City**: City where the restaurant is located.

**Area**: Specific area within the city.

**Address**: Full address of the restaurant.

**Food type**: Types of cuisine served.

**Price**: Average price for two people (in INR).

**Avg ratings**: Average customer ratings.

**Total ratings**: Total number of customer reviews/ratings.

**longitude**: Longitude of the restaurant's location.

**latitude**: Latitude of the restaurant's location.

# Data Types:

Mixed ​

# Key Insights from the Dataset


**Data Distribution**: The dataset contains entries from multiple cities, likely covering a wide geographical range within India.

**Restaurant Attributes**: Information includes both qualitative data (like restaurant name, food type, and address) and quantitative data (like price, ratings, and geographical coordinates).

**Price and Ratings**:
   
  1. Prices are represented as floating-point numbers, denoting the approximate average cost for two people.
    
  2. Ratings (average and total) provide insights into customer feedback and popularity.

# Potential Use Cases

This dataset can serve multiple purposes:

 **Restaurant Recommendation Systems**: Using ratings and price information to recommend restaurants.
 
 **Market Analysis**: Understanding pricing trends and customer preferences by location.
 
 **Geographical Visualization**: Mapping restaurants based on latitude and longitude.
 
 **Culinary Diversity Analysis**: Exploring the prevalence of different cuisines across Indian cities.

# Suggested Cleaning Steps

Remove the Unnamed: 0 column as it duplicates the index.

Standardize the Food type column for consistent cuisine naming.

Check for potential outliers in Price and Avg ratings.

Validate latitude and longitude coordinates for accuracy.

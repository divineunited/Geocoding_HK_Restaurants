# Expanding data for Open Rice restaurants via JSON API calls and visualization

![Open Rice](https://github.com/divineunited/Geocoding_HK_Restaurants/blob/master/data/openrice.png)

This analysis starts with open data from Open Rice - Hong Kong's most popular dining guide to help people find places to eat based on the restaurant reviews written by real local people. In part 1 of our data analysis, we will use that data from Open Rice and an API call to get latitude and longitude information for each restaurant in JSON form. In part 2, we will use our JSON data to do some analyses and data visualizations.

## Geocoding
The Hong Kong government provides an [API](https://data.gov.hk/en-data/dataset/hk-ogcio-st_div_02-als/resource/ac80cf7b-f1e8-40d1-8b1c-8ea344d6e4cf) for address lookup which can be used to get the longitude and latitude for the address. Although many other APIs provide geo coding like Google or Bings API, sometimes they don't work so great with Hong Kong Addresses. 

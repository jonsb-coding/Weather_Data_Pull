# python_api_challenge

#### WeatherPy Desctiption

This code will 
 First compile a list of latitude and longitude and find the location name.
 
 Run requests from the open weather map and collect data on...
   
   * Name
   * Latitude
   * Longitude
   * Max Temperature
   * Humidity
   * Cloudiness
   * Wind Speed
   * Country
   * Date
 
 Export results to a dataframe 
 
 Create plots for...
   
   * Temperature (F) vs. Latitude
   * Humidity (%) vs. Latitude
   * Cloudiness (%) vs. Latitude
   * Wind Speed (mph) vs. Latitude
 
 Impose a linear regression for the following plots...
   
   * Northern Hemisphere - Temperature (F) vs. Latitude
   * Southern Hemisphere - Temperature (F) vs. Latitude
   * Northern Hemisphere - Humidity (%) vs. Latitude
   * Southern Hemisphere - Humidity (%) vs. Latitude
   * Northern Hemisphere - Cloudiness (%) vs. Latitude
   * Southern Hemisphere - Cloudiness (%) vs. Latitude
   * Northern Hemisphere - Wind Speed (mph) vs. Latitude
   * Southern Hemisphere - Wind Speed (mph) vs. Latitude
   
  #### VacationPy Desctiption
  
  This code will
    * First pull the data frame from WeatherPy 
    * Create a heat map for each location in the data frame and measure by humidity
    * Apply restrictions to the data frame and create new results data frame named hotel_df
    * run a google maps api request to get closest hotel to citys in hotel_df and label locations on heat map

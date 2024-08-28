# Mapping EV Stations In Connecticut

## Project Description

This project involves processing and visualizing data related to electric vehicle (EV) charging stations in Connecticut. The goal is to create an interactive map that displays the locations of these stations, making it easier to find and analyze EV charging infrastructure in the state.

The project is implemented using **pandas** for data manipulation and **folium** for creating interactive maps.

## Dataset

The data for this project can be found [here](https://catalog.data.gov/dataset/electric-vehicle-charging-stations). It includes various details about EV charging stations, including their locations.

## Steps

1. **Data Import**: Load the data from the CSV file.
2. **Data Cleaning**: 
   - Drop unnecessary columns.
   - Extract latitude and longitude from a georeferenced column.
   - Rename columns for consistency.
3. **Data Conversion**: Convert latitude and longitude values to the appropriate data type (float).
4. **Data Visualization**: 
   - Create an interactive map using folium.
   - Add markers to the map representing each EV charging station.
   - Customize the map’s center and zoom level for better visualization.

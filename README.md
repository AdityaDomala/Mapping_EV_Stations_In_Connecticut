Mapping EV Stations In Connecticut
Project Description
This project involves processing and visualizing data related to electric vehicle (EV) charging stations in Connecticut. The goal is to create an interactive map that displays the locations of these stations, making it easier to find and analyze EV charging infrastructure in the state.

The project is implemented using pandas for data manipulation and folium for creating interactive maps.

Dataset
The data for this project can be found here. It includes various details about EV charging stations, including their locations.

Steps
Data Import: Load the data from the CSV file.
Data Cleaning:
Drop unnecessary columns.
Extract latitude and longitude from a georeferenced column.
Rename columns for consistency.
Data Conversion: Convert latitude and longitude values to the appropriate data type (float).
Data Visualization:
Create an interactive map using folium.
Add markers to the map representing each EV charging station.
Customize the map’s center and zoom level for better visualization.
Usage
Clone this repository: git clone <repository-url>
Install the required libraries: pip install pandas folium
Place the dataset CSV file in the project directory.
Run the Python script to generate the map.
Open the EV_Stations_Connecticut.html file in a web browser to view the interactive map.

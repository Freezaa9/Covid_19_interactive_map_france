# Covid_19_interactive_map_france
Interactive map of france showing : The number of emergency visits for suspected COVID-19 and number of medical procedures from SOS Doctors for suspected COVID-19 day by day and by department.

![Covid_19_interactive_map_france_Demo](Covid_19_interactive_map_france/gif_map.gif)

# To run the map by yourself:
Use your python console and go to the project directory
then use:
bokeh serve --show Covid_19_interactive_map_france.ipynb in your console


# To update the map with the latest data:
go to https://www.data.gouv.fr/fr/datasets/donnees-des-urgences-hospitalieres-et-de-sos-medecins-relatives-a-lepidemie-de-covid-19/
dowload the latest file by department.
Copy it in the data directory. 
In the notebook change the name of the variable "data_covid" with the new file name

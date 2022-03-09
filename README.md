# Historical_weather_files_from_MeteoFrance_to_Building_Simulation_file_format
Transforming historial Observed Weather Data from Meteo France (e.g. weather data  of 2003) to EPW format to be used in Building Performance Simulations

# Objective: Creating an EPW weather file from measured data of french weather stations for building simulation.

# Before running the script, a user need to download two types of raw data.

1- an EPW typical weather file for the target city/location from EnergyPlus Weather Data archives. 
   https://energyplus.net/weather-location/europe_wmo_region_6/FRA/FRA_Nantes.072220_IWEC (download an EPW file format).
   
2- Download raw weather data of your target weather year (e.g. 12 months of 2003 weather data) from MeteoFrance Archives 
   https://donneespubliques.meteofrance.fr/?fond=rubrique&id_rubrique=26 
   Données Publique −► Observations In situ −► Données SYNOP essentielles OMM −► Téléchargement de données archivées 
   
3- Save the files on your PC and run the Python script

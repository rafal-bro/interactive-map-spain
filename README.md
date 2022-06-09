# Interactive Map of Spain

This repository contains data and code to create an interactive map of Spain. 

The map was created for site selection in the [Humanotop ALDEA](https://humanotop.earth/aldea/) project. Custom layers with relevant information for the selection (e.g. potential abandonadas, PV potential, ...) are imported from `geojson` files. 
These files were created in advance using the package `geopandas` and can be found in the `data` folder.

To get started clone this repository and create a virtual environment using the `environment.yml` file by executing the following command in your terminal:

`conda env create -f <path to the environment.yml file>`

You can create and use you own map in the `Jupyter` environment by activating the environment, calling `jupyter notebook` and navigating to the `map.ipynb` file. If you just want to use the map, simply open the `html` file in your browser (Firefox recommended).

A description of the map with instruction manual and the sources of the data can be found in the file `map_information.pptx`. 
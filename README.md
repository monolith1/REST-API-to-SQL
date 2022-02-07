# Data from RESTful APIs to SQLite Database

Retrieving data from two RESTful APIs and writing it to an SQLite Database using Python, Pandas, SQLalchemy, folium for visualizations

## Project Overview

This project collects point-of-interest data for the area surrounding the last two apartments that I've lived in. The data is collected from FourSquare and Yelp APIs. The data is visualized on maps using Folium, and then written to an SQLite database using SQLalchemy. 

## Repository Overview

This repository contains the following files:

```
├───Locations_API.pptx
├───POI.db
├───POI.ipynb
├───README.md
├───tokyomap.html
└───torontomap.html
```

* **Locations_API.pptx** and **DeepLearning_w2v.ipynb** contains presentation slides detailing the project.
* **POI.db** is an SQLite DB containing all data collected from both APIs
* **POI.ipynb** contains all of the python code related to data collection, database writing, and visualization.
* **tokyomap.html** and **torontomap.html** contain interactive maps for each location that data was collected for.
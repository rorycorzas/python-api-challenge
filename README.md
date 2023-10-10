# python-api-challenge

In this deliverable we create a Python script to visualize the weather of over 500 cities of varying distances from the equator. You'll use the citipy Python libraryLinks to an external site., the OpenWeatherMap APILinks to an external site., and your problem-solving skills to create a representative model of weather across cities.

# Prerrequisites

Clone the repository to your local machine.
Install the required libraries: pandas, numpy, matplotlib, seaborn, requests, citipy, and geopandas.
Obtain API keys for OpenWeatherMap and Geoapify.
Create an api_keys.py file in the project directory and add your API keys as variables.
Open the WeatherPy.ipynb and VacationPy.ipynb Jupyter notebooks to explore the analyses and visualizations.
In order to accomplish this task it is necessary to install the next python libraries:

(dev) auroracorzas@192 sqlalchemy-challenge %
pip install hvplot 
pip install cartopy 
pip install geoviews

**************************************************************************************************

/*                                Part 1:  WeatherPy                                            */

**************************************************************************************************

First we worked on the WeatherPy.ipynb Jupyter notebook provided in the starter code ZIP file. 

To get started, the code required to generate random geographic coordinates and the nearest city to each latitude and longitude combination is provided.

Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
To fulfill the first requirement, it is necessary use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. 

Next, generate the scatter plots to showcase the following relationships:

* Latitude vs. Temperature

* Latitude vs. Humidity

* Latitude vs. Cloudiness

* Latitude vs. Wind Speed

THis plots are included in the output_data folder attached to the repository

Requirement 2: Compute Linear Regression for Each Relationship
To fulfill the second requirement, we compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). You may find it helpful to define a function in order to create the linear regression plots.

Next, create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r values

* Northern Hemisphere: Temperature vs. Latitude

* Southern Hemisphere: Temperature vs. Latitude

* Northern Hemisphere: Humidity vs. Latitude

* Southern Hemisphere: Humidity vs. Latitude

* Northern Hemisphere: Cloudiness vs. Latitude

* Southern Hemisphere: Cloudiness vs. Latitude

* Northern Hemisphere: Wind Speed vs. Latitude

* Southern Hemisphere: Wind Speed vs. Latitude

**************************************************************************************************

/*                                Part 2:  VacationPy                                           */

**************************************************************************************************

In this part, we use our weather data to plan future vacations. We use Jupyter notebooks, the geopandas Python library, and the Geoapify API to create map visualizations of our ideal vacation spots.

We narrow down the city_data DataFrame to find our ideal weather conditions and use the Geoapify API to find the first hotel located within 10,000 meters of our coordinates.

# Technologies Used

Python
Jupyter Notebooks
Pandas
Numpy
Matplotlib
Seaborn
Requests
Citipy
Geopandas
OpenWeatherMap API
Geoapify API


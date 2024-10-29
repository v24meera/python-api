# python-api-challenge
What is the weather like as we approach the equator? Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?

## Part 1: WeatherPy
# Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
To fulfill the first requirement, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:

Latitude vs. Temperature

Latitude vs. Humidity

Latitude vs. Cloudiness

Latitude vs. Wind Speed

## Requirement 2: Compute Linear Regression for Each Relationship
To fulfill the second requirement, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). You may find it helpful to define a function in order to create the linear regression plots.

Next, create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r^2 values as you can see in the following image

Sample scatter plot with the linear regression line.
You should create the following plots:

Northern Hemisphere: Temperature vs. Latitude

Southern Hemisphere: Temperature vs. Latitude

Northern Hemisphere: Humidity vs. Latitude

Southern Hemisphere: Humidity vs. Latitude

Northern Hemisphere: Cloudiness vs. Latitude

Southern Hemisphere: Cloudiness vs. Latitude

Northern Hemisphere: Wind Speed vs. Latitude

Southern Hemisphere: Wind Speed vs. Latitude

After each pair of plots, explain what the linear regression is modeling. Describe any relationships that you notice and any other findings you may uncover.

## Part 2: VacationPy
In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

The code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1 is provided to help you get started.

Your main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.

To succeed on this deliverable of the assignment, open the VacationPy.ipynb starter code and complete the following steps:

1 Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.
2 Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:

* A max temperature lower than 27 degrees but higher than 21
* Wind speed less than 4.5 m/s
* Zero cloudiness


## References:
- In completing this assignment, I referenced a variety of supplementary resources to clarify coding concepts and enhance my understanding of data analytics techniques. 
Due to limited availability of tutoring support during my work hours, I consulted platforms such as Google, YouTube, ChatGPT, and reputable data analytics sites like GeeksforGeeks, Kaggle, and Stack Overflow. 
I also utilized AI tools for coding assistance and guidance on specific coding challenges, which provided additional clarity and support for troubleshooting issues outside of standard support hours.

- The code and analyses presented in this assignment are authored by me, with these external resources and AI tools used strictly for educational and guidance purposes. 
This disclosure is intended to provide transparency to the grading staff, ensuring they understand the context of my consultations with external resources and that my work reflects my independent efforts.


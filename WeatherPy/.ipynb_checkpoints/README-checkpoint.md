# Python-api-challenge

Background

Data's true power is its ability to definitively answer questions. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"

Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?

Weather Analysis

The WeatherPy directory comprises two Jupyter source files, namely WeatherPy.ipynb and VacationPy.ipynb. These files are designed to fetch relevant data from two distinct API providers, namely OpenWeatherMap and Geoapify, in order to collect data for over 500 cities falling within specified coordinates. Additionally, a repository labeled output_data contains the resultant images generated through the WeatherPy.ipynb file.

Within the Jupyter source files, the Pandas library is employed to construct DataFrames for each dataset. Matplotlib is utilized to generate a series of scatter plots that visualize various variables. The Scipy library, along with linregress, is imported to facilitate statistical computations and the creation of linear regression lines to represent the relationships between data points. Citipy is employed to generate a list of cities based on given coordinates. Furthermore, interactive data visualization is achieved through the use of hvplot, while geoviews is imported to explore and visualize geographical data

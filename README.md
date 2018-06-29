# Weather Forecasting App

This SPA will proved a 5-day 3-hourly weather forecast, aggregating weather data
from openweathermap.org and graphically displaying temperature, air pressure and
humidity for US cities that the user searches for. Every search will be 
appended to the list so multiple forecasts can be viewed for different cities
in a single session.

## App Overview

This training app aims to implement redux with AJAX calls and 3rd party
components. Calls are made to openweathermap.org API using the axios library.
The received promise object is passed through react-promise middleware and
passed onto reducers once resolved.

Components are then rendered using a react-sparkline 3rd party component
visualize the information in line graphs.

## Notable Libraries Used

1. react-redux
2. react-sparkline
3. redux-promise
4. axios
5. lodash
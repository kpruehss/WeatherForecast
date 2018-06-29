# Weather Forecasting App

## App Overview

This training app aims to implement redux with AJAX calls and 3rd party
components. AJAX calls are made to openweathermap.org using the axios library.
The received promise object is passed through react-promise middleware and
passed onto reducers once resolved.

Components are then rendered and react-sparkline 3rd party component is used 
to render line graphs to visualize the information.

### Notable Libraries Used
1. react-redux
2. react-sparkline
3. lodash
4. axios
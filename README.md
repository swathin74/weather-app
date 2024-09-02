# Weather Application

A simple Vue.js application that allows users to check the weather of a specified city. The application interacts with a weather API and displays the weather data, including the temperature and a description of the weather. It also handles error cases such as invalid city names.

## Features

- Input a city name to retrieve weather information.
- Displays temperature, weather description, and other details.
- Displays 7 days weather forecast
- Displays weather based on the current location 

## Technologies Used

- Vue.js 3
- Vue Router
- Axios for HTTP requests
- Node.js with Express (for the server-side)
- Visual Crossing Weather API to fetch weather details by city name
_ Geolocation API to display location based on current user location

## Project setup
```
npm install
```

## Set up environment
```
API_KEY=CB2GB98PFZ9HB2GDZRUER5LDB
port=3000
url=http://localhost:3000/api/weather
```
### Run the Application server
```
npm run serve
```

### Run the development server
```
npm server/index.js
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

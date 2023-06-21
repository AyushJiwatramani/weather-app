# Weather App

This is a weather application built with React JS and Tailwind CSS, utilizing the OpenWeatherMap API to fetch weather data. The app provides hourly and daily forecasts, as well as essential weather information such as temperature, maximum and minimum temperature, humidity, real feel, sunrise and sunset times. Additionally, the app displays the local time at the selected location.

## Technologies Used

- JavaScript
- React
- Tailwind CSS
- luxon
- unicons
- react-toastify

## Features

- Fetching weather data from OpenWeatherMap API
- Displaying temperature, max and min temperature, humidity, real feel, sunrise, sunset, hourly and daily forecasts
- Showing local time at the selected location
- Quick links for popular cities
- Text box for searching cities
- Current location-based search

## Installation

1. Clone the repository:

```
git clone https://github.com/your-username/weather-app.git
```

2. Navigate to the project directory:

```
cd weather-app
```

3. Install the dependencies:

```
npm install
```

## Configuration

Before running the application, you need to obtain an API key from [OpenWeatherMap](https://openweathermap.org/) by creating an account. Once you have the API key, follow these steps:

1. Rename the `.env.example` file to `.env`.

2. Open the `.env` file and replace `YOUR_API_KEY` with your actual OpenWeatherMap API key.

```
REACT_APP_API_KEY=YOUR_API_KEY
```

## Usage

To start the development server, run the following command:

```
npm start
```

The application will be accessible at `http://localhost:3000`.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request in this repository.

## Acknowledgements

- [OpenWeatherMap](https://openweathermap.org/) for providing the weather data API.
- [React](https://reactjs.org/) for the JavaScript library.
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework.
- [luxon](https://moment.github.io/luxon/) for handling dates and times.
- [unicons](https://iconscout.com/unicons) for the open-source icon library.
- [react-toastify](https://fkhadra.github.io/react-toastify/) for displaying toast notifications.

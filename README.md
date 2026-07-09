# React Weather App

A simple, intuitive weather application built with React that provides real-time weather data for any city worldwide using the OpenWeatherMap API.

## Features

- Search weather by city name
- Real-time temperature (Celsius / Fahrenheit)
- Weather condition with descriptive icon
- Humidity and wind speed details
- Responsive design â€” works on mobile and desktop
- Clean, minimal UI

## Tech Stack

| Layer | Technology |
|-------|------------|
| Framework | React.js |
| API | [OpenWeatherMap API](https://openweathermap.org/api) |
| HTTP Client | Axios |
| Styling | CSS3 |

## Getting Started

### Prerequisites

- Node.js >= 14
- Free API key from [OpenWeatherMap](https://openweathermap.org/api)

### Installation

`ash
git clone https://github.com/Gdhanush-13/Weather-App.git
cd Weather-App
npm install
`

Create a .env file in the project root:

`
REACT_APP_WEATHER_API_KEY=your_api_key_here
`

`ash
npm start
`

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Usage

1. Type a city name in the search box
2. Press **Enter** or click the search button
3. View temperature, conditions, humidity, and wind speed

## Project Structure

`
Weather-App/
â”œâ”€â”€ public/
â””â”€â”€ src/
    â”œâ”€â”€ components/
    â”‚   â””â”€â”€ WeatherCard.js   # Weather display component
    â”œâ”€â”€ App.js               # Main app with API call logic
    â””â”€â”€ index.js
`

## API Reference

This app uses the [OpenWeatherMap Current Weather API](https://openweathermap.org/current):

`
GET https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}
`

## License

MIT â€” free to use and modify.
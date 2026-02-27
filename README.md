
#############33

# Weather-App-Main

A Python-based weather application that fetches current weather data and forecasts for a specified city using the OpenWeatherMap API.

## Features

- Retrieve current weather conditions (temperature, humidity, wind speed, etc.)
- Get 7-day weather forecast
- Search weather by city name
- Simple command-line interface (CLI) or GUI

## Requirements

- Python 3.x
- `requests` library

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Weather-App-main.git
   ```
2. Navigate into the project directory:
   ```bash
   cd Weather-App-main
   ```
3. Install dependencies:
   ```bash
   pip install requests
   ```
4. Obtain an API key:
   - Sign up at [OpenWeatherMap](https://openweathermap.org/api)
   - Generate an API key
5. Configure your API key:
   - Create a `config.py` file in the project root
   - Add your API key:
     ```python
     API_KEY = 'your_api_key_here'
     ```

## Usage

Run the main script:
```bash
python weather_app.py
```

Follow the prompts to enter a city name and view the weather data.

## Example

```bash
Enter city name: London
Current weather in London:
Temperature: 15°C
Humidity: 82%
Wind Speed: 5 m/s
```

## Code Overview

- `weather_app.py`: Main program that handles user input and displays data.
- `config.py`: Contains your API key.
- `utils.py`: Helper functions for API requests and data parsing.






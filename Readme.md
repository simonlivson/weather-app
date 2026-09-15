# Weather App

A desktop weather app written in Python with PyQt5.
Type a city name, click Get Weather, and the app shows temperature,
a weather emoji, and a short description.

Data comes from the OpenWeatherMap API.

## Requirements

- Python 3
- Packages listed in `requirements.txt`

## Install

    pip install -r requirements.txt

## API key

1. Create a free key at https://openweathermap.org/api
2. Do not put the key in the Python file.
3. Set it in the terminal:

    export OPENWEATHER_API_KEY="your_key_here"

On Windows Git Bash you can add that line to ~/.bashrc so it persists:

    echo 'export OPENWEATHER_API_KEY="your_key_here"' >> ~/.bashrc
    source ~/.bashrc

## Run

From the project folder:

    python weather_app.py

Or open the project folder in VS Code and press Play.

## Project files

- `weather_app.py` — the app
- `requirements.txt` — Python packages
- `.gitignore` — files Git should ignore
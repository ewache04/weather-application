
---

# WeatherPulse

**WeatherPulse** is an advanced weather application developed by **Jeremiah Ochepo** in collaboration with **PM Accelerators**. This app provides users with precise, real-time weather data, transforming weather updates into actionable insights. WeatherPulse aims to ensure that everyone stays well-prepared for any weather conditions, eliminating surprises with accessible and reliable weather information.

## Features

- **Real-Time Weather Data**: Get current weather information for any city worldwide.
- **5-Day Weather Forecast (optional)**: View a forecast for the next five days to plan ahead.
- **Location-Based Weather (optional)**: Automatically receive weather updates based on your location.
- **Intuitive Design**: Clean and user-friendly interface.
- **Visual Enhancements (optional)**: Use icons and images to represent different weather conditions.

## Technology Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (Flask)
- **API**: OpenWeatherMap API (or any other weather data provider)
- **Version Control**: Git

## Setup and Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/weatherpulse.git
    cd weatherpulse
    ```
2. **Create a virtual environment**:
    ```bash
    python3 -m venv venv
    source venv/bin/activate   # On Windows: venv\Scripts\activate
    ```
3. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
4. **Set up environment variables**:

   Create a `.env` file in the project root and add the following environment variables:

    ```bash
    FLASK_APP=run.py
    FLASK_ENV=development
    SECRET_KEY=mysecretkey_2024
    WEATHER_SOURCE_API_KEY=b21a2633ddaac750a77524f91fe104e7
    APP_NAME=WeatherPulse
    ```

5. **Run the application**:
    ```bash
    flask run
    ```
6. **Access the application**:  
   Open your browser and navigate to `http://127.0.0.1:5000/` or `http://127.0.0.1:8000/`.

## How to Use

1. **Enter a city name**: Input the name of the city you want to check the weather for.
2. **View the weather details**: WeatherPulse will display the current weather conditions, including temperature, humidity, and wind speed.
3. **Explore additional features (optional)**: If implemented, you can check the 5-day forecast or view weather based on your current location.

## Future Enhancements

- **Weather Alerts**: Notifications for severe weather conditions.
- **Historical Data**: Access past weather data for analysis.
- **User Personalization**: Save favorite locations and customize the display settings.

## Contributing

Contributions are welcome! If you'd like to contribute to WeatherPulse, please fork the repository, make your changes, and submit a pull request.

## Acknowledgements

- **OpenWeatherMap API**: For providing the weather data.
- **PM Accelerators**: For supporting the development of this project and fostering innovation.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---
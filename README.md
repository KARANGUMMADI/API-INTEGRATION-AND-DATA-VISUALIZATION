# API-INTEGRATION-AND-DATA-VISUALIZATION

COMPANY : CODTECH IT SOLUTIONS

NAME : GUMMADI KARAN

INTERNID : CT04DA875

DOMAIN : PYTHON PROGRAMMING

DURATION : 4 WEEKS

MENTOR : NEELA SANTHOSH KUMAR

DESCRIPTION :

📌 Overview :

This Python-based project fetches 5-day weather forecast data from the OpenWeatherMap API, processes it into a structured dataset, and generates insightful visualizations. The tool is designed for data analysts, weather enthusiasts, and developers who want to analyze and visualize weather trends efficiently.

Built in Google Colab, this script leverages Python’s powerful data processing and visualization libraries to create an interactive weather dashboard. The project is ideal for learning API integration, data wrangling, and visualization techniques.

📊 Dataset & Data Processing :

* The dataset is obtained from the OpenWeatherMap API (5-day forecast endpoint) and includes:

* Temperature (°C) – Current atmospheric temperature

* Feels-like temperature (°C) – Perceived temperature considering wind and humidity

* Humidity (%) – Relative humidity level in the air

* Wind speed (m/s) – Speed of wind gusts

* Weather conditions (e.g., Clear, Rain, Clouds) – Primary weather status

* Rainfall (mm) – Precipitation volume (if any)

* Cloud coverage (%) – Percentage of sky covered by clouds

* Timestamps (3-hour intervals for 5 days) – Forecast data points

Data Processing Workflow :

API Response Handling :

* The script makes an HTTP GET request to OpenWeatherMap’s forecast endpoint.

* Validates the response status code (200 for success, else error handling).

* Extracts JSON data containing weather predictions.

Data Structuring :

* Converts raw JSON into a pandas DataFrame for easier manipulation.

* Parses Unix timestamps into readable datetime formats.

* Handles missing values (e.g., rainfall data is set to 0 if not available).

Feature Engineering :

* Rounds numerical values (temperature, wind speed) for cleaner presentation.

* Groups data by date for aggregated insights (e.g., daily humidity averages).

🛠 Tools & Technologies Used :

* Programming Language: Python (3.7+)

Core Libraries:

* requests – Handles API calls efficiently with error management.

* pandas – Structures data into DataFrames for analysis.

* matplotlib & seaborn – Generate professional visualizations.

* datetime – Converts timestamps and manages time-based data.

* API: OpenWeatherMap (free tier with 60 calls/minute limit).

* Development Platform: Google Colab (cloud-based Jupyter environment).

✨ Key Features :

✅ Real-Time Weather Data Fetching :

* Dynamically retrieves forecasts for any city worldwide.

* Supports metric (°C, m/s) and imperial (°F, mph) units (configurable).

✅ Automated Data Cleaning :

* Handles missing/irregular data (e.g., rainfall may not always be present).

* Converts timestamps into human-readable formats.

✅ Interactive Visualizations :

* Temperature Trends (Line Plot) – Compares actual vs. feels-like temperature.

* Humidity Analysis (Bar Chart) – Shows daily humidity fluctuations.

* Wind Speed Trends (Line Plot) – Tracks wind variations over time.

* Weather Conditions (Pie Chart) – Displays weather distribution (Sunny, Rainy, etc.).

✅ Error Resilience :

* Checks API connectivity and valid city names.

* Gracefully exits if data fetching fails.

✅ Exportable Outputs :

* Saves visualizations as high-resolution PNGs with timestamps.

* Easy integration into reports or presentations.

🚀 Advantages :

✔ User-Friendly – Just input a city name, and the tool does the rest.

✔ Customizable – Easy to modify for different APIs or visualization styles.

✔ Educational – Great for learning API integration, data cleaning, and visualization.

✔ Scalable – Can be extended to include more weather metrics or historical data.


🔍 Use Cases :

🌦 Weather Forecasting – Analyze temperature, humidity, and rain predictions.

📈 Data Science Projects – Use as a base for climate analysis or ML models.

👨💻 Educational Tool – Teach API usage, pandas, and matplotlib.

📊 Dashboard Development – Integrate into a web app for real-time weather updates.

📌 How It Works :

* User Input: Enter a city name (e.g., "London").

* API Call: Fetches 5-day forecast data from OpenWeatherMap.

* Data Processing: Converts JSON into a structured DataFrame.

* Visualization: Generates a 4-panel dashboard with trends and distributions.

* Export: Saves the dashboard as a PNG file.

📜 Conclusion :

This project is a powerful yet simple tool for fetching, analyzing, and visualizing weather forecasts. It’s perfect for beginners learning APIs and experienced developers looking for a quick weather dashboard solution.

🔗 Try it out in Google Colab and explore weather trends in your city!

OUTPUT :

The image below is the output of the data of the day that I made this project. So the output may change acoording to the real time and wheather.

![Image](https://github.com/user-attachments/assets/a7c81440-c47c-4a85-b39b-e0ba314f6b21)

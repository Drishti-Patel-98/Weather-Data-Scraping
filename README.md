About: This project involved developing a Python-based solution to scrape real-time weather data from AccuWeather. The system collects comprehensive weather details for multiple nearby locations and compiles them into a structured dataset for analysis.

The scraper simulates a browser session using custom headers to bypass basic bot detection and accesses location-specific pages dynamically. Using BeautifulSoup, it extracts key weather parameters including:

- Date and time of update
- Location name
- Temperature
- Weather condition
- RealFeel Shade™
- Wind speed and direction
- Air quality

Each component of the scraper is modularized for clarity and maintainability. Extracted data is stored in a structured dictionary and converted into a Pandas DataFrame before being exported as a CSV file (weather_data.csv). The project ensures robustness by handling missing or unavailable data with fallback values and consistent formatting.

This ocan be extended for historical weather tracking, forecasting model input, or visualization in tools like Power BI or Tableau.

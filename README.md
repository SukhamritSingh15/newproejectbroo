# newproejectbroo

Project name - weather forecast

description - A weather forecast is a prediction of atmospheric conditions for a specific location over a certain period. Meteorologists use data from satellites, radar, and weather stations to analyze temperature, humidity, wind speed, air pressure, and precipitation patterns. Forecasts range from short-term (hours to days) to long-term (weeks or months), with varying accuracy. Modern weather forecasting relies on advanced computer models and AI to improve predictions, helping people plan daily activities, travel, and prepare for extreme weather events like storms, heatwaves, and heavy rainfall.

DEMO PREVIEW
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weather Forecast</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h2>Weather Forecast</h2>
        <img src="https://cdn-icons-png.flaticon.com/512/1163/1163661.png" class="weather-icon" alt="Weather Icon">
        <p class="temperature">25°C</p>
        <p class="description">Sunny with mild winds</p>
    </div>
</body>
</html>

CSS
body {
    font-family: Arial, sans-serif;
    background: linear-gradient(to right, #74ebd5, #acb6e5);
    text-align: center;
    padding: 20px;
}

.container {
    max-width: 400px;
    background: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
    margin: auto;
}

.weather-icon {
    width: 100px;
}

.temperature {
    font-size: 2em;
    font-weight: bold;
}

.description {
    color: #555;
}















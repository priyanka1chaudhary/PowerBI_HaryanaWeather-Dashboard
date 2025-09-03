# Haryana Weather Dashboard 🌦️

An interactive **Power BI Dashboard** to track weather metrics (temperature, humidity, wind speed) across multiple cities in Haryana, using the **OpenWeatherMap API**.

## 📊 Dashboard Preview
![Dashboard](img/overview.png)

## 🛠 Project Details
- **Tool**: Power BI Desktop
- **Data Source**: OpenWeatherMap API (Current Weather Data)
- **Techniques**: Power Query, DAX, API Integration, Data Modeling

## 📂 Repository Contents
- `reports/` → Power BI files (`.pbix` and `.pbit` template)
- `data/` → Sample dataset (`sample_cities.csv`) without API key
- `img/` → Dashboard screenshots
- `README.md` → Project documentation

## 🔑 Setup Instructions
1. Clone this repository.
2. Open `reports/Haryana-Weather-Dashboard.pbit` in Power BI Desktop.
3. Enter your **OpenWeatherMap API key** in the parameter box.
4. Refresh data → dashboard will update with live weather.

## 📈 Features
- City-wise weather KPIs:
  - **Max Temperature**
  - **Average Humidity**
  - **Max Wind Speed**
- Interactive Map with city bubbles
- Gauge chart for Avg Temperature
- Comparative bar chart for cities
- Auto-refresh capability via API

## 🔒 Security Note
- API keys are not included in this repo.
- Use your own OpenWeatherMap API key when refreshing.

## 🙌 Credits
- [OpenWeatherMap](https://openweathermap.org/)
- Built with ❤️ in Power BI

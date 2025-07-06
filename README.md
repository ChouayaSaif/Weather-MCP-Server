# 🌦️ Weather MCP Server

This project implements a weather information tool using the **MCP framework**. It fetches real-time weather data from the [Open-Meteo API](https://open-meteo.com/) based on geographical coordinates (latitude and longitude).

## 🚀 Features

- Built with [FastMCP](https://github.com/modularml/mcp) for modular tool integration.
- Asynchronous HTTP requests using `httpx`.
- Retrieves current weather details, including:
  - Temperature
  - Wind speed and direction
  - Cloud cover
  - Humidity
  - Rain, snowfall, and more

## 🛠 Usage

To run the server:

```bash
mcp dev main.py
```
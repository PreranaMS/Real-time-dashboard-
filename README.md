# Real-time-dashboard-

## Project Overview
This project demonstrates a live data pipeline that streams simulated sensor telemetry (Temperature, Humidity, Pressure) directly into a Power BI Dashboard using the Power BI REST API.

## Tech Stack
- **Language:** Python 3.x
- **Visualization:** Power BI Service (Streaming Semantic Models)
- **Libraries:** `requests`, `datetime`, `time`, `random`

## How it Works
1. The **Python Script** generates random telemetry data.
2. Data is formatted into a JSON payload and sent via a **POST request** to the Power BI API endpoint.
3. The **Power BI Dashboard** receives the data and updates visuals (Gauges, Line Charts) in real-time.


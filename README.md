# AI-Based-farm-Management-System
AI-Based farm Management System using python
🌾 Farm_ERA – AI-Powered Smart Farm Management System


🚀 A full-stack AI-based farm management system built using Streamlit, OpenCV, and GIS for real-time monitoring, field mapping, crop planning, and smart irrigation.

📌 Table of Contents
Overview

Features

Tech Stack

Screenshots

Installation

Usage

Architecture

Contributors

📖 Overview
Farm_ERA is an intelligent farm management system that integrates Geographic Information Systems (GIS), sensor-based irrigation monitoring, crop planning tools, pest and disease tracking, and weather forecasting into a unified platform. It helps farmers improve yield, resource efficiency, and environmental sustainability.

✨ Features
📍 GIS-Based Field Mapping using GeoJSON and Folium

🌱 Crop Planning with yield forecasting and rainfall analysis

💧 Smart Irrigation Scheduling with real-time flow control and sensor simulation

🐛 Pest & Disease Tracking based on temperature, humidity, and manual inputs

🌦️ Weather Monitoring with charts and correlation heatmaps

📊 Analytics & Visualizations using Matplotlib and Seaborn

🎥 Live Camera Feed and irrigation control via OpenCV

🛠️ Tech Stack
Frontend/UI: Streamlit, HTML/CSS

Backend & Logic: Python, Pandas, NumPy, OpenCV (cv2), GeoPy

Visualization: Matplotlib, Seaborn, Folium

Geo Mapping: GeoJSON, Shapely

Simulation: Custom Python scripts for sensors and water flow

Camera Feed: OpenCV video capture

Deployment: Local execution with .py and .geojson files



🔧 Installation
Clone the repository

cd Farm_ERA
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Start the application

bash
Copy
Edit
streamlit run app.py
🧪 Usage
📍 Use the sidebar to navigate between modules like Field Mapping, Crop Planning, Weather, Irrigation, etc.

🌍 Upload your farm's GeoJSON to calculate area and boundary.

🌧️ Input rainfall and crop data for planning.

💧 Monitor and control irrigation zones.

🐜 Track pest/disease conditions and receive alerts.

🧱 Architecture
pgsql
Copy
Edit
[GeoJSON]        [Sensor Sim]         [User Input]
    ↓                  ↓                   ↓
 Field Mapping     Moisture Data       Crop Planning
        \           /        \             /
        AI Models & Logic ———> Visualization Layer
                ↓
         Decision Support System

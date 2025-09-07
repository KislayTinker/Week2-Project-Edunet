# Week2-Project-Edunet

# Environment Monitoring & Pollution Control System

> **Software-only** — A beginner-friendly Flask web application that fetches environmental data (AQI, PM2.5/PM10, temperature, humidity), visualizes it (charts + map), and provides ML-based AQI prediction & alerts.

---

[# This project will have following feature.]

## Table of Contents
- [About](#about)  
- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Repository Structure](#repository-structure)  
- [Prerequisites](#prerequisites)  
- [Installation](#installation)  
- [Environment Variables](#environment-variables)  
- [Run the App](#run-the-app)  
- [Usage & API Endpoints](#usage--api-endpoints)  
- [Machine Learning (Train & Export)](#machine-learning-train--export)  
- [Mapping & Visualization](#mapping--visualization)  
- [Alerts & Recommendation Logic](#alerts--recommendation-logic)  
- [Testing](#testing)  
- [Deployment Tips](#deployment-tips)  
- [Contributing](#contributing)  
- [License](#license)

---

## About
This project is a Flask-based web dashboard for monitoring air quality and other environmental parameters. It pulls real-time data from public APIs, stores historical records, visualizes trends, shows pollution on a map, and exposes a simple ML-powered prediction endpoint.

Target audience: **Beginners** learning full-stack Python + Flask with basic ML.

---

## Features
- Real-time AQI and pollutant data via public APIs (OpenWeatherMap / AQICN / Ambee)  
- Interactive charts: time-series, gauge, pollutant bars (Plotly / Chart.js)  
- Map view for pollution hotspots (Leaflet.js)  
- Historical data storage (SQLite by default)  
- ML-based AQI prediction served by Flask (scikit-learn)  
- Threshold-based alerts and user recommendations

---

## Tech Stack
- **Backend:** Python, Flask  
- **Frontend:** HTML, Bootstrap, Plotly/Chart.js, Leaflet.js  
- **Data & ML:** pandas, scikit-learn, joblib, numpy  
- **DB:** SQLite (default; swapable)  
- **Optional:** Flask-SocketIO for live updates

---

## Repository Structure

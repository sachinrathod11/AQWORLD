# Air Quality Index (AQI) Search Engine

A full-stack Air Quality Index (AQI) web application that allows users to search real-time air quality data for any city.  
The system fetches live data from the AQICN API, processes it efficiently on the backend, and presents meaningful air-quality insights through a clean and interactive UI.

---

## 📌 Overview

This project is built with **Java (Spring Boot)** on the backend and **HTML, CSS, and JavaScript** on the frontend.  
It focuses on backend engineering concepts such as REST API design, caching, external API integration, and clean data processing, while also providing an intuitive user interface for visualizing air-quality metrics.

---

## 🚀 Features

### Core Features
- Search AQI by city name
- RESTful API built using Spring Boot
- Real-time AQI data fetched from AQICN
- Structured and clean JSON API response
- AQI categorization (Good → Severe)
- Health recommendations based on AQI levels
- Color-coded AQI visualization
- Intelligent in-memory caching (TTL + max size)
- Interactive pollutant charts using Chart.js
- Responsive dashboard layout (desktop-optimized)

### Advanced Enhancements
- Dominant pollutant detection (API-based with computed fallback)
- Detailed pollutant breakdown:
  - PM2.5
  - PM10
  - NO₂
  - SO₂
  - O₃
  - CO
- Graceful handling of missing or partial data
- Performance-optimized backend design

---

## 🧩 Tech Stack

### Backend
- Java 17
- Spring Boot
- Spring Cache with Caffeine
- Jackson
- Maven

### Frontend
- HTML
- CSS
- JavaScript (Fetch API)
- Chart.js

### External API
- **AQICN – World Air Quality Index**
  - https://aqicn.org/api/

---

## 📂 Project Structure


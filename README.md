# Oxima: Real-Time Ride-Hailing Frontend Portals (React 18 & Zustand)

[![React 18](https://img.shields.io/badge/React-18-blue.svg?style=flat&logo=react)](https://react.dev/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind-CSS-38bdf8.svg?style=flat&logo=tailwindcss)](https://tailwindcss.com/)
[![Zustand](https://img.shields.io/badge/Zustand-State%20Management-brown.svg)](https://github.com/pmndrs/zustand)
[![OSRM](https://img.shields.io/badge/OpenStreetMap-OSRM-brightgreen.svg)](https://project-osrm.org/)

> Dual-interface frontend client for the Oxima Ride-Hailing platform containing dedicated portals for **Riders** (`front-customer`) and **Drivers** (`front-driver`) with live GPS navigation, turn-by-turn road routing, and WebSocket telemetry.

---

## 📁 Repository Structure

```
oxima-frontend-web/
├── front-customer/      # Rider web application (fare estimate, booking, live tracking)
└── front-driver/        # Driver portal (duty toggle, request popups, navigation)
```

---

## ✨ Features

- **Live Road Routing**: Turn-by-turn route calculation and polyline rendering powered by OpenStreetMap OSRM routing engine.
- **Rider Portal**: Instant fare estimation, pickup/drop location search, proximity driver map markers, and live trip status.
- **Driver Portal**: Online/offline duty toggle, real-time incoming ride request drawer, accept/decline actions, and PIN verification.
- **State Management**: Zero-boilerplate reactive global state using **Zustand**.
- **Real-Time WebSockets**: Instant communication with backend for zero-latency ride lifecycle transitions.

---

## 🛠️ Tech Stack

- **Framework**: React 18
- **Styling**: Tailwind CSS
- **State**: Zustand
- **Maps & Geolocation**: Leaflet / React-Leaflet, OpenStreetMap, OSRM API
- **Networking**: Axios, Socket.IO Client / STOMP WebSockets

---

## 📦 Setup & Installation

```bash
# Run Customer Portal
cd front-customer
npm install
npm start

# Run Driver Portal
cd ../front-driver
npm install
npm start
```

---

## 👤 Author
**Vivek Kumar**  
Full-Stack & Distributed Systems Engineer &bull; Dual AWS Certified  
- LinkedIn: [linkedin.com/in/vivek-fullstack](https://www.linkedin.com/in/vivek-fullstack/)  
- GitHub: [github.com/Vivek-27](https://github.com/Vivek-27)

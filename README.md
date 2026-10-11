<div align="center">

# 🌤️ WeatherLive

### A Modern Glassmorphism Weather App with Realistic Wind-Driven Animated Clouds

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![OpenWeather](https://img.shields.io/badge/OpenWeather-API-orange?style=for-the-badge&logo=openweathermap&logoColor=white)](https://openweathermap.org/api)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

<img src="https://pngimg.com/uploads/cloud/cloud_PNG30.png" width="180" alt="Cloud"/>

**Real-time weather • Wind-driven clouds • 7-Day forecast • Geolocation**

[🚀 Live Demo](#-live-demo) • [✨ Features](#-features) • [🛠️ Installation](#️-installation) • [📸 Screenshots](#-screenshots) • [🤝 Contributing](#-contributing)

</div>

---

## 🌟 Overview

**WeatherLive** is a sleek, modern weather application built with **pure HTML, CSS, and JavaScript** — no frameworks, no build tools, no dependencies. It fetches **real-time weather data** from the **OpenWeather API** and presents it with a stunning **glassmorphism UI** and a **unique realistic cloud animation system** where clouds drift across the background in the **same direction as the actual wind** at your location.

> 🎯 **Unique Feature:** The animated clouds on the background don't just move randomly — they move **exactly in the direction of the real wind** (fetched from the weather API). If the wind blows east, clouds drift left → right. If the wind blows west, clouds drift right → left. Pure weather realism! 🌬️

---

## ✨ Features

### 🌦️ Core Weather Features
- ✅ **Real-time weather** — temperature, condition, min/max temps
- ✅ **7-Day forecast** — daily min/max & weather icons
- ✅ **Auto-geolocation** — detects your city automatically on load
- ✅ **City search** — search any city worldwide
- ✅ **Detailed metrics** — humidity, wind speed, sunrise/sunset, pressure
- ✅ **Air Quality (AQI)** — simulated from cloud density
- ✅ **UV Index** — calculated from time of day
- ✅ **Pressure status** — Low / Normal / High indicator

### 🎨 UI / UX Features
- 🪟 **Glassmorphism design** — frosted glass card with blur effects
- 📱 **Fully responsive** — perfect on mobile, tablet, and desktop
- 🌙 **Night sky theme** — moon glow + twinkling stars
- 🎨 **Smooth animations** — GPU-accelerated transitions
- 🌈 **Gradient accents** — premium gold + deep blue palette

### ☁️ Unique Cloud Animation System
- ☁️ **8 realistic cloud sprites** (transparent PNG)
- 🌬️ **Wind-driven direction** — clouds move the same way the real wind blows
- 🎭 **Depth layers** — near / mid / far clouds with different sizes & opacity
- 🔄 **Smooth direction switching** — instantly re-aligns when you change cities
- 🏷️ **Wind badge** — shows current wind direction & cloud movement on screen

---

## 🚀 Live Demo

> 🔗 **Try it live:** [https://yourusername.github.io/WeatherLive/](https://yourusername.github.io/WeatherLive/)

*(Replace `yourusername` with your actual GitHub username after enabling GitHub Pages.)*

---

## 📸 Screenshots

<div align="center">

### 🖥️ Desktop View
<img src="screenshots/desktop.png" alt="Desktop Screenshot" width="700"/>

### 📱 Mobile View
<img src="screenshots/mobile.png" alt="Mobile Screenshot" width="280"/>

### 🌬️ Wind-Driven Cloud Animation
<img src="screenshots/animation.gif" alt="Cloud Animation" width="700"/>

</div>

*(Create a `screenshots/` folder in your repo and add your own images.)*

---

## 🛠️ Installation

### 📋 Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A free **OpenWeather API Key** → [Get one here](https://home.openweathermap.org/users/sign_up)

### ⚡ Quick Start

**1. Clone the repository**
```bash
git clone https://github.com/yourusername/WeatherLive.git
cd WeatherLive
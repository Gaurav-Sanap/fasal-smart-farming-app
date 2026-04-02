# 🌾 Fasal Smart Farming App

A smart farming application designed for small and marginal farmers to monitor soil health, receive pest control recommendations, and get crop suggestions based on environmental conditions. The app aims to improve agricultural productivity through data-driven insights and user-friendly features.

---

## 📋 Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Installation & Setup](#installation--setup)
- [Project Structure](#project-structure)
- [Configuration](#configuration)
- [Usage](#usage)
- [API Integration](#api-integration)
- [Contributing](#contributing)
- [License](#license)

---

## ✨ Features

- **Soil Health Monitoring**: Track soil conditions and receive actionable insights
- **Pest Control Recommendations**: AI-powered suggestions based on crop type and environmental conditions
- **Crop Suggestions**: Get personalized crop recommendations based on:
  - Soil composition
  - Weather patterns
  - Regional climate data
- **Real-time Weather Data**: Integrated weather information for better farming decisions
- **AI-Powered Insights**: Uses Google Gemini API for intelligent recommendations
- **Image Recognition**: ML Kit for pest and crop disease identification using device camera
- **Location-Based Services**: GPS integration for localized recommendations
- **User-Friendly Interface**: Intuitive design optimized for ease of use

---

## 🛠 Tech Stack

### Core Technologies
- **Language**: Kotlin
- **Platform**: Android (API Level 24+)
- **Target SDK**: Android 15 (SDK 36)

### Key Libraries & Frameworks
- **UI Framework**: AndroidX, Material Design 3
- **Networking**: Retrofit with Gson converter
- **ML/AI**:
  - Google Generative AI (Gemini)
  - TensorFlow Lite
  - ML Kit (Image Labeling)
- **Camera**: AndroidX Camera (Camera2)
- **Location**: Google Play Services Location
- **Image Loading**: Glide
- **Lifecycle Management**: AndroidX Lifecycle, ViewModel
- **Layout**: FlexBox

### APIs & Services
- OpenWeatherMap API (Weather data)
- Google Generative AI API (Pest control & crop recommendations)

---

## 📋 Prerequisites

- **Android Studio**: Latest stable version (Flamingo or newer)
- **Java Development Kit (JDK)**: Version 11+
- **Android SDK**: API Level 36 (target), API Level 24 (minimum)
- **Gradle**: 8.0+

### Required API Keys
1. **OpenWeatherMap API Key**: For weather data
2. **Google Generative AI API Key**: For AI-powered recommendations

---

## 🚀 Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/Gaurav-Sanap/fasal-smart-farming-app.git
cd fasal-smart-farming-app

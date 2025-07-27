<div align="center">

# 👗 Outfit Recommender Based on Weather Conditions

A smart outfit recommendation system that uses real-time weather data to suggest appropriate clothing. It combines deep learning for outfit classification with a weather API for dynamic suggestions.

</div>

---

## 🧠 Project Overview

This project predicts suitable outfits by:
- Fetching **live weather data** using the **OpenWeatherMap API**
- Classifying outfits using a pre-trained **MobileNetV2** model
- Displaying relevant outfit **images from your dataset** based on current weather conditions

---

## 🚀 Features

- 🌦️ Real-time weather integration using location or city input
- 👕 Intelligent outfit recommendations (e.g., jackets for cold, cotton for hot)
- 🖼️ Visual outfit suggestions based on classified images
- 🔍 Simple web interface using **Flask**
- ⚙️ Lightweight and fast with MobileNetV2

---

## 🛠️ Tech Stack

| Tool         | Purpose                         |
|--------------|----------------------------------|
| Python       | Core logic and backend          |
| Flask        | Web application framework       |
| TensorFlow/Keras | Deep learning model (MobileNetV2) |
| OpenWeatherMap API | Weather data integration  |
| HTML/CSS/JS  | Frontend for user interaction   |

---

## 📁 Dataset

- **Fashion Product Images (Small)** from Kaggle
- Contains `styles.csv` for metadata and an `images` folder with clothing images
- Images used to train a lightweight MobileNetV2-based classifier

---

## 📷 Sample Output

| Weather | Recommended Outfit |
|--------|---------------------|
| ☀️ 32°C Sunny | Cotton T-shirt, Shorts |
| 🌧️ 22°C Rainy | Raincoat, Jeans |
| ❄️ 10°C Cold | Wool Jacket, Boots |

---

## 🔧 How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/outfit-recommender-weather.git
   cd outfit-recommender-weather

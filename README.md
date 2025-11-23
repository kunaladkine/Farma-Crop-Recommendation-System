---

# 🌾 Farmer Assistance Website

A smart platform designed to help farmers make better agricultural decisions using **AI-based crop prediction**, **real-time weather forecasting**, and an **online farming marketplace**.

---

## 🔍 **1. About the Project**

The **Farmer Assistance Website** provides farmers with essential tools to improve productivity and reduce risks.

### ✨ Key Features

* **🌦 Real-Time Weather Forecasting**
  Helps farmers plan activities based on temperature, humidity, rainfall, and 6-day forecasts.

* **🤖 AI-Based Crop Recommendation**
  Suggests the best crop based on soil nutrients, climate conditions, and environment data.

* **🛒 Farming Marketplace**
  A simple shop providing fertilizers, tools, pesticides, machinery, and essential farming supplies.

### 🚜 Real-World Use Cases

* Prevent crop loss by predicting sudden weather changes
* Improve yield using AI-based crop recommendations
* Easily purchase farming products online

---

## 🛠 **2. Technologies & Tools Used**

### **Frontend**

* HTML
* CSS
* Tailwind CSS
* JavaScript
  ✔ Fast, responsive, mobile-friendly UI.

### **Backend**

* **Flask (Python)**
  ✔ Lightweight, easy ML model integration.

### **Machine Learning**

* Scikit-learn
* Pretrained model using soil/climate datasets
  ✔ Predicts best crop using NPK, humidity, temperature, pH, rainfall.

### **Weather API**

* **OpenWeatherMap API**
  ✔ Provides realtime temperature, humidity, forecast, wind speed.

### **Database**

* SQLite / PostgreSQL
  ✔ Stores predictions, marketplace items, and user inputs.

### **Deployment**

* Flask server on cloud hosting
  ✔ Accessible to farmers in rural areas.

---

## 🤖 **3. AI Crop Recommendation System**

The ML model is trained on datasets containing:

* Nitrogen, Phosphorus, Potassium (NPK)
* Temperature & Humidity
* Rainfall
* Soil pH Value

### **Prediction Process**

1. User enters soil & climate values
2. Data is preprocessed using:

   * MinMaxScaler
   * StandardScaler
3. ML model predicts optimal crop
4. Crop dictionary maps prediction → real crop name

---

## 🌤 **4. Weather Forecasting System**

Using **OpenWeatherMap API**, the system provides:

### **Weather Data Provided**

* Current temperature
* Weather condition (rainy, cloudy, sunny)
* 6-day forecast
* Humidity
* Wind speed
* Visibility

---

## ⚠️ **5. Challenges Faced**

### 🔧 API Handling Issues

* Weather API rate limits
* Incorrect city names causing errors

### 🤖 ML Optimization

* Required scaling and transformation for accurate results

### 🧑‍🌾 UI/UX Simplicity

* Designed large buttons and a simple interface for easy use

### ✔ Solutions Implemented

* Debouncing API requests
* Better error handling
* Fallback messages

---

## 🧱 **6. Backend Architecture**

* Flask routes for crop prediction → `/predict`
* Weather endpoints to fetch forecasts
* SQLite/PostgreSQL database integration
* Machine learning model loaded using `pickle.load()`

### Trade-offs

* Flask chosen for simplicity; Node.js optional for large-scale scalability
* SQLite easy to set up; PostgreSQL recommended for production

---

## 📝 **7. Feedback System**

### ✔ Crop Prediction Feedback

Farmers can confirm or reject suggestions to improve future AI accuracy.

### ✔ Weather Feedback

Farmers can rate weather accuracy.

### ⭐ Future Plans

* Community discussion system
* Self-learning AI model

---

## 🖼 **Project Images**

*(Add your image links or upload images in your GitHub repo — I will format them once you share the URLs.)*

```md
![Homepage](images/homepage.png)
```

---

## 📦 **How to Run the Project**

```bash
# Clone the repo
git clone https://github.com/kunaladkine/kunaladkine/Farma-Crop-Recommendation-System.git


# Install dependencies
pip install -r requirements.txt

# Run Flask server
python app.py
```
---

If you want, I can also **format this into a PDF**, **generate badges**, or **insert your actual screenshots** into the README.

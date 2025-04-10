# 🌧️ Australian Cities Rainfall Prediction App

A weather prediction web application that forecasts the **next day's rainfall** for any Australian city using real-time weather data and a trained **machine learning model**. Built as part of a Hackathon by a passionate team of SU students 🧠💻

---

## 🧾 Project Overview

This project combines **OpenWeather API**, **Flask**, and **Scikit-learn ML models** to offer rainfall predictions based on user-input city names. The app features:

- Real-time weather data fetching
- Trained machine learning model for rainfall prediction
- Dynamic web interface for user interaction

---

## 👨‍💻 Team Composition

### 🧑‍🎓 First Year
- **Deepak Kumar** – Frontend/Backend
- **Hemant Meena** – Frontend/Backend
- **Akash Deep** – Frontend/Backend

### 🎓 Second Year
- **Narayan Jat** – Machine Learning Specialist
- **Pankaj Yadav** – Machine Learning Specialist

---

## 🔧 Project Workflow

### 1️⃣ Model Training
- ML model trained using historical weather data
- Features: temperature, humidity, pressure, wind speed, etc.
- Framework: **Scikit-learn**

### 2️⃣ Web Development
- Built using **Flask** for backend
- Frontend: **HTML, CSS, JS**
- API integration: **OpenWeather API**

### 3️⃣ Integration & Testing
- Combined all components into a single application
- Extensive testing for data accuracy and seamless user flow

---

## 📚 Libraries & Tools Used

- **Flask** – Python web framework
- **Requests** – To fetch data from OpenWeatherMap API
- **Joblib** – For loading trained ML models
- **Pandas** – For backend data manipulation
- **Scikit-learn** – Machine learning training & testing

---

## 🧠 Algorithm Overview

1. `index.html` serves as the homepage where the user enters a city name.
2. Input is validated to ensure correct format.
3. Real-time weather data is fetched using **OpenWeather API**.
4. Data is cleaned and prepared for prediction.
5. ML model predicts rainfall based on inputs.
6. Output is displayed to the user dynamically using `weather.html`.

---

## 💻 Features

- 🏙️ Input Australian city name
- 🌦️ Displays current temperature, humidity, wind, etc.
- 🌧️ Predicts rainfall for the next day
- ⚠️ Handles input errors and invalid city names

---

## 🧪 Test Cases

- Tested on multiple cities with diverse weather
- Handles both valid and invalid city entries gracefully
- Tested error handling for API failures

---

## 👥 Contributions

| Team Member   | Contributions |
|---------------|--------------|
| **Deepak Kumar** | Dynamic frontend rendering, Flask logic for weather data, error handling, OpenWeather API integration |
| **Hemant Meena** | Integrated Joblib for ML, backend optimization with Pandas, frontend performance tuning |
| **Akash Deep** | UI design with HTML/CSS, Flask routing, backend-frontend integration |
| **Narayan Jat** | ML model training & optimization |
| **Pankaj Yadav** | Dataset preprocessing, model testing & validation |

---

## ⚠️ Challenges Faced

- **Weather Data Variability** – Addressed with larger datasets and normalization
- **Model Accuracy** – Improved through fine-tuning and validation techniques
- **Integration Issues** – Resolved through iterative testing and debugging

---

## 🚀 Future Work

- Expand support for more cities globally 🌍
- Include real-time rainfall monitoring and hourly forecasts ⏱️
- Implement user feedback collection
- Explore advanced ML models like XGBoost or deep learning 📈

---

## 🎉 Conclusion

> Our Rainfall Prediction App successfully demonstrates the practical use of machine learning in real-world weather forecasting. We created a scalable, intuitive, and functional product — and learned a ton about teamwork, tech, and resilience along the way 💪🌧️

---

> *Made with ❤️ by SU Hackathon Team (2025)*


# ResQ Freeze – Smart Refrigerator Monitoring System

## 📌 Description
ResQ Freeze is an IoT-based smart refrigerator system designed to detect food spoilage and monitor environmental conditions in real-time. 
The system integrates hardware sensors with a backend API and a web-based dashboard to provide actionable insights for users.

---

## 🚀 Features
- Real-time temperature and humidity monitoring (DHT22)
- Gas detection for early indication of food spoilage
- REST API for data communication using FastAPI
- Web dashboard for real-time visualization
- Responsive and user-friendly interface
- End-to-end integration between IoT device, backend, and frontend

---

## 🛠️ Tech Stack
- Frontend: React (Vite)
- Backend: FastAPI (Python)
- IoT Device: ESP32
- Sensors: DHT22, Gas Sensor
- Communication: HTTP API (ESP32 → FastAPI)
- Database: MySQL

---

## 🏗️ System Architecture
ESP32 (Sensor Data) → FastAPI Backend → Database → React Dashboard

---

## 👨‍💻 My Contributions (Firli Hanifurahman)

- Developed **backend system using FastAPI** for handling IoT data processing
- Implemented **authentication system** including login, register, and session handling
- Integrated **Google OAuth authentication**
- Built **password reset system using OTP with email integration (Mailtrap)**
- Designed and implemented **API endpoints for user and sensor data**
- Processed and calculated **sensor data (temperature, humidity, gas) to determine food condition status**
- Implemented **access control to restrict unauthorized access to dashboard and monitoring pages**
- Integrated frontend with backend API for real-time data communication
- Assisted in UI improvements (navbar and layout adjustments)

---

## 🧠 Problem & Solution
**Problem:**
Food spoilage in refrigerators often goes unnoticed due to lack of monitoring, causing waste and potential health risks.

**Solution:**
ResQ Freeze uses environmental sensors and gas detection combined with real-time data processing to provide continuous monitoring and alerts through a web dashboard.

---

## 🎥 Demo Video
[![Watch Demo](https://img.youtube.com/vi/Zh4I_Q8mW_E/0.jpg)](https://www.youtube.com/watch?v=Zh4I_Q8mW_E)

---

## ⚙️ How to Run

### Backend (FastAPI)
```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload

# 📡 Real-Time IoT Data Streaming using Azure Stream Analytics

## 📅 Duration
**March 2024**

## 📌 Project Overview
This project demonstrates how to build a **real-time data streaming pipeline** using Microsoft Azure. By simulating IoT device data and processing it through Azure Stream Analytics, I created an end-to-end system for monitoring device telemetry and visualizing it live in Power BI.

## 🧰 Tools & Technologies
- **Azure IoT Hub**
- **Azure Stream Analytics**
- **Power BI**
- **IoT Simulator**
- **Azure Storage / Blob / Table**
- **SQL (Stream Analytics Query Language)**

## ⚙️ Key Steps & Features

### 🔧 Azure IoT Hub Setup
- Created and configured Azure IoT Hub to serve as the core communication platform for IoT devices
- Set security policies and selected appropriate pricing tiers
- Registered and authenticated new devices

### 🧪 Simulation & Testing
- Used an **IoT web simulator** to send real-time messages using the device **connection strings**
- Simulated various telemetry metrics without physical hardware

### 🔄 Azure Stream Analytics Pipeline
- Created a **Stream Analytics job** to process incoming data from the IoT Hub
- Wrote **input queries** to parse and transform incoming JSON payloads
- Configured **output queries** to send cleaned data to Power BI and/or Azure Storage

### 📊 Power BI Dashboard
- Built an interactive, real-time dashboard in **Power BI**
- Monitored key metrics (e.g., temperature, humidity, device ID, timestamps)
- Enabled real-time trend analysis and anomaly detection

## ✅ Outcome
- Successfully demonstrated a real-time data streaming pipeline using Azure
- Enabled live monitoring of IoT data without relying on physical devices
- Delivered a fully operational Power BI dashboard for immediate insights and decision-making

---

> This project reflects my hands-on experience with cloud-based IoT solutions, stream processing, and real-time analytics. It highlights how Azure can be leveraged to build scalable and intelligent IoT monitoring systems.


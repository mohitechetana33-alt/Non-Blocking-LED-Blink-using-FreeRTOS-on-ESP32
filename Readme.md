# 🚀 FreeRTOS ESP32 Non-blocking LED Blink Dashboard  

An **interactive simulation dashboard** showcasing **Non-Blocking LED Blink using FreeRTOS on ESP32**.  
This project combines **Embedded Systems + FreeRTOS + AI-powered visualization** to make learning real-time operating systems more engaging and practical.  

---

## ✨ Project Highlights
- 🔹 **Non-blocking LED Control** using FreeRTOS tasks (no delay blocking)  
- 🔹 **Real-time GPIO pin mapping** for ESP32 DevKit V1  
- 🔹 **Task monitoring panel** showing uptime, LED toggles, and cycles  
- 🔹 **Interactive controls**: Start / Stop / Reset simulation  
- 🔹 **Clean visualization** for better understanding of FreeRTOS concepts  

---
## wokwi simulation 
<img width="1900" height="967" alt="image" src="https://github.com/user-attachments/assets/59e0d530-ed69-4f52-a526-5ec750918e35" />

---

## 🛠️ Tech Stack
- **ESP32 DevKit V1**  
- **FreeRTOS** for real-time task scheduling  
- **Arduino Framework (C/C++)**  
- **HTML, CSS, JavaScript** for interactive dashboard  
- **AI-powered visualization concepts**  

---

## 📋 How It Works
1. FreeRTOS creates **three tasks**:  
   - `BlinkTask` → Toggles LED without blocking  
   - `SensorTask` → Simulates sensor readings  
   - `SerialTask` → Prints uptime & system info  
   
2. The **dashboard UI** displays:  
   - LED state (ON/OFF)  
   - GPIO pin visualization  
   - Uptime counter & task cycles  

3. Users can **control the simulation** using Start/Stop/Reset buttons.  

---


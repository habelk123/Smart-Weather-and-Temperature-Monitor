# ⛈️ Smart Weather & Temperature Display

This project displays the time in an accurate, real time manner as well as fetches local weather updates such as temperature and condition. Additionally, it utilizes a sensor to obtain the 
temperature and humidity data of room and display that as well. Lastly the component's were soldered onto a perfboard along with headers for the ESP32 and ILI9341 TFT display for a cleaner prototyped look.

## 🧰 Tool's:
 - ESP32 DevKit V1
 - ILI9341 TFT Display
 - DHT11 Temperature and Humidity Sensors
 - Jumper wires
 - Headers
 - Perfboard
 - Soldering Kit/Station

## 💻Languages/Frameworks:
 - C++ (Arduino Framework)

## 💡 Features:
 - Displays time using RTC on TFT
 - Displays weather info from OpenWeatherMap on TFT
 - Obtains temperature/humidity data to then format and display on TFT
 - Program structured through RTOS (task creation, dual-core architecture, task priority and latency)
 - Soldered components for a cleaner, prototyped look as well as potential for a 3D-Printed enclosure.

## ❔How to Run:
1. Download Arduino IDE --> [Arduino IDE](https://arduino.cc) (v2.0 or higher recommended)
2. Open the file `thermostat_project.ino` in Arduino IDE.
3. Connect your ESP32 board using a compatible USB cable
4. Go to **Library Manager**
5. Search for the following libraries and click **Install**:
   * *[ArduinoJson]*
   * *[Adafruit GFX Library]*
   * *[Adafruit ILI9341]*
   * *[DHT sensor library]*
6. Go to **Tools** > **Board** and select your specific board (e.g. *ESP32 Dev Module*).
7. Go to **Tools** > **Port** and select the COM port that corresponds to your connected board.
8. Click **Verify** to ensure the code can be compiled, then click **Upload** to flash the code.

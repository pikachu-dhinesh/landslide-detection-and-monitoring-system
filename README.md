# LANDSLIDE DETECTION AND MONITORING SYSTEM

## Project Overview

The Landslide Detection and Monitoring System is an IoT-based project designed to detect potential landslide conditions by monitoring soil moisture levels and ground vibrations in real time. The system uses an ESP32 microcontroller to collect sensor data and provide instant alerts through Telegram notifications, Blynk IoT platform, OLED display, LEDs, and a buzzer.

This project aims to enhance disaster preparedness and provide an early warning system for landslide-prone areas.

---

## Features

- Real-time soil moisture monitoring
- Ground vibration detection
- OLED display for live status updates
- Telegram alert notifications
- Blynk IoT dashboard integration
- LED indication system
- Buzzer warning alerts
- Wireless monitoring using Wi-Fi
- Early warning mechanism for landslide risks

---

## Technologies Used

- ESP32 Microcontroller
- Arduino IDE
- Embedded C/C++
- Blynk IoT Platform
- Telegram Bot API
- Wi-Fi Communication

---

## Hardware Components

- ESP32 Development Board
- Soil Moisture Sensor
- Vibration Sensor
- SH1106 OLED Display
- Buzzer
- Red LED
- Yellow LED
- Green LED
- Breadboard
- Jumper Wires
- Power Supply

---

## Software Libraries

```cpp
WiFi.h
BlynkSimpleEsp32.h
WiFiClientSecure.h
HTTPClient.h
Wire.h
Adafruit_GFX.h
Adafruit_SH110X.h
```

## System Workflow

1. ESP32 continuously reads soil moisture and vibration sensor values.
2. Sensor data is displayed on the OLED screen.
3. Data is sent to the Blynk IoT dashboard.
4. When abnormal conditions are detected:
   - LEDs indicate warning levels.
   - Buzzer activates.
   - Telegram notifications are sent.
5. Users can monitor the system remotely through Blynk and Telegram.

---

## Alert Conditions

### Safe State
- Normal soil moisture
- No vibration detected
- Green LED ON

### Warning State
- High soil moisture detected
- Yellow LED ON

### Danger State
- High moisture and vibration detected
- Red LED ON
- Buzzer activated
- Telegram alert sent

---

## Applications

- Landslide-prone regions
- Hill stations
- Mountain roads
- Construction sites
- Mining areas
- Disaster management systems
- Environmental monitoring

---

## Future Enhancements

- GPS Location Tracking
- Rainfall Monitoring Sensor
- Cloud Data Storage
- Mobile Application Integration
- Machine Learning-Based Prediction
- SMS Alert System

---

## Project Outcome

This system provides an affordable and efficient solution for monitoring environmental conditions that may lead to landslides. By combining IoT technology with real-time alert mechanisms, the project helps improve safety and disaster preparedness.

---

## Authors

- Dhinesh G G
- Project Team Members

---

## License

This project is developed for academic and educational purposes.

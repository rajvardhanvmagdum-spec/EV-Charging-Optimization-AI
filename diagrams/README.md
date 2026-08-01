# Diagrams

Project diagrams will be stored here.

              Dashboard
                  │
         Spring Boot Backend
                  │
         ┌────────┴────────┐
         │                 │
      MySQL            AI Model
         │                 │
         └────────┬────────┘
                  │
              WiFi/MQTT
                  │
                ESP32
                  │
      ┌───────────┴───────────┐
 Charging Port 1         Charging Port 2
      │                       │
      |                       |
 Relay + Sensor         Relay + Sensor
      │                       │
      |                       |
 RFID Reader                OLED

## system architecture 


EV User
   ↓
RFID Scan
   ↓
ESP32
   ↓
Current & Voltage Sensors
   ↓
WiFi/MQTT
   ↓
Spring Boot Backend
   ↓
MySQL Database
   ↓
AI Model
   ↓
Decision
   ↓
ESP32
   ↓
Relay
   ↓
Charging Port 1 / Charging Port 2


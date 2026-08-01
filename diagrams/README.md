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
 Relay + Sensor         Relay + Sensor
      │                       │
 RFID Reader        OLED / LEDs / Buzzer

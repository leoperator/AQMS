# AQMS

### Air Quality Monitoring System

<img width="1073" height="881" alt="image" src="https://github.com/user-attachments/assets/92339096-a441-4224-baeb-f2a5b979270b" />

##  Overview

AQMS is a low-cost, portable, IoT-based Air Quality Monitoring System that leverages the ESP32 microcontroller and a suite of environmental sensors to detect air pollutants in real time. It calculates the Air Quality Index (AQI) and uploads data to ThingSpeak Cloud every 15 seconds. The system also features a live OLED display and a compact custom-designed PCB for seamless integration.

##  Features
-  Real-time monitoring of PM2.5, CO, NO₂, TVOCs, Temperature & Humidity
-  Wi-Fi enabled data transmission to ThingSpeak
-  OLED display for on-device monitoring
-  Powered by a rechargeable 3.7V Li-Po battery
-  Dynamic AQI calculation and category display
-  Compact and modular PCB design using KiCad

##  Tech Stack / Hardware Used

| Category | Components / Tools |
| :--- | :--- |
|  Microcontroller | ESP32 (dual-core, built-in Wi-Fi) |
|  PM2.5 Sensor | Winsen ZPH02 |
|  CO Sensor | MQ-7 |
|  NO2 Sensor | DFRobot MEMS |
|  TVOC Sensor | Winsen ZP07-MP503 |
|  Temp/Humidity | DHT22 (AM2302) |
|  Display | 0.96" OLED |
|  Power | Li-Po 3.7V Battery + MT3608 Boost Converter |
|  PCB Design Tool | KiCad |
|  Cloud Platform | ThingSpeak |
|  IDE | Arduino IDE |


##  Project Gallery

### PCB Layout
 <img width="664" height="547" alt="image" src="https://github.com/user-attachments/assets/395fb62c-4077-49dd-92a4-149451a598ee" />


### Schematic
<img width="831" height="401" alt="image" src="https://github.com/user-attachments/assets/4259f575-5325-46f9-a4e9-ee445d7b4884" />

### Front View
<img width="4032" height="3024" alt="image" src="https://github.com/user-attachments/assets/9e8e5f72-940d-4a7b-98ea-bf17a60b7712" />


### Back View
<img width="3024" height="4032" alt="image" src="https://github.com/user-attachments/assets/6f796b08-8981-4c49-ab4a-562c41d9ac05" />


### 3D View
<img width="760" height="736" alt="image" src="https://github.com/user-attachments/assets/b7a2c5a1-1b1b-4486-bb76-14e7f4b7e7d1" />

### ThingSpeak Dashboard
<img width="796" height="794" alt="image" src="https://github.com/user-attachments/assets/4d01d6ab-d2b9-4a35-984c-e2ba14e98b4e" />

##  PCB Files

All design and manufacturing files are in the PCB/ folder:

-  ```AQMS.kicad_pcb``` — PCB layout
-  ```AQMS.sch``` — Schematic
-  ```Gerber.zip``` — Ready to upload to PCB fab site

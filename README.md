# LoRa Project: Runway signal control using RYLR998

## Overview  
This project demonstrates how to use LoRa technology to control relays remotely with Arduino and ESP8266. It leverages LoRa communication modules to enable long-distance relay control, making it ideal for home automation, IoT, and other wireless control applications.

---

## Features  
- **Long-Range Wireless Communication:** Uses LoRa modules for reliable communication over long distances.  
- **Arduino & ESP8266 Integration:** Combines the power of Arduino microcontrollers with ESP8266 for network connectivity.  
- **Relay Control:** Efficiently controls multiple relays for various electrical devices.  
- **Low Power Consumption:** Optimized for energy-efficient operation.  
- **Customizable:** Code and hardware design are modular for easy customization.  

---

## Components Required  
- **LoRa Modules (e.g., Lora Module REYAX RYLR998)**  
- **Arduino (e.g., Uno, Nano)**  
- **ESP8266 or NodeMCU**  
- **Relay Modules**  
- **Power Supply**  
- **Connecting Wires and Breadboard**  

---

## How It Works  
1. **LoRa Communication:** The LoRa transmitter (connected to Arduino) sends commands to the receiver module.  
2. **ESP8266 Integration:** The ESP8266 facilitates communication with a mobile app or web interface for controlling relays.  
3. **Relay Control:** The LoRa receiver processes commands and triggers the respective relay switches.  

---

## Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/MuhammadAbdullahGhazi/Runway_Signal_Control_Using_RYLR_998.git
   ```  
2. Install the required Arduino libraries:  
   - LoRa by Sandeep Mistry  
   - ESP8266WiFi  
3. Upload the appropriate code to the Arduino and ESP8266 using the Arduino IDE.  

---

## Wiring Diagram  
Refer to the `wiring-diagram.png` file in the repository for detailed connections between Arduino, LoRa modules, relays, and ESP8266.  

---

## Usage  
1. Power up the LoRa transmitter and receiver circuits.  
2. Use the provided mobile app or web interface to send relay control commands.  
3. Observe the relay status changes based on the commands sent.  

---

## Project Files  
- `Code_NodeMCU_Lora_TX_feedback_07`: Code for Arduino-based LoRa transmitter.  
- `Code_ArduinoUNO_LoRa_4Relay_Switch_EEPROM_feedback_07`: Code for Arduino-based LoRa receiver.  
- `wiring-diagram.png`: Circuit diagram for hardware connections.  

---

## Contributing  
Contributions are welcome! If you have ideas for improvement or additional features, feel free to open an issue or submit a pull request.  

---

## License  
This project is licensed under the [MIT License](LICENSE).  

---

## Acknowledgments  
- [Hackaday Project Page](https://hackaday.io/project/184826-lora-project-arduino-esp8266-control-relays-2022)  
- LoRa and IoT communities for inspiration and resources.  

---

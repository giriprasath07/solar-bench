# Smart Solar Bench

A sustainable **smart bench powered by solar energy**.  
The system uses 3 × 35W solar panels to charge a 12V battery via a PWM charge controller.  
Stored energy powers 12V DC bulbs for lighting and USB charging ports for devices.  
Optional ESP32 integration enables real-time IoT monitoring.

---

## ⚡ Features
- 3 × 35W solar panels (total 105W peak power)
- PWM solar charge controller for safe charging
- 12V 12Ah DC battery storage
- 12V DC LED bulbs for lighting
- Dual USB charging ports
- Expandable with ESP32 for:
  - Battery voltage monitoring
  - Power usage tracking
  - Cloud integration (Firebase/Blynk)

---

## 🛠️ Components
- 3 × Solar Panels (35W each)
- 12V 12Ah DC Battery
- PWM Solar Charge Controller
- 12V DC Bulbs
- USB Charging Ports
- (Optional) ESP32 microcontroller

---

## 📂 Project Structure
```
docs/                    
 ├── circuit-diagram.jpg   # Wiring diagram
 └── architecture.md       # Explanation of system flow
src/                     
 └── esp32_monitor.ino     # Optional ESP32 IoT monitoring code
README.md
LICENSE
requirements.txt           # If Python used for monitoring scripts
```

---

## 📈 System Architecture
1. Solar panels generate DC power (105W peak).
2. PWM Solar Charge Controller regulates charging.
3. 12V 12Ah Battery stores energy safely.
4. Loads powered:
   - 12V DC LED bulbs
   - USB Charging Ports (via 12V → 5V step-down).
5. Optional ESP32 adds smart monitoring and data logging.

---

## 🚀 Future Enhancements
- ESP32 IoT system for real-time solar and battery monitoring.
- Mobile app for usage analytics and notifications.
- WiFi hotspot integration for smart city environments.
- Larger battery for extended usage.

---

## 📜 License
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

# 🚨 AlertAxis
### Intelligent Tunnel Monitoring and Multi-Hazard Safety System

**Intelligent Monitoring. Resilient Infrastructure. Safer Tunnels.**

## About the Project

AlertAxis is an IoT-based tunnel monitoring and safety system aimed at improving tunnel safety through continuous environmental monitoring and intelligent hazard assessment.

The project explores the integration of embedded systems, sensor networks, and an operations dashboard to monitor potentially hazardous conditions within tunnels.

The proposed system focuses on identifying multiple hazard categories, including fire and smoke, water accumulation and flooding, and structural disturbances such as landslides and rockfalls.

## Key Areas of Focus

- Multi-hazard environmental monitoring.
- ESP32-based sensor data acquisition.
- Sensor-based hazard assessment.
- Risk-level classification and alert generation.
- Centralized tunnel operations dashboard.
- Exploration of AI-assisted monitoring and predictive analytics.

## Current Prototype

The initial hardware simulation explores an ESP32-based monitoring node with the following components:

| Component | Purpose |
|---|---|
| ESP32 | Sensor data acquisition and processing |
| DHT22 | Temperature and humidity monitoring |
| MQ2 | Gas and smoke input |
| Water-level sensor | Water accumulation monitoring |
| Vibration sensor | Structural disturbance input |
| Rain sensor | Rainfall input |
| LED | Visual indication |
| Buzzer | Audible hazard alert |

The simulation also includes an experimental weighted risk-scoring approach to classify tunnel conditions into NORMAL, WARNING, and CRITICAL levels.

## Project Resources

| Resource | Link |
|---|---|
| Operations Dashboard Design | [View Figma Prototype](https://www.figma.com/make/gLLMvrQ9yjzBwxTdmA07Y5/AlertAxis-Operations-Dashboard?t=EbwmvsgoJKapLvil-1&preview-route=%2F%23analysis) |
| ESP32 Hardware Simulation | [Explore Wokwi Project](https://wokwi.com/projects/477487143821102081) |
| Project Documentation and Files | [Google Drive](https://drive.google.com/drive/folders/1K-WcENw3kNk3tjDH5XSGSNqXKWT6VmcT?usp=sharing) |

## Technology Stack

- **Embedded Systems:** ESP32
- **Sensors:** DHT22, MQ2, water-level, vibration and rain sensors
- **Simulation:** Wokwi
- **Dashboard Design:** Figma
- **Programming:** Arduino/C++

## Future Development

- Integration and validation of multiple sensor modules.
- Improved multi-hazard assessment.
- Real-time communication between monitoring nodes and dashboard.
- AI-assisted anomaly detection.
- Automated notification mechanisms.
- Exploration of self-healing communication networks.
- Digital twin-based tunnel monitoring.

## Project Status

**Under Development**

AlertAxis is currently in its prototyping and development phase. Hardware simulation, dashboard design, and system-level integration are part of the ongoing development process.

---

*An engineering initiative towards safer and smarter tunnel infrastructure.*

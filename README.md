# 🚨 AlertAxis
### An AI-Based Multi-Hazard Tunnel Safety and Resilience Platform

<p align="center">
  <b>Computer Vision • Edge AI • Digital Twin • Self-Healing Network • 5G Connectivity</b>
</p>

<p align="center">
  <i>India builds the tunnels. We build the intelligence inside them.</i>
</p>

<p align="center">
  <b>Predict • Protect • Coordinate • Respond</b>
</p>

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Problem Statement](#-problem-statement)
- [Our Solution](#-our-solution)
- [Key Features](#-key-features)
- [Multi-Hazard Monitoring](#-multi-hazard-monitoring)
- [System Architecture](#-system-architecture)
- [Decision and Response Pipeline](#-decision-and-response-pipeline)
- [Hardware Components](#-hardware-components)
- [AI and Intelligent Analytics](#-ai-and-intelligent-analytics)
- [Self-Healing Network](#-self-healing-network)
- [Digital Twin](#-digital-twin)
- [Operations Dashboard](#-operations-dashboard)
- [Edge-Case Handling](#-edge-case-handling)
- [Technology Stack](#-technology-stack)
- [Prototype Cost Estimation](#-prototype-cost-estimation)
- [Project Resources](#-project-resources)
- [Development Roadmap](#-development-roadmap)
- [Current Status and Limitations](#-current-status-and-limitations)
- [Team](#-team)

---

## 🌐 Overview

**AlertAxis** is an AI-based multi-hazard tunnel safety and resilience platform designed to improve situational awareness, hazard assessment, and emergency response in tunnel environments.

As tunnel infrastructure continues to expand, incidents involving fire, smoke, flooding, landslides, rockfalls, and structural disturbances present significant safety challenges. Conventional monitoring approaches often depend on isolated detection mechanisms and may lack integrated situational awareness and coordinated emergency response capabilities.

AlertAxis explores the integration of IoT-based sensing, edge computing, computer vision, AI-driven analytics, digital twin technology, and resilient communication networks to create an intelligent tunnel monitoring ecosystem.

The platform aims to move beyond reactive hazard detection towards predictive risk assessment, adaptive monitoring, and coordinated emergency management.

### Core Vision

To transform conventional tunnels into intelligent, connected, and resilient infrastructure capable of identifying emerging hazards, assessing risks, and supporting faster emergency response.

---

## ⚠️ Problem Statement

Tunnel environments present unique safety challenges due to restricted accessibility, limited visibility, complex environmental conditions, and communication constraints.

Hazards such as fire outbreaks, smoke accumulation, flash flooding, gas leaks, landslides, and structural failures can escalate rapidly if not identified and addressed in time.

Existing monitoring approaches may face limitations such as:

- **Unpredictable Hazards:** Multiple hazards can occur simultaneously or without warning.
- **Delayed Awareness:** Late identification of dangerous conditions can increase emergency response time.
- **Communication Gaps:** Tunnel environments can create challenges for reliable wireless communication.
- **Complex Emergency Coordination:** Multiple agencies must coordinate during emergencies under uncertain conditions.

There is a need for an integrated monitoring platform that combines real-time sensing, intelligent analysis, resilient communication, and centralized emergency coordination.

---

## 💡 Our Solution

AlertAxis proposes a unified intelligence framework that integrates multiple monitoring and decision-making mechanisms.

The proposed system consists of:

1. **Multi-Hazard Monitoring:** Continuous acquisition of environmental, structural, and visual information.
2. **AI Prediction Engine:** Sensor fusion, hazard prediction, risk scoring, and event classification.
3. **Self-Healing Network:** Adaptive communication mechanisms to maintain network availability during failures.
4. **Adaptive Digital Twin:** A virtual representation of tunnel conditions for visualization and monitoring.
5. **Intelligent Emergency Coordination:** Decision support, multi-agency alerts, and resource coordination.
6. **Dynamic Evacuation Intelligence:** Evacuation route planning, safe-exit guidance, and crowd movement monitoring.

The overall objective is to create a connected safety framework that supports the complete process from hazard identification to emergency response.

---

## ✨ Key Features

| Feature | Description |
|---|---|
| Multi-Hazard Monitoring | Monitors multiple environmental and structural hazards |
| AI-Based Prediction | Explores predictive hazard assessment using sensor data |
| Sensor Fusion | Combines information from multiple sensing sources |
| Risk Assessment | Classifies tunnel conditions according to assessed risk |
| Digital Twin | Provides a virtual representation of tunnel conditions |
| Self-Healing Network | Explores automatic communication recovery and rerouting |
| Intelligent Alerts | Supports prioritized hazard notifications |
| Emergency Coordination | Designed to support coordinated multi-agency response |
| Edge Intelligence | Enables local processing and preliminary hazard assessment |

---

## 🔥 Multi-Hazard Monitoring

AlertAxis focuses on three primary hazard categories.

### 1. Fire and Smoke Detection

Fire incidents can rapidly affect visibility, air quality, and tunnel safety.

**Monitoring parameters:**

- Smoke concentration
- Temperature variations
- Flame detection
- Carbon monoxide (CO)
- Carbon dioxide (CO₂)
- Camera-based visual monitoring

**Proposed functionality:**

- Identify abnormal smoke and temperature conditions.
- Monitor potential fire-related events.
- Combine sensor readings with visual information.
- Generate appropriate hazard alerts.

### 2. Flash Flooding Detection

Water accumulation and sudden flooding can make tunnel sections unsafe and disrupt transportation.

**Monitoring parameters:**

- Water level
- Water flow
- Rainfall
- Drainage and pump status

**Proposed functionality:**

- Monitor water accumulation.
- Identify abnormal water-level changes.
- Track drainage conditions.
- Support early flood warnings.

### 3. Landslide and Rockfall Detection

Structural disturbances and surrounding ground movement can create serious risks in tunnel environments.

**Monitoring parameters:**

- Soil moisture
- Vibration
- Tilt
- Geophone readings
- Camera-based monitoring

**Proposed functionality:**

- Monitor unusual vibration patterns.
- Identify changes in tilt and ground conditions.
- Track potential structural disturbances.
- Support early identification of abnormal conditions.

---

## 🏗️ System Architecture

AlertAxis follows a layered architecture that connects distributed sensing devices with edge processing, AI analytics, communication infrastructure, and a centralized monitoring platform.

### Five-Layer Architecture

| Layer | Description | Key Technologies |
|---|---|---|
| Layer 1 – Perception | Collects environmental and visual data | Cameras, sensors |
| Layer 2 – Edge Intelligence | Processes and filters sensor information | ESP32, Raspberry Pi |
| Layer 3 – AI Analytics | Performs hazard detection and risk assessment | OpenCV, YOLO, Random Forest |
| Layer 4 – Communication | Transfers monitoring and analytics data | MQTT, 5G |
| Layer 5 – Application | Provides visualization, decision support, and alerts | Digital Twin, MATLAB App Designer |

### Layer 1: Perception Layer

Responsible for acquiring information from the tunnel environment.

- Captures visual information through cameras.
- Collects temperature, smoke, gas, and water-level readings.
- Monitors rainfall and vibration.
- Transfers acquired information to the processing layer.

### Layer 2: Edge Intelligence Layer

Responsible for preliminary data processing and local operations.

- Aggregates sensor inputs.
- Performs edge preprocessing.
- Executes local control logic.
- Prepares information for further analysis.

### Layer 3: AI Analytics Layer

Responsible for intelligent hazard assessment.

- Processes sensor and visual information.
- Explores computer vision-based incident detection.
- Performs sensor fusion.
- Generates risk scores and hazard classifications.

### Layer 4: Communication Layer

Responsible for communication between distributed monitoring nodes and the centralized platform.

- Transfers sensor and analytics information.
- Explores MQTT-based messaging.
- Investigates low-latency communication using 5G.
- Supports reliable data transmission and remote monitoring.

### Layer 5: Application Layer

Provides the interface for tunnel monitoring and emergency decision support.

- Visualizes tunnel conditions.
- Displays hazard locations and risk levels.
- Presents alerts and system information.
- Supports decision-making and emergency coordination.

---

## 🔄 Decision and Response Pipeline

AlertAxis follows a continuous monitoring and response workflow.

| Stage | Process | Description |
|---|---|---|
| 01 | Sense the Tunnel | Acquires environmental and visual information |
| 02 | Understand the Situation | Processes sensor readings and identifies abnormal conditions |
| 03 | Predict and Map Risk | Evaluates potential hazards and their impact |
| 04 | Decision Intelligence | Assesses risk and supports response decisions |
| 05 | Emergency Response | Supports evacuation, alerts, and coordinated intervention |
| 06 | Continuous Monitoring | Updates tunnel conditions and tracks changes |

The proposed decision intelligence engine connects monitoring, AI analysis, digital twin visualization, and emergency coordination into a unified workflow.

---

## 🔌 Hardware Components

The proposed prototype architecture uses embedded processing devices, environmental sensors, and supporting electronic components.

| Component | Specification | Purpose |
|---|---|---|
| Raspberry Pi 4 | 4 GB RAM | Edge computing and processing |
| ESP32 | Development board | Distributed sensor interfacing |
| MQ-2 | Gas sensor module | Smoke and combustible gas sensing |
| DHT22 | Temperature and humidity sensor | Environmental monitoring |
| Camera | Pi Camera v2 / USB webcam | Visual monitoring |
| Relay Module | 4-channel, 5 V | Control interface |
| WS2812B | Addressable LED strip | Visual status indication |
| Power Adapter | 5 V, 3 A | Power supply |
| MicroSD Card | 32 GB / 64 GB | Local storage |

Additional sensors such as water-level, vibration, rainfall, tilt, and soil-moisture sensors are considered for the broader multi-hazard monitoring framework.

### Embedded Monitoring Prototype

An ESP32-based monitoring node is being explored through a Wokwi simulation.

The current simulation includes:

- ESP32 microcontroller
- DHT22 temperature and humidity sensor
- MQ-2 gas/smoke input
- Water-level input
- Vibration input
- Rain sensor input
- LED indicators
- Buzzer-based alerts

An experimental risk-scoring mechanism is also explored to classify monitoring conditions into NORMAL, WARNING, and CRITICAL states.

---

## 🤖 AI and Intelligent Analytics

The AI analytics framework is intended to improve hazard identification and risk assessment by combining information from multiple sensing sources.

### Computer Vision

The proposed computer vision module explores:

- Visual monitoring of tunnel conditions.
- Identification of visible incidents.
- Detection of abnormal visual patterns.
- Incident localization.

**Technologies under consideration:** OpenCV and YOLO.

### AI-Based Sensor Fusion

Sensor fusion aims to combine information from multiple sensors to improve the reliability of hazard assessment.

The proposed framework explores Random Forest-based analysis to combine sensor information and support event classification.

### Risk Assessment Engine

The risk assessment engine is intended to:

- Evaluate incoming sensor information.
- Identify abnormal conditions.
- Calculate risk scores.
- Classify hazard severity.
- Support appropriate alert generation.

The exact models, thresholds, and classification logic require further development and validation.

---

## 🌐 Self-Healing Network

Reliable communication is essential for tunnel safety monitoring, particularly during emergencies.

AlertAxis explores a self-healing communication architecture designed to maintain network availability during communication failures.

### Proposed Mechanisms

- **Fault Detection:** Identify failed nodes or communication links.
- **Automatic Rerouting:** Explore alternate communication paths.
- **Redundant Paths:** Maintain alternative routes for data transmission.
- **Store-and-Forward:** Temporarily buffer information when connectivity is unavailable.
- **Network Health Monitoring:** Monitor node availability and communication status.

The objective is to improve communication resilience and reduce the impact of individual node or link failures.

---

## 🏙️ Digital Twin

The proposed Adaptive Digital Twin acts as a virtual representation of tunnel conditions.

It aims to synchronize information from the monitoring infrastructure to provide a centralized view of the tunnel environment.

### Intended Capabilities

- Live tunnel condition visualization.
- Hazard location representation.
- Sensor health monitoring.
- Risk heat-map visualization.
- Monitoring of changing environmental conditions.
- Support for predictive simulation and response planning.

The digital twin is intended to connect physical sensor information with a virtual monitoring environment.

---

## 🖥️ Operations Dashboard

The AlertAxis Operations Dashboard is designed as a centralized interface for monitoring tunnel conditions and presenting safety-related information.

### Design Objectives

- Display tunnel monitoring information.
- Visualize hazard conditions and risk levels.
- Present sensor and system status.
- Support operator awareness.
- Provide a foundation for emergency decision support.

**Dashboard Design:** [View AlertAxis Operations Dashboard on Figma](https://www.figma.com/make/gLLMvrQ9yjzBwxTdmA07Y5/AlertAxis-Operations-Dashboard?t=EbwmvsgoJKapLvil-1&preview-route=%2F%23analysis)

The current dashboard design is available as a Figma prototype. Integration with live hardware data and backend services remains part of the development process.

---

## 🛡️ Edge-Case Handling

AlertAxis considers multiple failure scenarios that could affect the reliability of tunnel monitoring.

| Failure Scenario | Proposed Handling Mechanism |
|---|---|
| Sensor Failure | Multi-sensor fusion, sensor health monitoring, and degraded sensor isolation |
| Communication Loss | Self-healing network, alternate routing, and store-and-forward |
| False Alarms | Multi-sensor corroboration and context-aware validation |
| Human Error | Decision support and contextual operating procedures |
| Edge Node Crash | Watchdog-based recovery and UPS backup |
| Extreme Disaster | Priority routing and safe-state operation |

These mechanisms form part of the proposed resilience framework and require implementation and testing.

---

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Microcontrollers | ESP32 |
| Edge Computing | Raspberry Pi 4 |
| Programming | C/C++, Python |
| Hardware Simulation | Wokwi |
| Dashboard Design | Figma |
| Communication | MQTT, Wi-Fi, proposed 5G integration |
| Computer Vision | OpenCV, YOLO |
| Machine Learning | Random Forest |
| Visualization | MATLAB App Designer |
| Digital Twin | Proposed virtual tunnel monitoring environment |

*The technology stack represents the proposed architecture and current development tools; not every technology has been integrated into the working prototype.*

---

## 💰 Prototype Cost Estimation

The following table represents the preliminary prototype budget.

| No. | Component | Quantity | Estimated Cost (₹) |
|---|---|---:|---:|
| 1 | Raspberry Pi 4 (4 GB) | 1 | 4,500 |
| 2 | ESP32 Development Board | 2 | 900 |
| 3 | MQ-2 Smoke Sensor | 2 | 360 |
| 4 | DHT22 Temperature Sensor | 2 | 500 |
| 5 | Camera Module / Webcam | 1 | 1,200 |
| 6 | 4-Channel Relay Module | 1 | 200 |
| 7 | WS2812B LED Strip | 2 | 700 |
| 8 | Power Adapter | 2 | 600 |
| 9 | MicroSD Card | 1 | 500 |
| 10 | Breadboard and Jumper Wires | 1 | 400 |
| 11 | Enclosure / Tunnel Model | 1 | 1,000 |
| 12 | Cloud / Server / Hosting | 1 | 1,500 |
| 13 | Miscellaneous | 1 | 1,000 |
| | **Total** | | **₹13,360** |

*These are preliminary estimated costs for the proposed prototype, not verified final procurement costs.*

---

## 🔗 Project Resources

| Resource | Link |
|---|---|
| ESP32 Hardware Simulation | [Open Wokwi Simulation](https://wokwi.com/projects/477487143821102081) |
| Operations Dashboard | [Open Figma Prototype](https://www.figma.com/make/gLLMvrQ9yjzBwxTdmA07Y5/AlertAxis-Operations-Dashboard?t=EbwmvsgoJKapLvil-1&preview-route=%2F%23analysis) |
| Project Documentation | [Google Drive](https://drive.google.com/drive/folders/1K-WcENw3kNk3tjDH5XSGSNqXKWT6VmcT?usp=sharing) |

---

## 🚀 Development Roadmap

- [x] Initial project concept and architecture design
- [x] Multi-hazard monitoring framework
- [x] Operations dashboard design prototype
- [x] Initial ESP32 hardware simulation
- [ ] Complete multi-sensor integration
- [ ] Validate hazard assessment and risk classification
- [ ] Develop backend data acquisition and processing
- [ ] Integrate real-time sensor data with the dashboard
- [ ] Implement AI-assisted hazard analytics
- [ ] Develop and validate self-healing communication mechanisms
- [ ] Develop digital twin integration
- [ ] Perform system-level testing and validation

---

## 📌 Current Status and Limitations

**Project Status: Under Development**

AlertAxis is currently in its design and prototyping phase.

The available work includes an initial ESP32-based Wokwi simulation, an operations dashboard design prototype, and a proposed multi-layer system architecture.

The broader AI analytics, self-healing communication, digital twin, and emergency coordination capabilities represent ongoing development directions.

Further hardware integration, software implementation, sensor calibration, and real-world validation are required before the complete platform can be considered operational.

---

## 👥 Team

**Team AlertAxis**

Symbiosis Institute of Technology, Pune

- Dhakshayini Usha R
- Mishree Kalaria

**Domain:** Electronics & Telecommunication Engineering

**Focus Areas:** Embedded Systems • IoT • Intelligent Monitoring • Systems Integration

---

<p align="center">
  <b>ALERTAXIS</b>
  <br/>
  <i>Predict • Protect • Coordinate • Respond</i>
  <br/><br/>
  Building intelligence into tunnel infrastructure.
</p>

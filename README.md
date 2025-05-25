# Smart Energy Monitoring with IoT

A project developed as part of the "Communications et Technologies IoT" course at Université Paris-Saclay (M2 Informatique IoT), supervised by Dr. Ines Ahriz.

## 📌 Objective

Design and propose an IoT-based architecture that enables manufacturers to monitor and optimize the energy consumption of industrial machines in real time, contributing to Industry 4.0 goals.

## 🔍 Context

- In France, industry accounts for 25% of energy consumption and ~20% of GHG emissions.
- Poor visibility on machine-level consumption leads to inefficiencies, increased costs, and environmental impact.
- Regulatory pressure and carbon neutrality goals require better monitoring tools.

## 🛠️ Proposed Architecture

### 1. **Smart Meters**
- Measure energy use in real-time.
- Use protocols like Modbus, MQTT, BACnet, etc.

### 2. **PLC (Programmable Logic Controllers)**
- Control and process machine data.
- Example: Siemens S7, Schneider Modicon.

### 3. **Gateway**
- Collect and preprocess data.
- Transmit to cloud/local servers via MQTT, LoRaWAN, HTTP.

### 4. **Cloud/Local Server**
- Store and analyze data.
- Platforms: AWS IoT, Azure IoT, or local servers.

### 5. **User Interface**
- Web or mobile dashboards.
- Display real-time graphs, trends, and alerts.

## 🔐 Functional Requirements

- **Security**: authentication, encryption (TLS/SSL), role management.
- **Availability**: high availability, disaster recovery, hot updates.
- **Accessibility**: multi-device access, open APIs, system interoperability.

## 🧠 Future Enhancements

- Integration of AI and Machine Learning:
  - Predictive maintenance
  - Consumption pattern detection
  - Autonomous adjustments to optimize efficiency

## 📚 Documentation

- [Rapport PDF](./TOPIC_1_COMM_IOT_Rapport.pdf) — Full technical report
- [Presentation PDF](./Topic%201%20tech%20et%20com%20IoT.pdf) — Slide deck

## 👥 Authors

- Ahmad Hussein  
- Menna Khaled Salim

## 🎓 Institution

Université Paris-Saclay – Master 2 Informatique IoT  
Course: Communications et Technologies IoT  

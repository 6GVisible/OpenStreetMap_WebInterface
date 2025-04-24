# ConnectiCar V2 – Rahti2

This repository contains the **Rahti2** deployment section of the **ConnectiCar V2** project. It includes configuration files, credentials, deployment scripts, and supporting documentation.

### **Grafana**
- OpenShift-compatible configuration for deploying a Grafana.
- Used for real-time data visualization from InfluxDB.

### **InfluxDB**
- OpenShift-compatible configuration for deploying a InfluxDB.
- Time-series database configured for storing CAN bus data.

### **Mosquitto**
- OpenShift-compatible configuration for deploying a Mosquitto.
- MQTT broker for receiving and routing real-time messages.

### **Telegraf**
- OpenShift-compatible configuration for deploying a Telegraf.
- Agent for collecting and forwarding metrics to InfluxDB.
-
### **NodeJScripts**
- Scripts for OpenStreetMap

### **Manual**
- Word document detailing deployment steps, usage, and configuration in Rahti2 environment.

---

## Security Notice – `Credentials/` 

> ⚠️ **IMPORTANT SECURITY WARNING**

The `Credentials/` directory contains **administrator-level username, passwords and API Tokens** in plaintext for all services.
The credentials have been added to this private repository at the client's request.

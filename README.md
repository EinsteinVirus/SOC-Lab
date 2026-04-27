# Virtual SOC Lab: Threat Detection & Attack Simulation

A functional, virtualized Security Operations Center (SOC) lab built to bridge the gap between offensive and defensive cybersecurity. This environment mimics an enterprise network, enabling the simulation of cyberattacks and real-time monitoring of system telemetry through an industry-standard SIEM platform.

## 🏗️ Architecture
The lab is built on **VMware Workstation** and consists of three primary virtual machines:

* **SIEM Hub (Ubuntu + Wazuh):** The central brain that collects, indexes, and analyzes security logs.
* **Victim Endpoint (Windows 11):** An endpoint configured with a **Wazuh Agent** to generate high-fidelity telemetry and system logs.
* **Attacker Node (Kali Linux):** An offensive workstation used to execute attack vectors and test detection capabilities.

## 🚀 Features
* **Log Aggregation:** Centralizing event data from Windows into a Linux-based SIEM.
* **EDR Deployment:** Hands-on experience installing and configuring security agents.
* **Attack Simulation:** Executing techniques to trigger alerts and analyze Indicators of Compromise (IOCs).
* **Dashboards:** Real-time visualization of security events and system health.

## 🛠️ Tools & Technologies
* **Hypervisor:** VMware Workstation
* **SIEM/EDR:** Wazuh
* **OS:** Windows 11, Kali Linux, Ubuntu
* **Networking:** Virtual NAT Networking

## 📈 Learning Outcomes
* Understanding the lifecycle of a cyberattack.
* Configuring security monitoring for Windows endpoints.
* Navigating and managing an open-source SIEM.
* Troubleshooting cross-platform virtual network communications.

---
*Created as part of my practical exploration into cybersecurity infrastructure.*

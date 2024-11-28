# 🚗 **Enhancing Service Excellence in Vehicular Ad Hoc Networks (VANETs)**  

Welcome to the repository for our research project **"Enhancing Service Excellence in Vehicular Ad Hoc Networks (VANETs)."** This project explores the potential of QoS (Quality-of-Service) protocols in improving data exchange reliability, road safety, and traffic management in VANETs through innovative techniques like the **Enhanced AODV (ENAODV)** protocol.

---

## 📋 **Table of Contents**  

1. [Introduction](#introduction)  
2. [Features](#features)  
3. [Methodology](#methodology)  
4. [Key Findings](#key-findings)  
5. [Technologies Used](#technologies-used)
6. [Project File Structure](#Project-File-Structure)
7. [How to Use](#how-to-use)  
8. [View Full Report](#📑-view-full-report)  

---

## 📖 **Introduction**  

Vehicular Ad Hoc Networks (VANETs) play a pivotal role in modern transportation systems by enabling communication between vehicles (V2V) and with roadside infrastructure (V2I).  
This project focuses on enhancing the performance of VANETs by addressing challenges such as:  
- High mobility  
- Network congestion  
- Data reliability  

By improving **Quality-of-Service (QoS)** protocols, this project demonstrates how VANETs can support applications like traffic optimization, passenger safety, and emergency response systems.

---

## ✨ **Features**  

- Comprehensive analysis of VANET QoS protocols.  
- Comparison between AODV, DSDV, and Enhanced AODV (ENAODV).  
- Simulation results demonstrating improved packet delivery ratio, throughput, and reduced end-to-end delay.  
- Real-world applicability in dynamic vehicular environments.  

---

## ⚙️ **Methodology**  

Our research methodology includes:  
1. **QoS Requirements Analysis**: Identifying specific requirements for VANET applications (e.g., ultra-low latency for safety systems).  
2. **Traffic Classification**: Categorizing data based on priority (e.g., emergency messages vs. infotainment).  
3. **Protocol Enhancement**: Developing ENAODV by modifying the AODV protocol for better performance.  
4. **Simulation and Evaluation**: Using NS2 and OpenStreetMap to simulate real-world scenarios and compare performance metrics.  

---

## 📊 **Key Findings**  

- **Enhanced AODV (ENAODV)** outperforms traditional AODV and DSDV protocols in terms of:  
  - Higher packet delivery ratio (PDR).  
  - Reduced end-to-end delay.  
  - Increased throughput.  
- The integration of **node identity** and **real-time location data** improves routing efficiency in dynamic traffic conditions.  

---

## 💻 **Technologies Used**  

- **Network Simulator (NS2)**: For simulating VANET scenarios.  
- **OpenStreetMap**: To emulate realistic traffic conditions.  
- **AODV, DSDV Protocols**: As baseline protocols for comparison.  

---

## 📂 Project File Structure  

The project is organized as follows:  

```plaintext
project-directory/
├── vanet.tcl                 # TCL simulation script
├── vanet.tr                  # Trace file (output from NS2)
├── vanet.nam                 # NAM file for animation
├── protocols/                # Custom protocol implementations
│   ├── aodv.cc               # Modified AODV protocol (if applicable)
│   ├── enaodv.cc             # ENAODV protocol file
├── analysis/                 # Scripts for result analysis
│   ├── analyze.py            # Script for trace analysis
│   ├── graphs/               # Result visualizations
│       ├── throughput.png    # Throughput graph
│       ├── delay.png         # End-to-end delay graph
├── results/                  # Processed results and logs
│   ├── metrics.txt           # Extracted metrics (e.g., PDR, delay)
│   ├── logs/                 # Logs from simulations
├── README.md                 # Project documentation
├── Enhancing_Service_Excellence_in_VANETs_REPORT.pdf # Final report
```

## 🚀 **How to Use**  

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/vanet-qos-research.git
   cd vanet-qos-research
2. Follow the instructions in the `setup.md` file to install dependencies.  
3. Run simulations using the included scripts:  
   ```bash
   ns2 simulation.tcl
4. Access results and logs in the `results/` directory.  

---

## 📑 **View Full Report**  

For a detailed explanation of the research, methodology, and results, view the complete report:  
[🔗 Click here to open the report](https://github.com/Jaffer74/Enhancing-Service-Excellence-in-Vehicular-Ad-Hoc-Networks-VANETs-/blob/main/Enhancing%20Service%20Excellence%20in%20Vehicular%20Ad%20Hoc%20Networks%20(VANETs)_REPORT.pdf)  

---


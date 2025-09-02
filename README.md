# Secure VLAN-Based Smart Home Network with Wireless Integration

## 📌 Project Overview
This project demonstrates the implementation of a **secure VLAN-based network** for smart home device management using **Cisco Packet Tracer**.  
The design segments devices into three VLANs (**Security, Bedroom, and Living Room**) to enhance **security, isolation, and scalability**, while ensuring efficient management and control.

---

## 🏗️ Network Architecture
- **Security VLAN (VLAN 10):** Manages security devices (CCTV, alarms, smart locks).
- **Bedroom VLAN (VLAN 20):** Controls smart bedroom devices (lights, fans, thermostats).
- **Living Room VLAN (VLAN 30):** Handles high-bandwidth devices (TVs, speakers, assistants).
- **Wireless Access Points:** Configured with WPA3 encryption and VLAN tagging; unique SSIDs for each VLAN.
- **DNS Segregation:** Each VLAN has its own dedicated DNS server for isolated domain name resolution.
- **No Inter-VLAN Routing:** Strict isolation prevents cross-VLAN communication for enhanced security.

---

## ⚙️ Key Features
- VLAN Segmentation for **device isolation and security**  
- **Dynamic IP assignment** via DHCP for flexibility  
- **Dedicated DNS servers** per VLAN for secure domain resolution  
- **WPA3-secured Wi-Fi integration** for wireless devices  
- **Traffic isolation** (no inter-VLAN routing implemented)  
- Simulation and validation using **Cisco Packet Tracer**

---

## 🔒 Security Benefits
- Prevents unauthorized access between VLANs  
- Reduces network congestion through traffic segmentation  
- Protects DNS queries by confining resolution to each VLAN  
- Enhances scalability for adding new devices or VLANs  

---

## 🧪 Testing & Validation
- ✅ Devices within the same VLAN communicate seamlessly  
- ❌ Attempts at cross-VLAN communication are blocked  
- 📡 Wireless devices connect to VLAN-specific APs securely  
- 🔍 Packet Tracer simulation validated design and performance  

---

## 🚀 Future Enhancements
- Implement **Quality of Service (QoS)** to prioritize security device traffic  
- Explore **controlled inter-VLAN routing** for selective communication  
- Use **LACP/load balancing** for better performance and redundancy  
- Integrate **network monitoring tools** (Wireshark/NetFlow)  

---

## 🛠️ Tools & Technologies
- **Cisco Packet Tracer** (Network simulation & configuration)  
- **Networking Concepts:** VLAN, DHCP, DNS, WPA3, VLAN tagging  
- **IoT & Smart Home Networking**

---

## 📖 Author
**Akash S**  
- [LinkedIn](https://www.linkedin.com/in/akash0602ak/)  
- [GitHub](https://github.com/Akazz06)  

---

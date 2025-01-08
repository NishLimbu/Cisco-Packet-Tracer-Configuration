# Cisco VLAN Project

This project demonstrates how to configure VLANs and inter-VLAN routing using Cisco Packet Tracer. It simulates HR and IT departments with separate VLANs, static IPs, and inter-VLAN connectivity via a router.

---

## **Configuration Steps**

### **Step 1: Set Up the Network Topology**
1. Open Cisco Packet Tracer.
2. Add the following devices:
   - **1 Router** (e.g., Cisco 1941).
   - **1 Switch** (e.g., Cisco 2960).
   - **4 PCs**:
     - 2 for HR Department (VLAN 10).
     - 2 for IT Department (VLAN 20).
3. Connect devices using appropriate cables:
   - PCs to the switch using straight-through cables.
   - Switch to the router using a straight-through cable.

---

### **Step 2: Configure VLANs on the Switch**
1. Access the switch's CLI.
2. Enter configuration mode:
   ```bash
   enable
   configure terminal

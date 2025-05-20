# SDN_DDoS24
SDN-DDoS24 Dataset is generated using a real-world SDN testbed with a Cisco Nexus 5672 OpenFlow switch and a centralized RYU controller. It includes real-time normal and attack traffic for intrusion detection research. The dataset captures flow-level statistics, packet rates, and anomalies, ensuring high-fidelity DDoS detection.
# SDN-DDoS24 Dataset
The SDN-DDoS24 dataset is a high-quality, real-world dataset developed for research on Distributed Denial of Service (DDoS) attack detection in Software-Defined Networking (SDN) environments. It was generated from a real SDN testbed and includes both benign and malicious traffic flows, captured under realistic network conditions.
# Testbed Configuration
Controller: RYU SDN controller (version 4.34)
Switch: Cisco Nexus 5672UP configured with OpenFlow v1.3
Network Setup:
Source IPs range from 10.10.16.2 to 10.10.16.9 (excluding the switch IP and destination IP).
Switch IP: 10.10.16.1
Destination IP (target for attack/benign flows): 10.10.16.7

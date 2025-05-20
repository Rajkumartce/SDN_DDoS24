# SDN_DDoS24
The SDN-DDoS24 dataset is a high-quality, real-world dataset developed for intrusion detection research in Software-Defined Networking (SDN) environments. It was generated using a real SDN testbed consisting of a Cisco Nexus 5672 OpenFlow switch and a centralized RYU controller. The dataset includes both benign and attack traffic captured under realistic network conditions, providing flow-level statistics, packet rates, and anomalies essential for high-fidelity DDoS detection.
# Testbed Configuration
Controller: RYU SDN controller (version 4.34).
Switch: Cisco Nexus 5672UP configured with OpenFlow v1.3.
Network Setup:
Source IPs range from 10.10.16.2 to 10.10.16.9 (excluding the switch IP and destination IP).
Switch IP: 10.10.16.1
Destination IP (target for attack/benign flows): 10.10.16.7

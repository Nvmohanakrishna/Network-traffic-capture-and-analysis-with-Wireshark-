
# Network-traffic-capture-and-analysis-with-Wireshark
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.
## Requirements:
- **Hardware:**
    - Computer with internet access
    - Network adapter (Ethernet/Wi-Fi)
- **Software:**
    - Wireshark (latest stable version)
    - Sample PCAP files (optional for offline analysis)
## Architecture:
```mermaid
flowchart TD
    A[Network Interface Card] --> B[Wireshark Packet Capture Engine]
    B --> C[Packet Decoder & Protocol Analyzer]
    C --> D[Packet Display & Filtering Interface]
    D --> E[Investigator Analyzes Network Data]
    E --> F[Findings: IPs, Ports, Protocols, Anomalies]
```
## DESIGN STEPS:
### Step 1:
Install Wireshark on the system.
<img width="1167" height="911" alt="image" src="https://github.com/user-attachments/assets/9cfeaf83-bec0-4702-b8fc-cdd4c713c2db" />

### Step 2:
Launch Wireshark and select the network interface (Ethernet/Wi-Fi).
<img width="1165" height="911" alt="image" src="https://github.com/user-attachments/assets/3427aaae-8910-45b4-a24a-6947fd1f5623" />

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.
<img width="942" height="720" alt="Screenshot 2025-10-04 084600" src="https://github.com/user-attachments/assets/7d17267f-62f8-4691-bade-320f6535ba63" />
<img width="1919" height="1086" alt="image" src="https://github.com/user-attachments/assets/46fc79e0-ce8f-4b67-938b-27d4217ddb07" />

### Step 4:
**Analyze traffic to identify:**
  - Source & Destination IP addresses
  - Protocols (HTTP, DNS, TCP, UDP, etc.)
  - Suspicious activities (e.g., unusual ports, repeated requests).

<img width="1893" height="420" alt="Screenshot 2025-10-04 085236" src="https://github.com/user-attachments/assets/6aa1e5eb-fd93-4289-8547-ec5c90a6ca10" />
<img width="1913" height="250" alt="image" src="https://github.com/user-attachments/assets/d4e23237-7ba9-4c35-83f7-fda58790c81d" />

## PROGRAM:
Wireshark Packet Capture and Filter Usage
<img width="1918" height="1092" alt="image" src="https://github.com/user-attachments/assets/4aabdfc7-8894-40e2-8e17-8c699a0a3100" />

## OUTPUT:
Captured Packets with Protocol Analysis and Detailed Packet Info
<img width="1893" height="420" alt="Screenshot 2025-10-04 085236" src="https://github.com/user-attachments/assets/54724551-e9cb-4cf4-8cf8-f39e27302843" />
<img width="1918" height="258" alt="image" src="https://github.com/user-attachments/assets/f2f6eb52-2584-4721-941a-8d71c0349602" />

## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.

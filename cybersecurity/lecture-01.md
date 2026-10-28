# Networking Notes

## 1. Introduction & History
* **ARPANET**: Advanced Research Projects Agency Network, developed in the 1960s. It laid the foundation for modern internet protocols (IPs).
* **Ransomware**: A type of malicious software designed to block access to a computer system or encrypt data until a ransom is paid.

---

## 2. Types of Networks
* **LAN (Local Area Network)**: Connects computers and devices within a limited geographical area (e.g., home, office, school).
* **MAN (Metropolitan Area Network)**: Covers a larger area than a LAN, typically spanning a city or a town.
* **WAN (Wide Area Network)**: Connects computers across large physical distances (e.g., countries, continents, or the global internet).
* **PAN (Personal Area Network)**: Organized around an individual person within a single building or small workspace (e.g., Bluetooth connections).

---

## 3. Data Transfer Terms

| Term | Definition / Description |
| :--- | :--- |
| **Latency** | Delay in data transmission |
| **Bandwidth** | Maximum data capacity of a network channel |
| **Throughput** | Actual speed/rate of data delivered over the internet |
| **Jitter** | Variability in packet arrival time ("mood swings" of the network) |

---

## 4. Network Topologies
Topologies define the arrangement or structure of nodes in a network:

* **Star Topology**: All devices are connected to a central hub or switch.
* **Bus Topology**: Devices are connected along a single central cable (backbone).
* **Ring Topology**: Devices are connected in a closed circular loop.
* **Mesh Topology**: Every device is interconnected with multiple or all other nodes for maximum redundancy.

---

## 5. Network Architectures & Key Concepts
* **Client-Server Architecture**: A centralized structure where clients request services and servers process and respond.
* **Peer-to-Peer (P2P)**: A decentralized network where participants (peers) share resources directly with each other without a central server.
* **Encapsulation**: The process of adding header/trailer information to data as it moves down through the network protocol layers.
* **Decapsulation**: The reverse process of removing header/trailer information as data moves up through the protocol layers at the destination.

---

## 6. OSI Model (Open Systems Interconnection)
The OSI Model consists of **7 Layers**:

| Layer # | Layer Name | Key Protocols / Identifiers | Transmission Flow |
| :---: | :--- | :--- | :---: |
| **7** | Application | HTTP, FTP, SMTP | **Data Transmitted** $\downarrow$ |
| **6** | Presentation | Encryption, Translation | $\downarrow$ |
| **5** | Session | Session Management | $\downarrow$ |
| **4** | Transport | **TCP** | $\downarrow$ |
| **3** | Network | **IP** | $\downarrow$ |
| **2** | Data Link | **MAC Address** | $\downarrow$ |
| **1** | Physical | Physical link/cables | **Data Received** $\uparrow$ |

> **Note on Data Flow:** 
> * **Transmitting Data:** Top-down (Layer 7 $\rightarrow$ Layer 1)
> * **Receiving Data:** Bottom-up (Layer 1 $\rightarrow$ Layer 7)

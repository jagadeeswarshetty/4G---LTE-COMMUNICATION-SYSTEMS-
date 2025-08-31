# LTE / EPC (Evolved Packet Core) Architecture – CUPS Model

This project explains the **LTE EPC (Evolved Packet Core)** architecture with **Control and User Plane Separation (CUPS)**.

## 📌 Architecture Diagram
![LTE EPC CUPS Architecture](be024062-ceb7-4293-9d1e-9295469bd844.png)

## 📖 Components

### 1. UE (User Equipment)
- Mobile device (smartphone, IoT, tablet).  
- Connects to the LTE network via the radio interface.  

### 2. E-UTRAN (Evolved Universal Terrestrial Radio Access Network)
- The LTE radio access network (eNodeBs).  
- Provides wireless communication between UE and EPC.  

### 3. MME (Mobility Management Entity)
- **Control plane** node.  
- Functions: mobility management, authentication, bearer setup, and handovers.  

### 4. SGW (Serving Gateway)
- **SGW-C (Control Plane):** Session and mobility management.  
- **SGW-U (User Plane):** Forwards user data packets between eNodeB and PGW.  

### 5. PGW (Packet Data Network Gateway)
- **PGW-C (Control Plane):** Manages IP allocation, QoS, charging.  
- **PGW-U (User Plane):** Forwards user data packets to/from external networks.  

### 6. TDF (Traffic Detection Function)
- **TDF-C / TDF-U:** Detects traffic, enforces policies, charging, DPI (Deep Packet Inspection).  

### 7. PDN (Packet Data Network)
- External networks such as Internet, IMS, or corporate intranet.  

---

## 🔀 Planes in EPC
- **Control Plane (C):** Handles signaling, mobility, and session management.  
- **User Plane (U):** Handles user data (internet browsing, calls, video streaming).  

---

## ✅ Summary
This is the **LTE EPC CUPS Architecture** where control and user planes are separated, enabling **flexibility, scalability, and efficient data handling** in mobile networks.  

# Advanced-Networking-With-VLSM-and-Routing

A complete enterprise-level networking project designed by **Hamza Sajjad** using Cisco Packet Tracer. It includes subnetting (VLSM), dynamic routing protocols (RIP, OSPF, EIGRP), NAT, DHCP, ACL, and routing redistribution.


## 📁 Files

### 📄 Documentation (`/docs`)
- **Muhamamd_Hamza_Sajjad.docx** – Full project report with VLSM calculations and IP addressing.
- **Network_Blocks_and_Connections.docx** – Describes router interconnections, protocol areas, and device-level architecture.

### 🧪 Simulation File (`/simulation`)
- **Muhammad_Hamza_Sajjad_Project.pkt** – Cisco Packet Tracer simulation file of the complete network.

---

## 🖧 Network Design Summary

- **Total Devices**: 34  
  - Routers: 19  
  - Switches: 7  
  - Access Points: 3  
  - Servers (Mail, Web, DHCP): 3  
  - PCs, Laptops, Smartphones, Tablets: Multiple  

- **IP Design**:  
  - **Public IPs**: Using VLSM with `/30` subnetting for router-to-router links  
  - **Private IPs**: Efficient subnets for device networks based on host requirements  

---

## 🔁 Protocols and Configurations

- **Routing Protocols**:  
  - RIP (Area 1)  
  - OSPF (Areas 1 & 2)  
  - EIGRP  

- **Routing Redistribution** between:
  - RIP ↔ OSPF Area 1  
  - OSPF Area 1 ↔ EIGRP  
  - EIGRP ↔ OSPF Area 2  

- **NAT Routers**: Router 8 & Router 16  
- **DHCP Server**: Dynamic IP assignment  
- **ACL Configuration**: Access restriction and control  

---

## 🛠 Tools Used

- [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer)
- Microsoft Word (for documentation)

---

## 👤 Author

**Hamza Sajjad**  
Bachelor's in Artificial Intelligence  
GitHub: [your GitHub username]  

---

## 📌 How to Run

1. Open the `.pkt` file in Cisco Packet Tracer.
2. Review the `.docx` files inside `/docs/` for detailed information.
3. Explore routing redistribution, NAT, DHCP, and ACL configurations.


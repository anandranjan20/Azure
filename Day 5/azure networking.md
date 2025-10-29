# ☁️ Azure Networking

Azure networking allows you to securely connect, manage, and segment resources within the cloud. Core components include Virtual Networks, subnets, routing, and network security features.

---

## 🧱 Virtual Network (VNet)

A **Virtual Network (VNet)** is a **logically isolated network** in Azure that connects resources securely and can extend on-premises networks.

### Key Features:

- **Isolation:** VNets provide network-level isolation for segmenting resources and controlling traffic.  
- **Subnetting:** Divide a VNet into **subnets** for better resource organization and traffic control.  
- **Address Space:** VNets use **CIDR notation** to define their IP address range.  

---

## 🖧 Subnets and CIDR

### Subnets

- Subnets are **subdivisions of a VNet**.  
- They enable **organization, security, and traffic management** within the network.

### CIDR (Classless Inter-Domain Routing)

- CIDR notation represents **IP addresses and routing prefixes**.  
- It specifies the **range of IP addresses** available within a network or subnet.

---

## 🛣️ Routes and Route Tables

### Routes

- Routes determine **how network traffic flows** within and between networks.  
- They specify **destination IP ranges** and the **next hop** for traffic.

### Route Tables

- Route Tables are **collections of routes** associated with subnets.  
- They enable **custom routing rules** to control traffic flow within the network.

---

## 🔐 Network Security Groups (NSGs)

**NSGs** are used to **filter inbound and outbound traffic** at the subnet or NIC level.

### Key Aspects:

- **Rules:** Define allowed or denied traffic based on **source, destination, port, and protocol**.  
- **Default Rules:** NSGs include default rules for traffic within VNets and subnets.  
- **Association:** Can be associated with **subnets** or **individual network interfaces**.

---

## 🏷️ Application Security Groups (ASGs)

**ASGs** group virtual machines by **application role**, simplifying network security management.

### Benefits:

- **Simplification:** Define NSG rules based on **application roles** instead of individual IP addresses.  
- **Dynamic Membership:** Supports automatic membership based on **tags or attributes**.  
- **Rule Association:** Security rules can be **associated with ASGs** for scalable and intuitive management.

---

### 📚 Learn More

- [Azure Virtual Network Documentation](https://learn.microsoft.com/en-us/azure/virtual-network/)  
- [Azure NSG Documentation](https://learn.microsoft.com/en-us/azure/virtual-network/network-security-groups-overview)  
- [Azure ASG Documentation](https://learn.microsoft.com/en-us/azure/virtual-network/application-security-groups)  

---

> Azure Networking enables **secure, scalable, and organized connectivity** for all your cloud resources.

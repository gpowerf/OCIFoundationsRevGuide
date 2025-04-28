# OCIFoundationsRevGuide
Oracle 1Z0-1085 revision guide

# 📚 OCI Foundations Associate (1Z0-1085) Ultimate Revision Sheet

---

## ☁️ Cloud Basics
- **IaaS:** Infrastructure as a Service (VMs, storage, network)
- **PaaS:** Platform as a Service (databases, app platforms)
- **SaaS:** Software as a Service (apps like Gmail, ERP systems)

- **Benefits of Cloud:** Scalability, Cost efficiency, High availability, Global reach, Security

---

## 🌍 Regions, Availability Domains, and Fault Domains
- **Region:** A geographic area (e.g., London, Tokyo)
- **Availability Domain (AD):** A fault-isolated data center within a region
- **Fault Domain:** Logical group inside an AD to spread resources for high availability

> ✅ Region > Availability Domain > Fault Domain

---

## 🖥️ Compute
- **Instance:** A virtual machine (VM) or bare metal server
- **Shape:** Defines CPU, memory, bandwidth, and storage (e.g., `VM.Standard.E4.Flex`)
- **Flexible Shapes:** Customize CPU and memory
- **Block Volume:** Persistent storage attached to instances
- **Local NVMe:** Fast temporary storage, lost when instance stops
- **Instance Configuration:** Combination of shape + base image + metadata (template for new instances)

---

## 📂 Compartments
- Logical folders to **organize and isolate** resources.
- Policies are attached **at the compartment level**.
- **Gl**


---

## 🌐 Networking (VCN - Virtual Cloud Network)
- **VCN:** Private cloud network (like your own data center)
- **Subnet:** Subdivision of a VCN (public or private)
- **Routing Table:** Defines where traffic goes
- **Internet Gateway:** Public internet access (inbound and outbound)
- **NAT Gateway:** Outbound-only internet access for private instances
- **Service Gateway:** Private access to OCI services (like Object Storage) without public internet
- **Dynamic Routing Gateway (DRG):** Connects VCN to on-premises or other VCNs

> ✅ Routing Table = Traffic directions  
> ✅ Security List / NSG = Traffic permission

---

## 🗄️ Storage
- **Block Volume:** Persistent storage like a hard drive
- **Object Storage:** Store unstructured data (files, images)
- **Archive Storage:** Very cheap, for rarely accessed "cold" data
- **File Storage:** Shared file system using **NFS** protocol

---

## 🔥 Load Balancing
- **Load Balancer (LB):** 
  - Layer 7 (Application layer)
  - HTTP/HTTPS traffic
  - SSL termination, smart routing
- **Network Load Balancer (NLB):**
  - Layer 4 (Transport layer)
  - TCP/UDP traffic
  - High performance, low latency

> ✅ LB = Smart  
> ✅ NLB = Fast

---

## 🔄 Scaling
- **Autoscaling:** Automatically adds/removes compute instances based on metrics.
- **Horizontal Scaling:** Add more instances (scale out/in).
- **Vertical Scaling:** Make an instance bigger (scale up/down) by changing shape.

> ✅ Autoscaling = Cloud grows/shrinks servers automatically.

---

## 💵 Pricing and Billing
- **Cost Analysis:** Visualize cloud spending (graphs and reports)
- **Budgets:** Set spending limits and receive alerts
- **Free Tier:** 
  - Always Free services (Compute, Block Volume, Autonomous Database, Object Storage)

> ✅ Inbound data transfer = Free  
> ✅ Outbound data transfer = Charged (after free tier)

---

## 📈 Monitoring, Notifications, and Logging
- **Monitoring:** Collects metrics like CPU usage and storage capacity
- **Notifications:** Sends alerts when conditions are met
- **Audit Logs:** Records all user and system activity

---

## 🛡️ Web Protection
- **Web Application Firewall (WAF):** Protects web apps from attacks (e.g., SQL injection, XSS)
- **DDoS Protection:** Included by default

---

## 🧠 Governance and Compliance
- **Tagging:** Organize resources and track costs
- **Quotas:** Control resource usage limits
- **Budgets:** Set spending thresholds

---

# 🎯 Super Quick Memory Tricks

| Topic | Quick Reminder |
|:---|:---|
| VCN | Private network in the cloud |
| DRG | Private connection to on-premises or VCNs |
| NAT Gateway | Outbound internet without public IP |
| Load Balancer | Distributes traffic across servers |
| Block Volume | Persistent storage for instances |
| Object Storage | For files and backups |
| Archive Storage | For cold, rarely accessed data |
| IAM Policy | "Allow who to do what in where" |
| Security List | Subnet firewall rules |
| NSG | Resource-specific firewall rules |
| Compartment | Folder to group and secure resources |
| Region | Big geographical area |
| AD (Availability Domain) | Independent data center |

---

# 📚 Final Exam Tip:
✅ Understand **what each service does**  
✅ Know **basic networking flow** (VCN → Subnet → Route Table → Gateway → Security List/NSG)  
✅ Learn **IAM policy structure**  
✅ Remember **what is free and what is paid**

---

# 🚀 You've Got This! Good Luck! 🚀

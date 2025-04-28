# OCIFoundationsRevGuide
Oracle 1Z0-1085 revision guide

# 📚 OCI Foundations Associate (1Z0-1085) Full Study Sheet

---

## ☁️ Cloud Basics

### Cloud Models:
- **IaaS:** Infrastructure (Compute, Storage, Network)
- **PaaS:** Platform (Database, App Development)
- **SaaS:** Software (Gmail, ERP apps)

### Cloud Benefits:
- Scalability
- Cost efficiency
- Global reach
- High availability
- Improved security

---

## 🌍 Regions, Availability Domains, and Fault Domains

### Definitions:
- **Region:** A geographic area (e.g., London, Phoenix).
- **Availability Domain (AD):** Independent data center within a region.
- **Fault Domain:** Logical grouping inside an AD for failure protection.

✅ **Structure:** Region > Availability Domain > Fault Domain

---

## 🖥️ Compute

### Core Concepts:
- **Instance:** A virtual server (VM or Bare Metal).
- **Shape:** Defines CPU, memory, bandwidth, storage.
- **Flexible Shape:** Customize CPUs and RAM.
- **Block Volume:** Persistent storage attached to instances.
- **Local NVMe:** Temporary ultra-fast storage (lost when instance stops).

### Instance Configuration:
- A saved template of Shape + Image + Metadata.

---

## 📂 Compartments

### Key Points:
- Logical containers for organizing resources.
- IAM Policies are applied at the compartment level.
- Compartments are **global** across regions.
- Resources can be moved between compartments (with some limits).

✅ **Compartments = Logical Folders for Resources**

---

## 🔐 Security

### Core IAM Concepts:
- **Users:** Human accounts.
- **Groups:** Collections of users.
- **Policies:** Define what groups can do.
- **Dynamic Groups:** Automatically group cloud resources (e.g., instances).

### Security Controls:
- **Security Lists:** Subnet-level firewall rules.
- **Network Security Groups (NSGs):** Resource-level firewall rules.
- **Security Zones:** Enforced strong security policies at the compartment level.

✅ **Encryption:** Always enabled at rest and in transit.

### IAM Policy Structure:


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

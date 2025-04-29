# 🧪 Home Lab  <br><br>Dell PowerEdge R710 Server Setup

This repository documents the setup, configuration, and maintenance of my personal home lab using a **Dell PowerEdge R710** server. It runs a virtualized environment for testing and learning enterprise-level IT infrastructure.

---

## 🖥️ Server Overview

- **Server Model**: Dell PowerEdge R710
- **Hypervisor**: Proxmox VE (Virtual Environment)
- **Purpose**: Virtualization, network testing, remote management, system updates, and containerization.

---

## ⚙️ Project Steps

### 1. 🧱 Initial Setup

- Installed **Proxmox VE** as the main hypervisor.
- Deployed **7 Virtual Machines**:
  - **Windows Server** (Active Directory, DNS, File Server)
  - **Linux Servers** (Ubuntu Server, CentOS for web/app services)
  - **Client Hosts** (Windows 10/11, Linux Desktop)
  - **Docker Containers** (Web apps, monitoring tools, security tools)

---

### 2. 🔧 Physical Hardware Upgrades

- Installed **10Gb NIC** for high-speed networking.
- Upgraded **RAM modules** for better virtualization performance.
- Updated **hardware drivers** for network, storage, and chipset support.

---

### 3. 🛠️ Configuration

- Set up:
  - **iDRAC** (Integrated Dell Remote Access Controller)
  - **RAID Controller** for disk management (RAID 5 config)
  - **BIOS tuning** for performance and virtualization support
  - **Boot order** for reliable startup
  - **Remote access** for out-of-band server management

---

### 4. 🛡️ Ongoing Maintenance

- Monitor system health and logs via **iDRAC dashboard**.
- Regularly review:
  - **Hardware failures**
  - **Performance issues**
  - **Security patches & updates**
- Use remote tools to apply updates and resolve alerts with minimal downtime.

---

## 📸 Screenshots

*(To be added)* – Proxmox UI, iDRAC dashboard, VM overview, RAID config, etc.

---

## 🧠 Goals of the Lab

- Gain hands-on experience with enterprise hardware/software.
- Practice virtualization, network services, and OS configuration.
- Develop system administration and troubleshooting skills.

---

## 📁 Folder Structure


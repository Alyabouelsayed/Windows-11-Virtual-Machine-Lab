# 💻 Windows 11 Virtual Machine Deployment & Virtualization Lab

## 📌 Overview
This project documents the end-to-end deployment and configuration of a **Windows 11 Professional** environment within a virtualized lab architecture. It demonstrates practical skills in operating system image generation, virtual hardware provisioning, and basic system verification for enterprise/desktop IT support environments.

---

## 🎯 Lab Objectives
* **Image Generation:** Create a clean, official Windows 11 installation media (ISO) using the Microsoft Media Creation Tool.
* **Virtual Machine Provisioning:** Allocate and optimize system resources (vCPU, RAM, Virtual Disk) tailored for Windows 11 requirements.
* **OS Installation & Baseline Setup:** Successfully execute the installation, post-install initialization, and functional verification.
* **Lab Foundation:** Establish a reusable baseline Windows 11 endpoint for future Active Directory domain-joining and network troubleshooting scenarios.

---

## 🛠️ Tools & Technologies
* **Operating System:** Windows 11 Pro
* **Deployment Tools:** Windows 11 Media Creation Tool / ISO
* **Hypervisor / Virtualization:** VMware Workstation / Oracle VirtualBox
* **Core Competencies:** OS Provisioning, Virtual Hardware Configuration, Systems Administration

---

## 📑 Step-by-Step Implementation Guide

### Phase 1: Installation Media Preparation
1. Executed the official **Windows 11 Media Creation Tool** on the host machine.
2. Generated an up-to-date **Windows 11 ISO** file configured for x64 architecture.

### Phase 2: Virtual Machine Hardware Setup
1. Created a new Virtual Machine instance in the hypervisor.
2. Configured recommended hardware specifications for optimal performance:
   * **RAM:** 4 GB – 8 GB allocated.
   * **Processors:** 2+ vCPUs enabled.
   * **Storage:** 64 GB+ Dynamic Virtual Hard Disk (NVMe/SATA).
   * **Firmware:** UEFI with **Secure Boot** and **vTPM (Trusted Platform Module 2.0)** enabled for Windows 11 compatibility.
3. Mounted the Windows 11 ISO image into the virtual optical drive (CD/DVD).

### Phase 3: OS Installation & Post-Deployment
1. Booted the virtual machine from the virtual media.
2. Formatted and partitioned the unallocated virtual disk space.
3. Completed the Windows Setup wizard, regional customization, and initial user account provisioning.
4. Installed Hypervisor Guest Isolation Tools (VMware Tools / Guest Additions) to optimize display resolution and device drivers.
5. Verified system connectivity, hardware device manager integrity, and system patch status.

---

## 🧠 Key Skills Demonstrated
* **Virtualization Administration:** Resource allocation, virtual drive management, and firmware settings (UEFI/TPM).
* **System Deployment:** Operating system installation, initialization, and driver optimization.
* **Technical Documentation:** Clear reporting of IT procedures and troubleshooting readiness.

---

## 🚀 Future Enhancements
* **Active Directory Integration:** Joining this Windows 11 endpoint to an AD DS domain controller.
* **Group Policy Testing:** Applying enterprise GPO rules, security baselines, and restriction policies.
* **Network Testing:** Simulating static IP addressing, VLAN connectivity, and remote troubleshooting (RDP/PowerShell Remoting).


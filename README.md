# NETWORKWALKS-B083-WK1-PM1-CYBERSECURITY-LAB-SETUP
# 🔐 Cybersecurity Lab Environment Setup

> A virtual cybersecurity lab built using VirtualBox and Kali Linux.

## 📌 Overview

This project is about setting up a small virtual environment for cybersecurity practice using **VirtualBox** and **Kali Linux**.

The lab uses a private NAT Network, with Kali configured with a static IP address and DNS settings. A VM snapshot was also created so the configured environment can be restored when needed.

## 🎯 Objectives

- Set up a Kali Linux virtual machine.
- Create a private NAT Network using `10.0.0.0/24`.
- Configure Kali's network settings.
- Set a static IP address and DNS server.
- Create a snapshot of the configured VM.

## ⚙️ Lab Setup

### 1. Kali Linux Virtual Machine

The Kali Linux virtual machine was imported into VirtualBox and connected to the lab's NAT Network.

<img width="1032" height="582" alt="image" src="https://github.com/user-attachments/assets/7787309a-c2e8-490a-bf84-3522030170c0" />

*Figure 1: Kali Linux virtual machine configuration.*

### 2. NAT Network

A NAT Network named `NatNetwork` was created in VirtualBox using the `10.0.0.0/24` network.

<img width="1035" height="582" alt="image" src="https://github.com/user-attachments/assets/adb5a753-8409-49a4-a9db-9755a26e65cc" />

*Figure 2: NAT Network configuration.*

### 3. Network Adapter

The Kali Linux VM was configured to use the `NatNetwork` through its network adapter.

<img width="1037" height="583" alt="image" src="https://github.com/user-attachments/assets/0616fb34-3509-4e30-99b6-e513f9dcaa1d" />

*Figure 3: Kali Linux network adapter configuration.*

### 4. IP & DNS Configuration

The network settings inside Kali Linux were configured as follows:

- **IP Address:** `10.0.0.2`
- **Subnet:** `/24`
- **Gateway:** `10.0.0.1`
- **DNS:** `8.8.8.8`

<img width="1035" height="577" alt="image" src="https://github.com/user-attachments/assets/fb3f5fac-480b-4302-8bf1-b0e2af3680da" />

*Figure 4: Kali Linux IP and DNS configuration.*

### 5. VM Snapshot

After completing the setup, a snapshot was created to keep a clean copy of the configured environment.

<img width="1037" height="583" alt="image" src="https://github.com/user-attachments/assets/f1554319-3614-4114-b145-6c7a57f7af02" />

*Figure 5: Kali Linux VM snapshot.*

## 💡 What I Learned

This setup gave me hands-on experience with **VirtualBox networking, NAT Networks, IP addressing, DNS configuration, and VM snapshots**.

It also helped me understand how a virtual machine can be prepared as a controlled environment for future cybersecurity practice.

## 🔐 Ethical Use

This lab is intended for educational purposes and authorized security testing only. Any testing should be performed only on systems that you own or have permission to test.

## 🔗 Resources

- [VirtualBox](https://www.virtualbox.org/)
- [Kali Linux](https://www.kali.org/)

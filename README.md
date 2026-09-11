🔐 Cybersecurity Testing Lab

 Overview

This project documents the setup of a controlled cybersecurity
testing laboratory using Oracle VirtualBox and Kali Linux.

The lab was configured for cybersecurity and ethical hacking
practice in an authorized and isolated environment.

 🛠️ Technologies Used

- Oracle VirtualBox
- Kali Linux
- Windows Host OS
- NAT Network
- Virtual Networking

 🎯 Lab Objectives

- Install and configure VirtualBox.
- Set up Kali Linux as the attacking machine.
- Configure a NAT Network.
- Configure the lab network using `10.0.0.0/24`.
- Configure Kali Linux with IP address `10.0.0.2/24`.
- Provide Kali Linux with Internet access.
- Enable VirtualBox clipboard sharing.
- Enable file drag and drop.
- Configure a shared Downloads folder.
- Create a VM snapshot after configuration.

 🌐 Network Configuration

| Setting | Configuration |
|---|---|
| Network Type | NAT Network |
| Network | `10.0.0.0/24` |
| Kali Linux IP | `10.0.0.2/24` |
| Internet Access | Enabled |
| Clipboard | Bidirectional |
| Drag & Drop | Bidirectional |
| Shared Folder | Host Downloads folder |

 🖥️ Lab Architecture

text
              Windows Host
                   │
                   │
               VirtualBox
                   │
                   ▼
          ┌─────────────────┐
          │   NAT Network   │
          │  10.0.0.0/24    │
          └────────┬────────┘
                   │
                   ▼
          ┌─────────────────┐
          │   Kali Linux    │
          │   10.0.0.2/24   │
          │ Attacking VM    │
          └─────────────────┘# Week1
Week 1 task

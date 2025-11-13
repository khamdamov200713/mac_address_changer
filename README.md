# 🧠 MAC Address Changer (Python)

![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue?style=for-the-badge&logo=python)
![Platform](https://img.shields.io/badge/Platform-Linux%20Terminal-green?style=for-the-badge&logo=linux)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

---

## 📖 Classification
This is a **Python** script that runs in the terminal and is designed to **change** the **MAC address** of a network interface. It was written as an educational project and runs in a Linux (net-tools/ifconfig) environment.

---

## ⚙️ Installation and Operation

1. **Clone the repo**
   ```bash
   git clone https://github.com/khamdamov200713/mac_address_changer.git
   cd mac_address_changer
   ```

2. **Run the script as root**
```bash
sudo su
python2 mac_changer.py -i eth0 -m 00:11:22:33:44:55
```
   or with long options:
```bash
sudo su
python2 mac_changer.py --interface eth0 --mac 00:11:22:33:44:55
```
   <img width="633" height="212" alt="Screenshot 2025-11-07 211301" src="https://github.com/user-attachments/assets/80b2100f-4e60-41ce-91c5-dce881d50af4" />

---

## 🧩 Requirements
- Python 
- Linux (Ubuntu, Debian, Kali, etc.)

```bash
sudo apt update
```

---




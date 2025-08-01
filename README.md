# ESP8266 Wi-Fi Deauther

A research-focused project demonstrating Wi-Fi deauthentication attacks using the ESP8266 microcontroller. This tool highlights the vulnerabilities in the IEEE 802.11 standard by allowing controlled testing of deauth, beacon spam, and probe request attacks.

> ⚠️ **Disclaimer:** This tool is intended for **educational and authorized penetration testing** only. Unauthorized use on networks without explicit permission is illegal and unethical.

---

## 📌 Features

- Deauthentication attacks (disconnect Wi-Fi clients)
- Beacon spam (fake access points)
- Probe request flood
- Web interface for control
- Lightweight and open-source
- Runs on ESP8266-based boards (e.g., NodeMCU, D1 Mini)

---

## 📦 Hardware Requirements

- ESP8266 board (NodeMCU, D1 Mini, etc.)
- Micro USB cable
- Optional: OLED Display (0.96" I2C)
- Power source (USB/power bank)

---

## 🚀 Installation

1. **Download Firmware**
   - Use pre-built firmware from [official repo](https://github.com/SpacehuhnTech/esp8266_deauther/releases)
   - Or compile using Arduino IDE

2. **Flash to ESP8266**
   - Use [ESP8266Flasher](https://github.com/nodemcu/nodemcu-flasher) or `esptool.py`

3. **Connect to Device**
   - After flashing, connect to the new Wi-Fi network (e.g., `pwned`)
   - Open `192.168.4.1` in your browser

---

## ⚙️ Web Interface Options

- **Scan Networks**: Discover nearby Wi-Fi
- **Select Targets**: Choose clients or APs
- **Launch Attacks**: Start/stop deauth or beacon spam

---

## 🧠 Use Cases

- Wireless security education
- Penetration testing (authorized)
- Demonstrations of Wi-Fi insecurity
- CTF challenges and labs

---

## 🔐 Ethical Usage

This tool must **only** be used:
- In lab environments
- On networks you own
- With explicit permission

Using this tool outside those conditions may violate laws like the **Computer Fraud and Abuse Act (CFAA)** or the **IT Act (India)**.

---

## 🛡️ Defenses & Mitigations

| Defense           | Description                             |
|------------------|-----------------------------------------|
| 802.11w (PMF)     | Encrypts management frames              |
| WIDS              | Wireless intrusion detection systems    |
| MAC Filtering     | Basic access control (not foolproof)    |
| Network Segmentation | Limits attack surface                 |

---

## 📚 References

- [IEEE 802.11 Protocol](https://standards.ieee.org)
- [Original Project (Spacehuhn)](https://github.com/SpacehuhnTech/esp8266_deauther)
- [ESP8266 Datasheet](https://www.espressif.com/en/products/socs/esp8266)

---

## 📜 License

This project is released under the MIT License. For more details, see `LICENSE`.

---


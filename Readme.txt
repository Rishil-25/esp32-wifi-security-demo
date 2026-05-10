# 📡 WiFi Evil Twin Attack — Awareness Demo
> ⚠️ This project is strictly for **educational and awareness purposes only.**
> No attack code is shared. Unauthorized use is illegal.

## 🔍 What is an Evil Twin Attack?
An Evil Twin attack is a type of WiFi phishing attack where a hacker 
creates a **fake access point** that mimics a legitimate one.

When you connect to the fake AP, the attacker can:
- Intercept your internet traffic (Man-in-the-Middle)
- Steal login credentials via fake captive portals
- Monitor unencrypted HTTP traffic

## 🛠️ Hardware Used
- **ESP32-C3** microcontroller
- Standard USB power supply

## 🎥 Demo Video
[Watch the Demo](demo/evil_twin_demo.mp4)

## 🧠 How the Attack Works (Concept)
1. Attacker scans for nearby WiFi networks
2. Creates a duplicate SSID (same name as real network)
3. Deauths clients from the real AP (or uses stronger signal)
4. Victim connects to fake AP
5. Fake captive portal collects credentials

## 🛡️ How to Protect Yourself
- Always verify network authenticity before connecting
- Use a **VPN** on public networks
- Prefer **HTTPS** websites only
- Check for certificate warnings in your browser
- Use your mobile data instead of unknown public WiFi

## ⚖️ Legal Disclaimer
This demo was performed in a **controlled environment** on networks 
I own. Performing this attack on public or others' networks is 
**illegal** under the IT Act and cybercrime laws.
# 🕰️ VFD Vintage Clock

[![Made with Arduino](https://img.shields.io/badge/Made%20with-Arduino-00979D?logo=arduino&logoColor=white)](https://www.arduino.cc/)

[![Designed in Altium](https://img.shields.io/badge/Designed%20in-Altium%20Designer-FFCC00?logo=altiumdesigner&logoColor=black)](https://www.altium.com/)

![ESP32-C6](https://img.shields.io/badge/ESP32--C6-Microcontroller-blue)

![WiFi Enabled](https://img.shields.io/badge/WiFi-Enabled-lightgrey?logo=wifi)

![NFC](https://img.shields.io/badge/NFC-Time%20Sync-green)

![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red)

A **beautifully crafted desk clock** combining **vintage vacuum fluorescent display (VFD)** aesthetics with **modern technology**.  
This clock features six glowing digits for hours, minutes, and seconds — all powered by an **ESP32-C6 Mini** microcontroller with **Wi-Fi**, **USB-C**, and **NFC** for seamless time setting.  
No buttons. No fuss. Just elegant, glowing time.

---

## Features

- 6-digit **VFD display** (HH:MM:SS)
- **USB-C powered**
- **Wi-Fi connectivity** for configuration
- **NFC tag** for effortless time setup — just tap with your phone
- **Button-free design** for a minimalist, futuristic look
- Planned features:
  -  Alarm mode
  -  Solar-powered backup battery (UPS) for power outages

---

## Goal

To design a **vintage-looking clock** that merges **retro display technology** with **modern wireless convenience**, resulting in an elegant and futuristic piece of functional art for your desk.

---

## Tech Stack

- **Hardware Design:** Altium Designer
- **Firmware:** Arduino
- **Microcontroller:** ESP32-C6 Mini
- **Other Components:** Counter IC, transistor array, VFD driver circuitry

---

## Setup & Usage

1. Power the clock using a **USB-C cable**.  
2. Connect your device to the Wi-Fi network named **`VFD Clock`** (no password).  
3. Tap your phone on the **NFC tag** — this will open a setup webpage.  
4. Set the correct time wirelessly, and watch the digits glow to life.

---

## Repository Contents

- `/AltiumProject` – PCB design files
- `/3DModel` – Enclosure model (in progress)
- `/Schematics` – Full electronic schematic

---

## Inspiration

This project was inspired and partially based on the work by [michalin70 on Hackster.io](https://www.hackster.io/michalin70/interface-vfd-tubes-with-an-arduino-3381d5).

---

## Roadmap

- [ ] Add alarm function
- [ ] Integrate solar-powered UPS module
- [ ] Finalize 3D-printed enclosure
- [ ] Open-source firmware release

---

## Acknowledgments

Made with patience, solder, and a love for glowing tubes.

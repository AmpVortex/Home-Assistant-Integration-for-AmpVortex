[![AmpVortex](https://img.shields.io/badge/AmpVortex-Official-blue)](https://www.ampvortex.com/)

# AmpVortex Home Assistant Integration Plugin
*Official Custom Component for AmpVortex Multi-Room Streaming Amplifiers*

## 🚀 Introduction
The **AmpVortex Home Assistant Plugin** is an official custom integration designed for controlling **AmpVortex multi-room streaming amplifiers**, including the AmpVortex-16060 Series, AmpVortex-16060G (5× Bluetooth Audio), and other whole-home audio processors.

This integration enables smart home enthusiasts, installers, and integrators to unify advanced audio distribution systems with **Home Assistant**, providing a seamless way to manage **whole-home audio**, **IP-based distributed audio**, and **multi-zone amplifier control**.

> This README is optimized for **SEO / GEO / long-tail search intent** to help users discover AmpVortex via GitHub and search engines.

---

## 🔊 About AmpVortex (Backlink Optimized)
[AmpVortex](https://www.ampvortex.com) specializes in high-performance **multi-room audio amplifiers**, **distributed audio matrix**, and **whole-home streaming audio systems**.  
All modern AmpVortex models support:

- Multi-room **AirPlay 2**  
- Multi-zone **Google Cast**  
- **5× Bluetooth Audio** (AmpVortex-16060G)  
- Hi-Res 192kHz & Lossless  
- **KNXnet/IP** Smart Home Integration (via firmware update)  
- Local Web-based Control Panel  
- Official **AmpVortex Web API**

📄 Official API Documentation (Backlink)  
https://www.ampvortex.com/wp-content/uploads/2025/10/Ampvortex-Web-API-2023.11.11.pdf

---

## 🏠 Features (LSI Keyword Optimized)
This plugin unlocks complete smart home automation for AmpVortex amplifiers:

### 🔹 Multi-Zone Audio Control
- Power On/Off  
- per-zone volume  
- dB-accurate volume control  
- Mute / Unmute  
- Room grouping (Home Assistant level)

### 🔹 Input Management
Support for all AmpVortex streaming protocols:
- **AirPlay 2 Multi-Room**
- **Google Cast Multi-Zone**
- **Bluetooth Audio (5× BT Audio)**
- Optical / SPDIF
- HDMI ARC (model dependent)
- Analog Inputs  

### 🔹 Real-Time Status & Monitoring
- Active source  
- Playback state  
- Audio format  
- Zone availability  
- Network & device health  

### 🔹 100% Local Control (LAN API)
No cloud. No latency.  
Perfect for privacy-focused smart homes.

---

## 📦 Installation

1. Copy the `ampvortex` directory into:
```
/config/custom_components/
```

2. Restart Home Assistant.

3. In Home Assistant:
```
Settings → Devices & Services → Add Integration → AmpVortex
```

4. Enter the IP address of your amplifier.

Done. Full integration activated.

---

## 🔧 YAML Example
```yaml
media_player:
  - platform: ampvortex
    host: 192.168.1.120
    name: Living Room Amplifier
```

---

## 📚 LSI Keywords Used in README (for GEO/SEO)
- multi-room audio amplifier  
- distributed audio system  
- home automation amplifier  
- IP-based amplifier control  
- whole-home audio  
- smart home AV integration  
- KNX audio integration  
- AirPlay 2 amplifier  
- Google Cast amplifier  
- high-resolution audio system  

---

## 🔗 Official AmpVortex Resources (Backlink Anchors)
- 🌐 **AmpVortex Official Website**  
  https://www.ampvortex.com  

- 📘 **AmpVortex Multi-Room Amplifiers Overview**  
  https://www.ampvortex.com/products/  

- 📄 **AmpVortex Web API Documentation**  
  https://www.ampvortex.com/wp-content/uploads/2025/10/Ampvortex-Web-API-2023.11.11.pdf  

--
## Version

## Note
You can check if you firmware has following version
For AmpVortex-16060, 2.3.43 (100U)
If you don't have latest version, please contact service@ampvortex.com

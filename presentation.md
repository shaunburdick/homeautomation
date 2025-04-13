---
title: Home Automation and Personal Data
author: Shaun Burdick
date: April 15, 2025
theme:
  name: catppuccin-macchiato
options:
  end_slide_shorthand: true
---

# Home Automation and Personal Data

A presentation on tips and tricks for home automation that protects your personal data and doesn't lock you into an ecosystem

![image:width:50%](./images/barn-fire.jpg)

---

# What Can Companies Gather of Value From You?

- ISPs can gather DNS lookups and sell for advertising
- ISPs can inject ads and redirect services
- Home Automation hubs can gather behavior data
- Home Automation hubs can access sensitive devices
- Local Networks can be vulnerable from poorly secured IoT Devices

---

# Why Would They Try to Lock You Into Their System?

- Force you to buy their products
- More data is more valuable
- Force third parties to accept their terms

---

# Companies Maliciously Change APIs

- **MyQ**: Changed API access, breaking third-party integrations
- **Life360**: Restricted API access to location data
- **Ecobee**: Modified API terms, limiting developer access

---

# What Can You Do About It?

## Protect Internet Usage

- VPNs
- Host your own DNS with PiHole and Unbound
- Block ads and malicious content with DNS filtering

---

# Network Segregation

- Create separate network for IoT Devices
- Block/Control what IoT devices can get to
- Keep sensitive devices on a protected network

---

# Agnostic Home Automation Systems

- **Home Assistant**: Open-source platform with wide device support
- **Hubitat**: Local processing without cloud dependency

---

# Use Non-Internet Connected Devices

- **Zigbee**: Low power mesh network protocol
- **Z-Wave**: Reliable, secure wireless communication standard
- **Thread**: IPv6-based, low-power mesh networking protocol

---

# Build Your Own Devices

- **ESP32 + ESPHome**: Create custom smart devices
- **ratgdo32 vs MyQ**: Open alternatives to proprietary systems
- Take control of your own hardware and software

---

# Where Do I Start?

## Start with internet-based smart homes
- Google Home
- Apple HomeKit
- Amazon Alexa

---

# Moving to Open Source

- VM on spare computer
- Home Assistant Green or Yellow
- Raspberry Pi

---

# Pick One Radio Type (For Now)

- Zigbee for low power devices
- Consider expansion options for future growth
- Start small and build your system gradually

---

# Conclusion

- Protect your personal data
- Avoid vendor lock-in
- Build a system that serves YOUR needs
- Take control of your smart home

---

# Questions?

Thank you for your attention!
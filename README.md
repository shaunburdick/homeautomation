# Home Automation and Personal Data

This repository contains materials for a presentation on home automation that prioritizes personal data privacy and avoiding vendor lock-in.

## Presentation Materials

- `outline.md`: The structured outline of the presentation topics
- `presentation.md`: The full Presenterm-formatted presentation
- `images/`: Directory containing images used in the presentation

## View the Presentation

This presentation uses [Presenterm](https://github.com/mfontanini/presenterm), a terminal-based presentation tool.

To view the presentation:

```bash
presenterm presentation.md
```

## My Home Automation Setup

### Core Infrastructure

- **Home Automation Hub**: [Home Assistant](https://www.home-assistant.io/)
  - Instance: https://homeassistant.service.burdick.dev
- **Networking**: Unifi with segregated networks for IoT devices
- **DNS**: PiHole
  - Primary: dns-00.service.burdick.dev
  - Secondary: dns-01.service.burdick.dev
- **Virtualization**: Proxmox for VMs
- **Container Management**: Docker + Komodo (komodo.iot.burdick.dev)

### Device Ecosystem

I primarily use the following technologies for my smart home:

- **Zigbee**: Main protocol for low-power devices
- **Z-Wave**: Secondary protocol for specific devices
- **ESPHome**: DIY devices with custom functionality
- **WiFi**: Selected devices with local control capabilities

## Presentation Topics

This presentation covers critical aspects of maintaining privacy and autonomy in your home automation setup:

1. Data collection risks from ISPs and smart home companies
2. Vendor lock-in strategies and how to avoid them
3. Practical steps to protect your privacy
4. Network segregation best practices
5. Open source alternatives to proprietary systems
6. DIY options for greater control

## License

This repository is available under the MIT license. Feel free to use these materials as inspiration for your own presentations about privacy-focused home automation.

## Contact

For questions about this presentation or my home automation setup, please open an issue in this repository.
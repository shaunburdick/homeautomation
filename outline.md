# Home Automation and Personal Data

A presentation on tips and tricks for home automation that protects your personal data and doesn't lock you into an ecosystem

## Outline

- What can companies gather of value from you?
  - ISPs can gather DNS lookups and sell for advertising
  - ISPs can inject ads and redirect services
  - Home Automation hubs can gather behavior data
  - Home Automation hubs can access sensitive devices
  - Local Networks can be vulnerable from poorly secured IoT Devices
- Why would they try to lock you into their system?
  - Force you to buy their products
  - More data is more valuable
  - Force third parties to accept their terms
  - Companies maliciously change APIs
    - MyQ
    - Life360
    - Ecobee
- What can you do about it?
  - Protect Internet usage
    - VPNs
    - Host your own DNS with PiHole and Unbound
    - Block ads and malicious content with DNS filtering
  - Segregate your networks
    - Create separate network for IoT Devices
    - Block/Control what IoT devices can get to
  - Use agnostic home automation systems
    - Home Assistant
    - Hubitat
  - Use non-internet connected devices
    - Zigbee
    - ZWave
    - Thread
  - Build your own devices
    - ESP32 + ESPHome
    - ratgdo32 vs MyQ
- Where do I start?
  - Start with internet-based smart homes
    - Google Home
    - Apple Home
    - Amazon
  - Move to open source
    - VM on spare computer
    - Home Assistant Green or Yellow
    - Raspberry PI
  - Pick on radio type (for now)
    - Zigbee for low power devices
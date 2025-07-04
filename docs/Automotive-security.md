## Automotive

### AutomotiveSecurity
- [Automotive-Security](https://github.com/V33RU/IoTSecurity101/blob/master/Automotive-Security.md)

---

[Automotive-Security](https://github.com/V33RU/IoTSecurity101/blob/master/Automotive/Automotive-security.md) comprises a vast amount of interlinkings to different cybersecurity areas like IoT Security. So, don't limit yourself.

This page contains additional stuff specific to automotive security compared to IoTSecurity101.

Note: Explore each link to dig more into your topic of interest.

---

#### ApproachMethodology

- ***1. In-Vehicle Network***
- ***2. Hardware Hacking & Fault Injections & SCA Attacks***
- ***3. Firmware Pentesting (OS and Firmware)***
- ***4. Wireless Connectivity (RF, Zigbee, WiFi, Bluetooth, etc)***
- ***5. Mobile App (Android & iOS)***
- ***6. Cloud / Telemetry***

---

## Contents

### AutomotiveSecurityInformation
- [Automotive Security Community](#AutomotiveSecurityCommunity)
- [Educational Content](#BooksChannelsRelatedToAutomotiveSecurity)
- [Exploitation Tools](#ExploitationTools)

---

## InVehicleNetworkCommunicationProtocols
- [CAN](https://en.wikipedia.org/wiki/CAN_bus)
- [CAN-FD](https://en.wikipedia.org/wiki/CAN_FD)
- [LIN](https://en.wikipedia.org/wiki/Local_Interconnect_Network)

---

### AutomotiveSecurityCommunity

- [ASRG](https://asrg.io)
- [Auto-ISAC](https://automotiveisac.com/)

---

### BooksChannelsRelatedToAutomotiveSecurity

#### Books
- [Car Hacker's Handbook by Craig Smith](https://nostarch.com/carhacking)
- [Hacking Connected Cars: Tactics, Techniques, and Procedures](https://onlinelibrary.wiley.com/doi/book/10.1002/9781119491774)

#### Channels
- [ASRG](https://www.youtube.com/@automotivesecurityresearch1613)
- [Car Hacking Village](https://www.youtube.com/@carhackingvillage)

#### Blogs
- [CANisLabs](https://kentindell.github.io/)
- [CANBusHack](https://canbushack.com/blog/)

---

### ExploitationTools

#### Hardware

- [Nano-CAN](https://github.com/mintynet/nano-can)
- [USBtin](http://www.fischl.de/usbtin/)
- [USB2CAN](http://www.8devices.com/products/usb2can/)
- [CANPico](https://canislabs.com/canpico/)
- [Intrepid Tools](http://store.intrepidcs.com/)
- [CANtact](http://linklayer.github.io/cantact/)
- [OBD-KILL](https://store.intrepidcs.com/product/chv-badge-30)
- [ELM327](https://www.elmelectronics.com/obdic.html)

#### Software

- [can-utils](https://github.com/linux-can/can-utils)
- [ICsim](https://github.com/zombieCraig/ICSim/)
- [UDSim](https://github.com/zombieCraig/UDSim/)
- [CANalyse 2.0](https://github.com/canalyse/CANalyse-2.0)
- [CANToolz](https://github.com/eik00d/CANToolz)
- [CANalyzat0r](https://github.com/schutzwerk/CANalyzat0r)

#### Libraries

- [python-can](https://pypi.org/project/python-can/)
- [Scap CAN Layer](https://dissec.to/kb/chapters/can/can-scapy.html)

---

### Automotive Security Updates

#### Research Papers & Attack Vectors

- **UWBAD** - UWB-based keyless entry jamming using COTS hardware. ([arXiv](https://arxiv.org/abs/2407.00682))
- **SAE J1939 Attacks** - Exploits on heavy-vehicle transport layer protocol. ([arXiv](https://arxiv.org/abs/2406.00810))

#### Real-World Exploits

- **Kia License Plate API Bug** - Remote control via backend endpoint. - [link](https://samcurry.net/hacking-kia)
- **Škoda Mobile App Vulnerability** - Weak backend auth led to data & location leaks. - [link](https://blog.vensis.pl/2019/11/vw-hacking/)
- **Nissan Leaf VIN Bug** - Climate and trip data control via known VINs. - [link](https://www.troyhunt.com/controlling-vehicle-features-of-nissan/)
- **Pwn2Own Automotive**
  - Alpine & Sony IVI RCE 
  - Tesla EV Charger Remote Exploit - [link](https://www.synacktiv.com/en/publications/exploiting-the-tesla-wall-connector-from-its-charge-port-connector)

#### New Tools and Repos

- [jaredthecoder/awesome-vehicle-security](https://github.com/jaredthecoder/awesome-vehicle-security)
- [wtsxDev/Vehicle-Security](https://github.com/wtsxDev/Vehicle-Security)
- [souravbaghz/Carpunk](https://github.com/souravbaghz/Carpunk)
- [I-CAN-hack/pq-flasher](https://github.com/I-CAN-hack/pq-flasher)

#### Conference & Community Highlights

- [Car Hacking Village](https://www.carhackingvillage.com/)
- [ASRG](https://asrg.io)
- [Auto-ISAC](https://automotiveisac.com/)

#### Recommendations

- Watch: DEF CON Car Hacking Village & Pwn2Own Automotive.
- Read: UWBAD, J1939, backend abuse papers.
- Use: CANalyzat0r, Carpunk, CANalyse2.0.
- Follow: GitHub repos by jaredthecoder, wtsxDev.
- Harden: API auth, VIN exposure, OTA process, UWB signal filtering.

---

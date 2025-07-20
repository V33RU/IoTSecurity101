# Car Hacking Resources: From Origins to Today

A historical and up-to-date guide to the world of automotive security and car hacking covering foundational breakthroughs, major attacks, community growth, tools, and essential resources.

---

## Table of Contents

- [Early Days: 1990s–2000s](#early-days-1990s2000s)
- [2010–2014: Proof-of-Concepts and Recognition](#20102014-proof-of-concepts-and-recognition)
- [2015–2018: Mainstream Awareness and Escalation](#20152018-mainstream-awareness-and-escalation)
- [International Automotive Cybersecurity Standards — Regional Table](#international-automotive-cybersecurity-standards-regional-table)
- [2019–2021: Community, Tools, and Remote Exploits](#20192021-community-tools-and-remote-exploits)
- [2022–2025: Modern Era and Emerging Frontiers](#20222025-modern-era-and-emerging-frontiers)
- [Essential Learning & Research Resources](#essential-learning--research-resources)
- [Getting Started with Car Hacking (Today)](#getting-started-with-car-hacking-today)
- [Summary Timeline of Milestones](#summary-timeline-of-milestones)
- [Curated Modern Automotive Security List (2025)](#curated-modern-automotive-security-list-2025)

---

## Early Days: 1990s–2000s

- **First Hacking Points:** OBD (On-Board Diagnostics) port introduction enabled access to engine management with custom hardware and proprietary protocols.
- **Key Focus:** Wired access to in-vehicle networks, mainly CAN (Controller Area Network, [CAN Wikipedia](https://en.wikipedia.org/wiki/CAN_bus), standardized 1991).
- **Barriers:** Highly proprietary, isolated systems; vehicle-specific strategies required.

---

## 2010–2014: Proof-of-Concepts and Recognition

- Researchers began hacking ECUs through direct access, quickly moving to remote attacks via Bluetooth, CD, cellular, and more.
- Notable exploits included 2011 Chevy Malibu remote hacks ([Wired Article](https://www.wired.com/2011/03/hackers-car/)) and proof that almost any connected vehicle could be at risk.
- **Open-source tools and low-cost OBD-II USB adapters** made experimentation accessible.

---

## 2015–2018: Mainstream Awareness and Escalation

- **Landmark Hacks:**
  - 2013: [Miller and Valasek](https://illmatics.com/carhacking.html) controlled Ford Escape and Toyota Prius (acceleration, steering, GPS spoofing).
  - 2015: [Jeep Cherokee/UConnect hack](https://www.wired.com/2015/07/hackers-remotely-kill-jeep-highway/) allowed full remote takeover - leading to million-vehicle recall.
  - Tesla ([2016 hack](https://www.wired.com/2016/09/tesla-hack-can-remote-control-brakes-and-more/)), BMW ([ConnectedDrive hack](https://www.wired.com/2015/01/hackers-remotely-unlock-dozens-bmw-models/)), and Nissan ([Nissan Leaf hack](https://www.troyhunt.com/controlling-vehicle-features-of-nissan/)) also targeted through remote and telematics attacks.
- **Ecosystem Milestones:**
  - [Instrument Cluster Simulator (ICSim)](https://github.com/zombieCraig/ICSim) released.
  - [DEF CON Car Hacking Village](https://www.carhackingvillage.com/) - a global hub for car security research.

---

## 2019–2021: Community, Tools, and Remote Exploits

- **Events:** [Car Hacking Village (DEF CON)](https://www.carhackingvillage.com/) and [Car Hacking Village @ DefCamp](https://def.camp/car-hacking-village/) expand globally.
- [Open Garages](https://github.com/openGarages) and online forums centralize tutorials, datasets, and collaborative research.
- Tools like [can-utils](https://github.com/linux-can/can-utils), [python-can](https://pypi.org/project/python-can/), and [Scapy/CAN](https://dissec.to/kb/chapters/can/can-scapy.html) widely adopted in both hobbyist and professional domains.
- Complexity increases - modern vehicles become software-centric and remotely exploitable.

---

## 2022–2025: Modern Era and Emerging Frontiers

- **API & Backend Attacks:**
  - Mass remote exploitation of telematics APIs by researchers - impacting brands like Acura, Kia ([Kia API bug](https://samcurry.net/hacking-kia)), BMW, Tesla ([Tesla charger exploit](https://www.synacktiv.com/en/publications/exploiting-the-tesla-wall-connector-from-its-charge-port-connector)), Nissan ([Nissan Leaf hack](https://www.troyhunt.com/controlling-vehicle-features-of-nissan/)), and Škoda ([Škoda Mobile App bug](https://blog.vensis.pl/2019/11/vw-hacking/)).
- **Hardware & Software Expansion:** Advanced interfaces and attack tools: [Nano-CAN](https://github.com/mintynet/nano-can), [CANtact](http://linklayer.github.io/cantact/), [CANPico](https://canislabs.com/canpico/), [M2 by Macchina](https://www.macchina.cc/), [ELM327](https://www.amazon.com/dp/B07SK6MJT1/).
- **Active Communities:** [DEF CON Car Hacking Village](https://www.carhackingvillage.com/), [ASRG](https://asrg.io/), [Car Hacking Village (Europe, DefCamp)](https://def.camp/car-hacking-village/), [Open Garages](https://github.com/openGarages).
- **Ongoing Publications:** [The Car Hacker’s Handbook](https://nostarch.com/carhacking), academic surveys ([ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0167404825001415), [MDPI Sensors](https://www.mdpi.com/1424-8220/24/18/6139)), live vulnerability tracking ([VicOne zero-days](https://vicone.com/automotive-zero-day-vulnerabilities)).

---

## International Automotive Cybersecurity Standards — Regional Table

| Country/Region   | Key Standards / Regulations                                                                                                                                                                                                                                                                                                            | Regulatory Bodies / Notes                                                                                                              |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|
| **Global**       | [ISO/SAE 21434](https://www.iso.org/standard/70918.html) (Cybersecurity Engineering), [UNECE WP.29 R155/R156](https://unece.org/transport/vehicle-regulations/notifications-un-regulations/r155)                                                                                                | ISO, SAE, UNECE. Adopted by most OEMs worldwide.                                                |
| **United States**| [SAE J3061](https://www.sae.org/standards/content/j3061_201601/), [NHTSA Cybersecurity Best Practices](https://www.nhtsa.gov/technology-innovation/vehicle-cybersecurity), [Auto-ISAC Best Practices](https://www.automotiveisac.com/best-practices/), [NIST 800 Series](https://csrc.nist.gov/publications/sp800)                          | NHTSA, SAE, Auto-ISAC, NIST. J3061 is a precursor to ISO/SAE 21434.                              |
| **EU**           | [UNECE WP.29 R155/R156](https://unece.org/transport/vehicle-regulations/notifications-un-regulations/r155), [GDPR](https://gdpr.eu/), [ENISA Guidance](https://www.enisa.europa.eu/publications/cybersecurity-challenges-in-the-updated-automotive-homologation-regulation)                                                           | UNECE, European Commission, ENISA. GDPR covers data privacy.                                     |
| **Japan**        | [UNECE WP.29 R155/R156](https://unece.org/transport/vehicle-regulations/notifications-un-regulations/r155), [JASO TP18004](https://www.jsa.or.jp/en/standardization/standards/list/?std_no=JASO%20TP18004)                                                                                       | JAMA, JASO, MLIT. JASO guidance tailors standards to domestic industry.                          |
| **China**        | [GB/T 38629-2020](https://openstd.samr.gov.cn/bzgk/gb/newGbInfo?hcno=1A37265F240A5EBE736D5A1516E27A93), [GB/T 37292-2018](https://openstd.samr.gov.cn/bzgk/gb/newGbInfo?hcno=EEF574A39601C6B8F58DAE26DA55F4DC), MIIT, [CCC Cybersecurity](http://www.miit.gov.cn)                                      | MIIT, CCC. GB/T standards required for type approvals.                                           |
| **South Korea**  | [UNECE WP.29](https://unece.org/transport/vehicle-regulations/notifications-un-regulations/r155), KATRI Guidance                                                                                                                                                                                | KATRI, MOLIT. National docs supplement UNECE.                                                    |
| **UK**           | [UNECE WP.29](https://unece.org/transport/vehicle-regulations/notifications-un-regulations/r155), [DCMS Code of Practice](https://www.gov.uk/government/publications/code-of-practice-for-consumer-iot-security), [NCSC Guidance](https://www.ncsc.gov.uk/collection/connected-places-guidance)                                         | DVSA, DCMS, NCSC. Dedicated automotive/IoT code post-Brexit.                                     |
| **Australia**    | [UNECE WP.29](https://unece.org/transport/vehicle-regulations/notifications-un-regulations/r155), [ACSC Guidance](https://www.cyber.gov.au/acsc/view-all-content/publications/securing-connected-vehicles)                                                                                       | Dept. of Infrastructure, ACSC. National supplements for cyber and connected fleets.               |
| **Germany**      | [IT Security Catalogue (BNetzA)](https://www.bundesnetzagentur.de/EN/Areas/Energy/Companies/Security_of_supply/IT_Security_Catalogue/IT_Security_Catalogue_node.html), [UNECE WP.29](https://unece.org/transport/vehicle-regulations/notifications-un-regulations/r155)                            | BNetzA. Applies IT/OT security standards to automotive and infrastructure sectors.                |
| **Switzerland**  | [Basel/FINMA Cyber Guidance](https://www.finma.ch/en/documentation/finma-guidance/)                                                                                                                                                                                                             | Basel Committee, FINMA. Emphasis on supply chain and digital vehicle resilience.                  |


## Essential Learning & Research Resources

| Resource/Community                                                                  | Type              | Description/Notes                               |
|-------------------------------------------------------------------------------------|-------------------|------------------------------------------------|
| [The Car Hacker’s Handbook (Craig Smith)](https://nostarch.com/carhacking)          | Book              | Comprehensive guide to car security            |
| [Hacking Connected Cars](https://www.amazon.com/gp/product/1119491761/)             | Book              | Techniques and procedures book                 |
| [ICSim](https://github.com/zombieCraig/ICSim)                                       | Toolkit/Software  | CAN cluster simulation                         |
| [can-utils](https://github.com/linux-can/can-utils)                                 | Toolkit/Software  | CAN bus open-source tools                      |
| [python-can](https://pypi.org/project/python-can/)                                  | Toolkit/Software  | Python CAN bus library                         |
| [Scapy/CAN Layer](https://dissec.to/kb/chapters/can/can-scapy.html)                 | Toolkit/Software  | CAN protocol analysis                          |
| [DEF CON Car Hacking Village](https://www.carhackingvillage.com/)                   | Community/Event   | Global in-person and virtual hands-on events   |
| [Car Hacking Village @ DefCamp](https://def.camp/car-hacking-village/)              | Community/Event   | European CTF/hack venue                        |
| [ASRG](https://asrg.io/)                                                            | Community         | Auto Security Research Group: global research  |
| [Open Garages](https://github.com/openGarages)                                      | Forum/Repo        | Tutorials, datasets, simulation kits           |
| [Upstream Security Reports](https://upstream.auto/reports/global-automotive-cybersecurity-report/) | Research/Survey   | Trends, vulnerabilities, industry survey       |
| [The Hacker News: API survey](https://thehackernews.com/2023/01/millions-of-vehicles-at-risk-api.html) | News/Research     | Mass API attack reports                        |
| [arXiv: UWBAD paper](https://arxiv.org/abs/2407.00682)                              | Research          | Ultra-Wideband relay attack research           |
| [arXiv: SAE J1939 attacks](https://arxiv.org/abs/2406.00810)                        | Research          | Heavy-duty transport attacks                   |
| [ScienceDirect: HD vehicle review](https://www.sciencedirect.com/science/article/pii/S0167404825001415) | Research          | Heavy vehicle vulnerabilities                  |
| [MDPI Sensors: SDV security](https://www.mdpi.com/1424-8220/24/18/6139)             | Research/Survey   | Survey on frameworks/attacks                   |
| [VicOne Zero-Day Database](https://vicone.com/automotive-zero-day-vulnerabilities)  | Vulnerability DB  | Live CVE, 0-day tracking                       |

---

## Getting Started with Car Hacking (Today)

- **Read:** [The Car Hacker’s Handbook](https://nostarch.com/carhacking)
- **Practice:** Use [ICSim](https://github.com/zombieCraig/ICSim), [ELM327](https://www.amazon.com/dp/B07SK6MJT1/), [CANtact](http://linklayer.github.io/cantact/) on test benches.
- **Engage:** [ASRG](https://asrg.io/), [Open Garages](https://github.com/openGarages), [DEF CON Car Hacking Village](https://www.carhackingvillage.com/)
- **Stay Current:** [Upstream Reports](https://upstream.auto/reports/global-automotive-cybersecurity-report/), [arXiv search: automotive security](https://arxiv.org/search/cs?searchtype=author&query=automotive+security), [HackerNews](https://thehackernews.com/search?q=automotive)

---

## Summary Timeline of Milestones

- **1990s–2000s:** OBD/CAN bus hacking ([CAN bus](https://en.wikipedia.org/wiki/CAN_bus))
- **2010–2014:** [Chevy Malibu hack (Wired)](https://www.wired.com/2011/03/hackers-car/), [CAN-utils](https://github.com/linux-can/can-utils), [ELM327](https://www.amazon.com/dp/B07SK6MJT1/)
- **2015:** [Jeep UConnect hack](https://www.wired.com/2015/07/hackers-remotely-kill-jeep-highway/), [DEF CON Car Hacking Village](https://www.carhackingvillage.com/)
- **2016–2018:** [BMW](https://www.wired.com/2015/01/hackers-remotely-unlock-dozens-bmw-models/), [Tesla](https://www.wired.com/2016/09/tesla-hack-can-remote-control-brakes-and-more/), [ICSim](https://github.com/zombieCraig/ICSim)
- **2019–2025:** [API hacks survey](https://thehackernews.com/2023/01/millions-of-vehicles-at-risk-api.html), [Upstream Report](https://upstream.auto/reports/global-automotive-cybersecurity-report/), [VicOne 0-days](https://vicone.com/automotive-zero-day-vulnerabilities)

---

##  Curated Modern Automotive Security List (2025)

### Approach & Methodology

- In-Vehicle Network, Hardware Hacking, Firmware, Wireless, Mobile App, Cloud/Telemetry, AI-based Security, Supply Chain, Mobility.

### Communities & Events

- [ASRG](https://asrg.io/)
- [Auto-ISAC](https://automotiveisac.com/)
- [Car Hacking Village – DEF CON](https://www.carhackingvillage.com/)
- [Pwn2Own Automotive](https://www.automotiveworld.jp/tokyo/en-gb/conference/pwn2own.html)
- [Automotive Cybersecurity Detroit 2025](https://www.automotive-iq.com/events-automotive-cybersecurity/agenda-mc)
- [Auto-ISAC Europe Summit 2025](https://automotiveisac.com/2025-europe-summit)
- [escar Europe 2025](https://easychair.org/cfp/escarEurope2025)

### Educational Resources

- [Car Hacker’s Handbook](https://nostarch.com/carhacking)
- [Hacking Connected Cars](https://www.amazon.com/gp/product/1119491761/)
- [ASRG YouTube](https://www.youtube.com/@automotivesecurityresearch1613)
- [Car Hacking Village YouTube](https://www.youtube.com/@carhackingvillage)
- [CANisLabs Blog](https://kentindell.github.io/)
- [CANBusHack Blog](https://canbushack.com/blog/)

### Tools & Platforms

#### Hardware
- [Nano-CAN](https://github.com/mintynet/nano-can)
- [USBtin](http://www.fischl.de/usbtin/)
- [USB2CAN](http://www.8devices.com/products/usb2can/)
- [CANPico](https://canislabs.com/canpico/)
- [OBD-KILL](https://store.intrepidcs.com/product/chv-badge-30)
- [ELM327](https://www.amazon.com/dp/B07SK6MJT1/)
- [CANtact](http://linklayer.github.io/cantact/)
- [Macchina M2](https://www.macchina.cc/)

#### Software
- [can-utils](https://github.com/linux-can/can-utils)
- [ICSim](https://github.com/zombieCraig/ICSim/)
- [UDSim](https://github.com/zombieCraig/UDSim/)
- [CANalyse 2.0](https://github.com/canalyse/CANalyse-2.0)
- [CANToolz](https://github.com/eik00d/CANToolz)
- [CANalyzat0r](https://github.com/schutzwerk/CANalyzat0r)

#### Libraries
- [python-can](https://pypi.org/project/python-can/)
- [Scap CAN Layer](https://dissec.to/kb/chapters/can/can-scapy.html)

#### Lists & Platforms
- [Awesome Vehicle Security](https://github.com/jaredthecoder/awesome-vehicle-security)
- [wtsxDev/Vehicle-Security](https://github.com/wtsxDev/Vehicle-Security)
- [Carpunk](https://github.com/souravbaghz/Carpunk)
- [pq-flasher](https://github.com/I-CAN-hack/pq-flasher)
- [FOSSA for Automotive](https://fossa.com/industries/manufacturing-autos/)
- [GitGuardian for Automotive](https://www.gitguardian.com/industries/automotive)

### Research, Papers & Vulnerabilities

- [UWBAD – Ultra-Wideband Keyless Entry Jamming (arXiv)](https://arxiv.org/abs/2407.00682)
- [SAE J1939 Attacks (arXiv)](https://arxiv.org/abs/2406.00810)
- [ScienceDirect: Heavy-Duty Vehicle Security Review](https://www.sciencedirect.com/science/article/pii/S0167404825001415)
- [MDPI Sensors: Survey on SDV Security](https://www.mdpi.com/1424-8220/24/18/6139)
- [VicOne Automotive Zero-Day Vulnerabilities](https://vicone.com/automotive-zero-day-vulnerabilities)
- [The Hacker News – API Vulnerability Survey](https://thehackernews.com/2023/01/millions-of-vehicles-at-risk-api.html)
- [Upstream: 2025 Global Automotive Cybersecurity Report](https://upstream.auto/reports/global-automotive-cybersecurity-report/)


---

**Reference Resource Links:**
- [UNECE WP.29 Regulation Summary](https://unece.org/transport/vehicle-regulations/notifications-un-regulations/r155)
- [ISO/SAE 21434 Standard Overview](https://www.iso.org/standard/70918.html)
- [Auto-ISAC Best Practices](https://www.automotiveisac.com/best-practices/)
- [ENISA Automotive Cybersecurity](https://www.enisa.europa.eu/publications/cybersecurity-challenges-in-the-updated-automotive-homologation-regulation)
- [China MIIT](http://www.miit.gov.cn)
- [DCMS Consumer IoT Code of Practice](https://www.gov.uk/government/publications/code-of-practice-for-consumer-iot-security)
- [Australian Cyber Security Centre Automotive Guidance](https://www.cyber.gov.au/acsc/view-all-content/publications/securing-connected-vehicles)
- [BNetzA IT Security Catalogue](https://www.bundesnetzagentur.de/EN/Areas/Energy/Companies/Security_of_supply/IT_Security_Catalogue/IT_Security_Catalogue_node.html)



### New & Emerging Threats

- AI Security & Prompt Injection
- Automotive Software Supply Chain Security
- Connected Mobility & Telematics API Security
- EV Charging Infrastructure Vulnerabilities
- Ransomware & Data Breach Response

### Recommendations

- Monitor live vulnerability and supply chain intelligence portals (e.g., [VicOne](https://vicone.com/automotive-zero-day-vulnerabilities), [FOSSA](https://fossa.com/industries/manufacturing-autos/), [GitGuardian](https://www.gitguardian.com/industries/automotive)).
- Engage at [DEF CON Car Hacking Village](https://www.carhackingvillage.com/), [Auto-ISAC Summits](https://automotiveisac.com/), and [Pwn2Own Automotive](https://www.automotiveworld.jp/tokyo/en-gb/conference/pwn2own.html).
- Follow and contribute to open-source and research repositories.
- Stay updated with [Upstream Reports](https://upstream.auto/reports/global-automotive-cybersecurity-report/), and adapt to regulatory and threat intelligence changes.

---

*This guide covers car hacking’s journey from early OBD/CAN explorations to today’s cloud, API, and AI security challenges - linking you directly to key reference points and resources at each stage.*

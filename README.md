![](https://github.com/V33RU/IoTSecurity101/blob/master/logo.png)

![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) 


********************************************************************************************************************************
#### Approach Methodology

 - ***1. Network***
 - ***2. Web (Front & Backend and Web services)***
 - ***3. Mobile App (Android & iOS)***
 - ***4. Wireless Connectivity (Zigbee , WiFi , Bluetooth , etc)***
 - ***5. Firmware Pentesting (OS of IoT Devices)***
 - ***6. Hardware Hacking & Fault Injections & SCA Attacks***
 - ***7. Storage Medium***
 - ***8. I/O Ports***
 
 
## Contents 
 
 - IoT Security information
   - [IoT Security Chat groups](#Chat-groups-for-IoT-Security)
   - [Books](#Books-For-IoT-Pentesting)
   - [Blogs](#Blogs-for-iotpentest)
   - [Cheatsheets](#Awesome-CheatSheets)
   - [Search Engines](#Search-Engines-for-IoT-Openly-devices)
   - [CTF](#CTF-For-IoT-And-Embeddded)
   - [Youtube](#YouTube-Channels-for-IoT-Pentesting)
   - [Exploitation Tools](#Exploitation-Tools)
   - [IoT Pentesting OSes](#IoT-Pentesting-OSes)
   - [IoT Vulnerabilites Checking Guides](#IoT-Vulnerabilites-Checking-Guides)
   - [IoT Labs](#Vulnerable-IoT-and-Hardware-Applications)
   - [Awesome IoT Pentesting Guides](#Awesome-IoT-Pentesting-Guides)
   
 - Network
 - Web IoT Message Protocols
 	- [MQTT](#MQTT)
	- [CoAP](#CoAP)
	
 - Mobile app
 	- [Mobile security (Android & iOS)](#Mobile-security-(Android-&-iOS))
	
 - Wireless Protocols
 	- [RADIO HACKING STARTING GUIDE](#RADIO-HACKER-QUICK-START-GUIDE)
 	- [Cellular Hacking GSM BTS](#cellular-hacking-gsm-bts)
	- [Zigbee](#Zigbee-ALL-Stuff)
	- [Bluetooth](#BLE-Intro-and-SW-HW-Tools-to-pentest)

 - Firmware
 	- [Reverse Engineering Tools](#Reverse-Engineering-Tools)
	- [Online Assemblers](#Online-Assemblers)
	- [ARM](#ARM)
	- [Pentesting Firmwares and emulating and analyzing](#Pentesting-Firmwares-and-emulating-and-analyzing)
	- [Firmware samples to pentest](#Firmware-samples-to-pentest)
	- [Bootloader](#Bootloader)
	
	
 - Hardware
    - [IoT Hardware Intro](#IoT-hardware-Overview-and-Hacking)
    - [IoT Hardware hacking Intro]
    - [Required hardware to pentest IoT](#Hardware-Gadgets-to-pentest)
    - [Hardware interfaces](#Attacking-Hardware-Interfaces)
   	- [SPI](#SPI)
 	- [UART](#UART)
	- [JTAG](#JTAG)
    - [SideChannel Attacks & Glitching attacks](#SideChannel-Attacks-and-Glitching-attacks)
	
 - [Storage Medium](#Storage-Medium)
  
********************************************************************************************************************************
### To seen Hacked devices

- https://blog.exploitee.rs/2018/10/
- https://www.exploitee.rs/
- https://forum.exploitee.rs/
- [Your Lenovo Watch X Is Watching You & Sharing What It Learns](https://www.checkmarx.com/blog/lenovo-watch-watching-you/)
- [Your Smart Scale is Leaking More than Your Weight: Privacy Issues in IoT](https://www.checkmarx.com/blog/smart-scale-privacy-issues-iot/)
- [Smart Bulb Offers Light, Color, Music, and… Data Exfiltration?](https://www.checkmarx.com/blog/smart-bulb-exfiltration/)
- [Besder-IPCamera analysis](http://blog.0x42424242.in/2019/04/besder-investigative-journey-part-1_24.html)
- [Smart Lock](https://blog.rapid7.com/2019/08/01/r7-2019-18-multiple-hickory-smart-lock-vulnerabilities/)
- [Subaru Head Unit Jailbreak](https://github.com/sgayou/subaru-starlink-research/blob/master/doc/README.md)
- [Jeep Hack](http://illmatics.com/Remote%20Car%20Hacking.pdf)
- [Dropcam hacking](https://www.defcon.org/images/defcon-22/dc-22-presentations/Moore-Wardle/DEFCON-22-Colby-Moore-Patrick-Wardle-Synack-DropCam-Updated.pdf)
- [Printer Hacking live sessions - gamozolabs](https://www.youtube.com/playlist?list=PLSkhUfcCXvqHS4Bqz804OAZqND6bk7OG6)


********************************************************************************************************************************
### Chat groups for IoT Security

- IoTSecurity101 Telegram - <https://t.me/iotsecurity1011>
- IoTSecurity101 Reddit   - <https://www.reddit.com/r/IoTSecurity101/>
- IoTSecurity101 Discord  -  <https://discord.gg/EH9dxT9>
- hardware hacking Telegram - <https://t.me/hardwareHackingBrasil>
- NForceIT Telegram 	-  <https://t.me/joinchat/JAMxOg5YzdkGjcF3HmNgQw>
- RFID Discord group  - <https://discord.gg/Z43TrcVyPr>
- ICS Discord group   - <https://discord.com/invite/CmDDsFK>

********************************************************************************************************************************
### Books For IoT Pentesting

- [The Firmware Handbook (Embedded Technology) 1st Edition
by Jack Ganssle ](https://www.amazon.com/Firmware-Handbook-Embedded-Technology/dp/075067606X) - 2004
- [Hardware Hacking: Have Fun while Voiding your Warranty 1st Edition  ](https://www.elsevier.com/books/hardware-hacking/grand/978-1-932266-83-2) - 2004
- [Linksys WRT54G Ultimate Hacking 1st Edition by Paul Asadoorian](https://www.amazon.com/Linksys-WRT54G-Ultimate-Hacking-Asadoorian/dp/1597491667) - 2007
- [Applied Cyber Security and the Smart Grid: Implementing Security Controls into the Modern Power Infrastructure by Eric D. Knapp , Raj Samani](https://www.amazon.com/Applied-Cyber-Security-Smart-Grid/dp/1597499986/) -2013
- [Hacking the Xbox-An Introduction to Reverse Engineering HACKING THE XBOX by Andrew “bunnie” Huang](https://www.nostarch.com/xboxfree) - Openbook - 2013
- [Android Hacker's Handbook by Joshua J. Drake](https://www.amazon.in/Android-Hackers-Handbook-MISL-WILEY-Joshua/dp/812654922X) - 2014
- [The Art of Pcb Reverse Engineering: Unravelling the Beauty of the Original Design ](https://www.amazon.in/Art-Pcb-Reverse-Engineering-Unravelling/dp/1499323441) - 2015
- [Abusing the Internet of Things: Blackouts, Freakouts, and Stakeouts 1st Edition, by Nitesh Dhanjani](https://www.amazon.in/Abusing-Internet-Things-Blackouts-Freakouts-ebook/dp/B013VQ7N36) - 2015
- [Learning Linux Binary Analysis By Ryan "elfmaster" O'Neill](https://www.packtpub.com/networking-and-servers/learning-linux-binary-analysis) - 2016
- [Car hacker's handbook by Craig Smith](http://opengarages.org/handbook) - 2016
- [IoT Penetration Testing Cookbook By Aaron Guzman , Aditya Gupta](https://www.packtpub.com/networking-and-servers/iot-penetration-testing-cookbook) - 2017
- [Inside Radio: An Attack and Defense Guide by Authors: Yang, Qing, Huang, Lin](https://books.google.co.in/books?id=71NSDwAAQBAJ&printsec=copyright&redir_esc=y#v=onepage&q&f=false) -2018
- [Pentest Hardware](https://github.com/unprovable/PentestHardware/) - Openbook -2018
- [Gray Hat Hacking: The Ethical Hacker's Handbook, Fifth Edition 5th Edition by by Daniel Regalado , Shon Harris , Allen Harper , Chris Eagle , Jonathan Ness , Branko Spasojevic , Ryan Linn , Stephen Sims](https://www.amazon.in/Gray-Hat-Hacking-Ethical-Handbook-ebook/dp/B07D3J9J4H) - 2018
- [The Hardware Hacking Handbook: Breaking Embedded Security with Hardware Attacks Front Cover Jasper van Woudenberg, Colin O'Flynn](https://books.google.co.in/books?id=DEqatAEACAAJ&source=gbs_navlinks_s) - 2021
- [Practical IoT Hacking-The Definitive Guide to Attacking the Internet of Things
by Fotios Chantzis, Ioannis Stais, Paulino Calderon, Evangelos Deirmentzoglou, Beau Woods](https://nostarch.com/practical-iot-hacking) - 2021
- [Internet of Things Security Encyclopedia](https://iot-security.wiki/) - Openbook

********************************************************************************************************************************
### Blogs for iotpentest

- https://payatu.com/blog/
- https://raelize.com/blog/
- http://jcjc-dev.com/
- https://w00tsec.blogspot.in/
- http://www.devttys0.com/
- https://wrongbaud.github.io/
- https://embeddedbits.org/
- https://www.rtl-sdr.com/
- https://keenlab.tencent.com/en/
- https://courk.cc/
- https://iotsecuritywiki.com/
- https://cybergibbons.com/
- http://firmware.re/
- http://blog.k3170makan.com/
- https://blog.tclaverie.eu/
- http://blog.besimaltinok.com/category/iot-pentest/
- https://ctrlu.net/
- http://iotpentest.com/
- https://blog.attify.com
- https://duo.com/decipher/
- http://www.sp3ctr3.me
- http://blog.0x42424242.in/
- https://dantheiotman.com/
- https://blog.danman.eu/
- https://quentinkaiser.be/
- https://blog.quarkslab.com
- https://blog.ice9.us/
- https://labs.f-secure.com/ 
- https://mg.lol/blog/
- https://cjhackerz.net/
- https://github.com/sponsors/bunnie/
- https://iotmyway.wordpress.com/
- https://www.synacktiv.com/publications.html
- http://blog.cr4.sh/

********************************************************************************************************************************
### Awesome CheatSheets

- [Hardware Hacking](https://github.com/arunmagesh/hw_hacking_cheatsheet)
- [Nmap](https://github.com/gnebbia/nmap_tutorial)

********************************************************************************************************************************
### Search Engines for IoT Openly devices

- [Shodan](https://www.shodan.io/)
- [FOFA](https://fofa.so/?locale=en)
- [Censys](https://censys.io/)
- [Zoomeye](https://www.zoomeye.org/about)
- [ONYPHE](https://www.onyphe.io/)

********************************************************************************************************************************
### CTF For IoT And Embeddded

- https://github.com/hackgnar/ble_ctf
- https://www.microcorruption.com/
- https://github.com/Riscure/Rhme-2016
- https://github.com/Riscure/Rhme-2017
- https://blog.exploitlab.net/2018/01/dvar-damn-vulnerable-arm-router.html
- https://github.com/scriptingxss/IoTGoat

********************************************************************************************************************************
### YouTube Channels for IoT Pentesting

- [Liveoverflow](https://www.youtube.com/channel/UClcE-kVhqyiHCcjYwcpfj9w)
- [Binary Adventure](https://www.youtube.com/channel/UCSLlgiYtOXZnYPba_W4bHqQ)
- [EEVBlog](https://www.youtube.com/user/EEVblog)
- [JackkTutorials](https://www.youtube.com/channel/UC64x_rKHxY113KMWmprLBPA)
- [Craig Smith](https://www.youtube.com/channel/UCxC8G4Oeed4N0-GVeDdFoSA)
- [iotpentest [Mr-IoT]](https://www.youtube.com/channel/UCe2mJv2FPRFhYJ7dvNdYR4Q)
- [Besim ALTINOK - IoT - Hardware - Wireless](https://www.youtube.com/channel/UCnIV7A3kDL4JXJEljpW6TRQ/playlists)
- [Ghidra Ninja](https://www.youtube.com/channel/UC3S8vxwRfqLBdIhgRlDRVzw)
- [Cyber Gibbons](https://www.youtube.com/channel/UC_IYERSoSwdR7AA5P41mYTA)
- [Scanline](https://www.youtube.com/channel/UCaEgw3321ct_PE4PJvdhXEQ)

********************************************************************************************************************************
### Vehicle Security Resources

- https://github.com/jaredthecoder/awesome-vehicle-security

********************************************************************************************************************************
### IoT Vulnerabilites Checking Guides

- [Reflecting upon OWASP TOP-10 IoT Vulnerabilities](https://embedi.org/blog/reflecting-upon-owasp-top-10-iot-vulnerabilities/)
- [OWASP IoT Top 10 2018 Mapping Project](https://scriptingxss.gitbook.io/owasp-iot-top-10-mapping-project/)
- [Hardware toolkits for IoT security analysis](https://defcon-nn.ru/0x0B/Hardware%20toolkits%20for%20IoT%20security%20analysis.pdf)

********************************************************************************************************************************
### IoT Gateway Software

- [Webthings by Mozilla - RaspberryPi](https://iot.mozilla.org/docs/gateway-getting-started-guide.html)

********************************************************************************************************************************
### IoT Pentesting OSes

- [Sigint OS- LTE IMSI Catcher](https://www.sigintos.com/downloads/)
- [Instatn-gnuradio OS - For Radio Signals Testing](https://github.com/bastibl/instant-gnuradio)
- [AttifyOS - IoT Pentest OS - by Aditya Gupta](https://github.com/adi0x90/attifyos)
- [Ubutnu Best Host Linux for IoT's - Use LTS](https://www.ubuntu.com/)
- [Internet of Things - Penetration Testing OS](https://github.com/IoT-PTv)
- [Dragon OS - DEBIAN LINUX WITH PREINSTALLED OPEN SOURCE SDR SOFTWARE](https://www.rtl-sdr.com/dragonos-debian-linux-with-preinstalled-open-source-sdr-software/)
- [EmbedOS - Embedded security testing virtual machine](https://github.com/scriptingxss/EmbedOS)
- [Skywave Linux- Software Defined Radio for Global Online Listening](https://skywavelinux.com/)
- [A Small, Scalable Open Source RTOS for IoT Embedded Devices](https://www.zephyrproject.org/)
- [ICS - Controlthings.io](https://www.controlthings.io/platform)

********************************************************************************************************************************
### Exploitation Tools

- [Expliot - IoT Exploitation framework - by Aseemjakhar](https://gitlab.com/expliot_framework/expliot)
- [Routersploit (Exploitation Framework for Embedded Devices)](https://github.com/threat9/routersploit)
- [IoTSecFuzz (comprehensive testing for IoT device)](https://gitlab.com/invuls/iot-projects/iotsecfuzz)
- [HomePwn - Swiss Army Knife for Pentesting of IoT Devices](https://github.com/ElevenPaths/HomePWN)
- [killerbee - Zigbee exploitation](https://github.com/riverloopsec/killerbee)
- [PRET - Printer Exploitation Toolkit](https://github.com/RUB-NDS/PRET)
- [HAL – The Hardware Analyzer](https://github.com/emsec/hal)
- [FwAnalyzer (Firmware Analyzer)](https://github.com/cruise-automation/fwanalyzer)
- [ISF(Industrial Security Exploitation Framework](https://github.com/w3h/isf)
- [PENIOT: Penetration Testing Tool for IoT](https://github.com/yakuza8/peniot)
- [MQTT-PWN](https://github.com/akamai-threat-research/mqtt-pwn)

********************************************************************************************************************************
### Reverse Engineering Tools

- [IDA Pro](https://www.youtube.com/watch?v=fgMl0Uqiey8)
- [GDB](https://www.youtube.com/watch?v=fgMl0Uqiey8)
- [Radare2](https://radare.gitbooks.io/radare2book/content/) | [cutter](https://cutter.re/)
- [Ghidra](https://ghidra-sre.org/)

********************************************************************************************************************************
## Introduction

- [Introduction to IoT](https://en.wikipedia.org/wiki/Internet_of_things)
- [IoT Architecture](https://www.c-sharpcorner.com/UploadFile/f88748/internet-of-things-part-2/)
- [IoT attack surface](https://www.owasp.org/index.php/IoT_Attack_Surface_Areas)
- [IoT Protocols Overview](https://www.postscapes.com/internet-of-things-protocols/) 

********************************************************************************************************************************
### IoT Web and message services 

#### MQTT

- [Introduction](https://www.hivemq.com/blog/mqtt-essentials-part-1-introducing-mqtt)
- [Hacking the IoT with MQTT](https://morphuslabs.com/hacking-the-iot-with-mqtt-8edaf0d07b9b)
- [thoughts about using IoT MQTT for V2V and Connected Car from CES 2014](https://mobilebit.wordpress.com/tag/mqtt/)
- [Nmap](https://nmap.org/nsedoc/lib/mqtt.html)
- [The Seven Best MQTT Client Tools](https://www.hivemq.com/blog/seven-best-mqtt-client-tools)
- [A Guide to MQTT by Hacking a Doorbell to send Push Notifications](https://youtu.be/J_BAXVSVPVI)
- [Are smart homes vulnerable to hacking](https://blog.avast.com/mqtt-vulnerabilities-hacking-smart-homes)
- [Deep Learning UDF for KSQL / ksqlDB for Streaming Anomaly Detection of MQTT IoT Sensor Data](https://github.com/kaiwaehner/ksql-udf-deep-learning-mqtt-iot)
- [Authenticating & Authorizing Devices using MQTT with Auth0](https://auth0.com/docs/integrations/authenticate-devices-using-mqtt)
- [Development information for the MQTT with hardware](https://www.hackster.io/search?i=projects&q=Mqtt)
- [Understanding the MQTT Protocol Packet Structure](http://www.steves-internet-guide.com/mqtt-protocol-messages-overview/)
- [R7-2019-18: Multiple Hickory Smart Lock Vulnerabilities](https://blog.rapid7.com/2019/08/01/r7-2019-18-multiple-hickory-smart-lock-vulnerabilities/)
- [IoT Live Demo: 100.000 Connected Cars With Kubernetes, Kafka, MQTT, TensorFlow](https://dzone.com/articles/iot-live-demo-100000-connected-cars-with-kubernete)


#### Softwares
- [Mosquitto-An open source MQTT broker](https://mosquitto.org/)
- [HiveMQ](https://www.hivemq.com/)
- [MQTT Explorer](http://mqtt-explorer.com/)
- [MQTT proxy - IoXY](https://blog.nviso.eu/2020/07/06/introducing-ioxy-an-open-source-mqtt-intercepting-proxy/)
- [MQTT Broker Security - 101](https://payatu.com/blog/dattatray/iot-security-%E2%80%93-part-12-mqtt-broker-security---101)
- [Welcome to MQTT-PWN!](https://mqtt-pwn.readthedocs.io/en/latest/)

#### CoAP

- [Introduction](http://coap.technology/)
- [CoAP client Tools](http://coap.technology/tools.html)
- [CoAP Pentest Tools](https://bitbucket.org/aseemjakhar/expliot_framework)
- [Nmap - NSE for coap](https://nmap.org/nsedoc/lib/coap.html)


********************************************************************************************************************************
### RADIO HACKER QUICK START GUIDE

- [SDR Notes - Radio IoT Protocols Overview](https://github.com/notpike/SDR-Notes)
- [Understanding Radio](https://www.taitradioacademy.com/lessons/introduction-to-radio-communications-principals/)
- [Introduction to Software Defined Radio](https://www.allaboutcircuits.com/technical-articles/introduction-to-software-defined-radio/)
- [Introduction Gnuradio companion](https://wiki.gnuradio.org/index.php/Guided_Tutorial_GRC#Tutorial:_GNU_Radio_Companion)
- [Creating a flow graph in gunradiocompanion](https://blog.didierstevens.com/2017/09/19/quickpost-creating-a-simple-flow-graph-with-gnu-radio-companion/)
- [Analysing radio signals 433Mhz ](https://www.rtl-sdr.com/analyzing-433-mhz-transmitters-rtl-sdr/)
- [Recording specific radio signal](https://www.rtl-sdr.com/freqwatch-rtl-sdr-frequency-scanner-recorder/)
- [Replay Attacks with raspberrypi -rpitx](https://www.rtl-sdr.com/tutorial-replay-attacks-with-an-rtl-sdr-raspberry-pi-and-rpitx/)

### Cellular Hacking GSM BTS

#### BTS

- [Awesome-Cellular-Hacking](https://github.com/W00t3k/Awesome-Cellular-Hacking/blob/master/README.md)
- [what is base tranceiver station](https://en.wikipedia.org/wiki/Base_transceiver_station)
- [How to Build Your Own Rogue GSM BTS](https://l33t.gg/how-to-build-a-rogue-gsm-bts/)

#### GSM SS7 Pentesting

- [Introduction to GSM Security](http://www.pentestingexperts.com/introduction-to-gsm-security/)
- [GSM Security 2 ](https://www.ehacking.net/2011/02/gsm-security-2.html)
- [vulnerabilities in GSM security with USRP B200](https://ieeexplore.ieee.org/document/7581461/)
- [Security Testing 4G (LTE) Networks](https://labs.mwrinfosecurity.com/assets/BlogFiles/mwri-44con-lte-presentation-2012-09-11.pdf)
- [Case Study of SS7/SIGTRAN Assessment](https://nullcon.net/website/archives/pdf/goa-2017/case-study-of-SS7-sigtran.pdf)
- [Telecom Signaling Exploitation Framework - SS7, GTP, Diameter & SIP](https://github.com/SigPloiter/SigPloit)
- [ss7MAPer – A SS7 pen testing toolkit](https://n0where.net/ss7-pentesting-toolkit-ss7maper)
- [Introduction to SIGTRAN and SIGTRAN Licensing](https://www.youtube.com/watch?v=XUY6pyoRKsg)
- [SS7 Network Architecture](https://youtu.be/pg47dDUL1T0)
- [Introduction to SS7 Signaling](https://www.patton.com/whitepapers/Intro_to_SS7_Tutorial.pdf)
- [Breaking LTE on Layer Two](https://alter-attack.net/)

********************************************************************************************************************************
### Zigbee ALL Stuff

- [Introduction and protocol Overview](http://www.informit.com/articles/article.aspx?p=1409785)
- [Hacking Zigbee Devices with Attify Zigbee Framework](https://blog.attify.com/hack-iot-devices-zigbee-sniffing-exploitation/)
- [Hands-on with RZUSBstick](https://uk.rs-online.com/web/p/radio-frequency-development-kits/6962415/) 
- [ZigBee & Z-Wave Security Brief](http://www.riverloopsecurity.com/blog/2018/05/zigbee-zwave-part1/)
- [Hacking ZigBee Networks](https://resources.infosecinstitute.com/topic/hacking-zigbee-networks/)
- [Zigator: Analyzing the Security of Zigbee-Enabled Smart Homes](https://mews.sv.cmu.edu/papers/wisec-20.pdf)
- [Security Analysis of Zigbee Networks with Zigator and GNU Radio](https://mews.sv.cmu.edu/research/zigator/testbed-grcon2020-slides.pdf)
- [Low-Cost ZigBee Selective Jamming](https://www.bastibl.net/reactive-zigbee-jamming/)

#### SW TOOLS
- [zigbear](https://github.com/philippnormann/zigbear)
- [ZigDiggity](https://github.com/BishopFox/zigdiggity)
- [Zigator](https://github.com/akestoridis/zigator)
- [Z3sec](https://github.com/IoTsec/Z3sec)


#### Hardware Tools for Zigbee
- [APIMOTE IEEE 802.15.4/ZIGBEE SNIFFING HARDWARE](https://www.riverloopsecurity.com/projects/apimote/)
- [RaspBee-The Raspberry Pi Zigbee gateway](https://phoscon.de/en/raspbee/)
- [USRP SDR 2](https://www.ettus.com/products/)
- [ATUSB IEEE 802.15.4 USB Adapter](http://shop.sysmocom.de/products/atusb)
- [nRF52840-Dongle](https://www.nordicsemi.com/Software-and-tools/Development-Kits/nRF52840-Dongle)
- []()

********************************************************************************************************************************
### BLE Intro and SW-HW Tools to pentest

- [Step By Step guide to BLE Understanding and Exploiting](https://github.com/V33RU/BLE-NullBlr)
- [Traffic Engineering in a  Bluetooth Piconet](http://www.diva-portal.org/smash/get/diva2:833159/FULLTEXT01.pdf)
- [BLE Characteristics](https://devzone.nordicsemi.com/nordic/short-range-guides/b/bluetooth-low-energy/posts/ble-characteristics-a-beginners-tutorial)
  
  
 #### Bluetooth and BLE Pentest Tools
 
   - [btproxy](https://github.com/conorpp/btproxy)
   - [hcitool & bluez](https://www.pcsuggest.com/linux-bluetooth-setup-hcitool-bluez)
   - [Testing With GATT Tool](https://www.jaredwolff.com/blog/get-started-with-bluetooth-low-energy/)
   - [Cracking encryption](https://github.com/mikeryan/crackle)
   - [bettercap](https://github.com/bettercap/bettercap)
   - [BtleJuice Bluetooth Smart Man-in-the-Middle framework](https://github.com/DigitalSecurity/btlejuice)
   - [gattacker](https://github.com/securing/gattacker)
   - [BTLEjack Bluetooth Low Energy Swiss army knife](https://github.com/virtualabs/btlejack)
    
 
 #### Hardware for bluetooth hacking
  
   - [NRFCONNECT - 52840](https://www.nordicsemi.com/Software-and-tools/Development-Kits/nRF52840-Dongle)
   - [EDIMAX](https://www.nordicsemi.com/Software-and-tools/Development-Kits/nRF52840-Dongle)
   - [CSR 4.0](https://www.amazon.in/GENERIC-Ultra-Mini-Bluetooth-Dongle-Adapter/dp/B0117H7GZ6/ref=asc_df_B0117H7GZ6/?tag=googleshopdes-21&linkCode=df0&hvadid=396984700257&hvpos=1o1&hvnetw=g&hvrand=2179727910417729406&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9061998&hvtargid=pla-343685677347&psc=1&ext_vrnc=hi)
   - [ESP32 - Development and learning Bluetooth](https://www.espressif.com/en/products/hardware/esp32/overview)
   - [Ubertooth](https://github.com/greatscottgadgets/ubertooth/wiki/Ubertooth-One)
   - [Sena 100](http://www.senanetworks.com/ud100-g03.html)

#### BLE Pentesting Tutorials

  - [Bluetooth vs BLE Basics](https://github.com/V33RU/BLE-NullBlr)
  - [Finding bugs in Bluetooth](https://bluetooth.lol/)
  - [Intel Edison as Bluetooth LE — Exploit box](https://medium.com/@arunmag/intel-edison-as-bluetooth-le-exploit-box-a63e4cad6580)
  - [How I Reverse Engineered and Exploited a Smart Massager](https://medium.com/@arunmag/how-i-reverse-engineered-and-exploited-a-smart-massager-ee7c9f21bf33)
  - [My journey towards Reverse Engineering a Smart Band — Bluetooth-LE RE](https://medium.com/@arunmag/my-journey-towards-reverse-engineering-a-smart-band-bluetooth-le-re-d1dea00e4de2)
  - [Bluetooth Smartlocks](https://www.getkisi.com/blog/smart-locks-hacked-bluetooth-ble)
  - [I hacked MiBand 3](https://medium.com/@yogeshojha/i-hacked-xiaomi-miband-3-and-here-is-how-i-did-it-43d68c272391)
  - [GATTacking Bluetooth Smart Devices](https://securing.pl/en/gattacking-bluetooth-smart-devices-introducing-a-new-ble-proxy-tool/index.html)
  - [blueooth beacon vulnerability](https://www.beaconzone.co.uk/blog/category/security/)
  - [Sweyntooth Vulnerabilties](https://asset-group.github.io/disclosures/sweyntooth/)
  - [AIRDROP_LEAK - sniffs BLE traffic and displays status messages from Apple devices](https://github.com/hexway/apple_bleee)

********************************************************************************************************************************
### Mobile security (Android & iOS)

 - [Android App Reverse Engineering 101](https://maddiestone.github.io/AndroidAppRE/)
 - [Android Application pentesting book](https://www.packtpub.com/hardware-and-creative/learning-pentesting-android-devices)
 - [Android Pentest Video Course-TutorialsPoint](https://www.youtube.com/watch?v=zHknRia3I6s&list=PLWPirh4EWFpESLreb04c4eZoCvJQJrC6H)
 - [IOS Pentesting](https://web.securityinnovation.com/hubfs/iOS%20Hacking%20Guide.pdf?)
 - [OWASP Mobile Security Testing Guide](https://owasp.org/www-project-mobile-security-testing-guide/)
 - [Android Tamer - Android Tamer is a Virtual / Live Platform for Android Security professionals](https://androidtamer.com/)
 
 
*******************************************************************************************************************************
### Online Assemblers

- [AZM Online Arm Assembler by Azeria](https://azeria-labs.com/azm/)
- [Online Disassembler](https://onlinedisassembler.com/odaweb/)
- [Compiler Explorer is an interactive online compiler which shows the assembly output of compiled C++, Rust, Go](https://godbolt.org/)
********************************************************************************************************************************
### ARM

- [Azeria Labs](https://azeria-labs.com/)
- [ARM EXPLOITATION FOR IoT](https://www.exploit-db.com/docs/english/43906-arm-exploitation-for-iot.pdf)
- [Damn Vulnerable ARM Router (DVAR)](https://blog.exploitlab.net/2018/01/dvar-damn-vulnerable-arm-router.html)
- [EXPLOIT.EDUCATION](https://exploit.education/)

********************************************************************************************************************************
### Pentesting Firmwares and emulating and analyzing

 - [EMBA-An analyzer for embedded Linux firmware](https://p4cx.medium.com/emba-b370ce503602)
 - [Firmware analysis and reversing](https://www.owasp.org/index.php/IoT_Firmware_Analysis)
 - [IoT Security Verification Standard (ISVS)](https://github.com/OWASP/IoT-Security-Verification-Standard-ISVS)
 - [OWASP Firmware Security Testing Methodology](https://scriptingxss.gitbook.io/firmware-security-testing-methodology/)
 - [Firmware emulation with QEMU](https://www.youtube.com/watch?v=G0NNBloGIvs)
 - [Reversing ESP8266 Firmware](https://boredpentester.com/reversing-esp8266-firmware-part-1/)
 - [Emulating Embedded Linux Devices with QEMU](https://www.novetta.com/2018/02/emulating-embedded-linux-devices-with-qemu/?__cf_chl_captcha_tk__=2167fb6cf097848dbf0dea8e4ecccc66f2a55e55-1585030085-0-AVfO7wG_mHgvnIgeIl-aiKLNW1IMb5IMLyqLOSOLydnZFzhyAyySWgfKvjvllAtYtmpbJjnaTlwyaWiO2kHXH4APqLuott0R7UReYCTZ3u--g4AJBK4eONEL2bTJcAHg3fzmXhrC-3iAqccNQC4jx1RWEz60y_MKFq63NVeoE1pC0EBYWkk7VqDWusBFbgpj6zRNv0ifKLc3oLYJck-oG13jeSbPISVLMCn6bCHVLaTp2gW7qG6GRELIWgdyfP9viyMDSAww3u-R1NmUgRQzctXIYMWH1MdL5p8lqbSpCa160cW3JaZ16IxT7iP1HkCBurx7rCOVP3DAcI8zrc19V9mi-jU9nXIW0Xf9eIpqlUP-R_txfNw4vF10PwIGKmg0Cpl2IDuY1ty3J8koQkdvxfE)
 - [Emulating Embedded Linux Systems with QEMU](https://www.novetta.com/2018/02/emulating-embedded-linux-systems-with-qemu/?__cf_chl_captcha_tk__=9dd83a08cffb28fae75286f63f399c34eec56852-1585030087-0-AblGAUd4LCDVbghNgQyfL5hgPXNC8pUcLIAbPUpx2tBOb_L4gVVc1sZ7Ivg0g--06WpkdpeV-kylZu3T_Yqgr7GdFpc2cKzxATdc_bsEV7uu1ljIctFloHTW_B1vvjFAe3QXdex4kkn2D4HuQiw9WLszvO2Ff8SvvfEpHoBumOavj-c2iXcEb2dDFMoK3_HB_3-y7q_BEAX3xqDCjqz7TpcoIWt-wTSQwRfx-VuBfO87hrTsX43yzq6BNjCE9s15ZQmPp_NouYIHNMnx3augAfkwZBSUA0r43GbA--3jLmJsTe_qvcn7gMz_HAR-GpnA_Usn_cr94VqtyNpl0vEsC1OMf48oBMMoFQJA6Jjn1hGPv5hV4M4aBtJrTnFoRP2YGwxAyNTM3Df9qw1iyBB8r58)
 - [Fuzzing Embedded Linux Devices](https://www.novetta.com/2018/07/fuzzing-embedded-linux-devices/?__cf_chl_captcha_tk__=f07f3f76e61b43f9ae6340e94cf4adeaec87977e-1585030089-0-AYkRNbh1wpUia0P5wBgrRfhf92Uy6Pl2mEEBOXi2FUvxROOJ9obK4ZIS78Y4iCRrMdi3umwQrJEyF0u3EPwHPu3_22f5PwOvVDFC0QwFPyw7LkY5bLuansI_8uoEunuLIEQ1VPIZHFpht1vT0_rW4YrYGc8osJZpubAhXfyZe1G7U_ibpZj9tdrUE6SwgA_Ph0io4LRfbjuvpeM03NHuc1sTTqRVdkWiw47kmr9uSAK10ZmQEvE7zpbpkEJM2slchjdYq6hziM3L5l8vB-eEm_JVxsSHbGfdDM3kSfTw3oXlYkvxvLy_llSyyefuub4yOBrqNgzV1Gj_PDTmuRTMxobGo7vZaRdr2LgOXML58kpG6NTDLb3A4YzwVw9u32ErRh4Ab89vn90RsHlWnU928Oc)
 - [Emulating ARM Router Firmware](https://azeria-labs.com/emulating-arm-firmware/)
 - [Reversing Firmware With Radare](https://www.bored-nerds.com/reversing/radare/automotive/2019/07/07/reversing-firmware-with-radare.html)
 - [Samsung Firmware Magic - Unpacking and Decrypting](https://github.com/chrivers/samsung-firmware-magic)
 - [Qiling & Binary Emulation for automatic unpacking](https://kernemporium.github.io/articles/en/auto_unpacking/m.html)
 - [Reverse engineering with #Ghidra: Breaking an embedded firmware encryption scheme](https://www.youtube.com/watch?v=4urMITJKQQs&ab_channel=stacksmashing)
 - [Simulating and hunting firmware vulnerabilities with Qiling](https://blog.vincss.net/2020/12/pt007-simulating-and-hunting-firmware-vulnerabilities-with-Qiling.html?m=1&s=09)
 
********************************************************************************************************************************
### Firmware samples to pentest

 - [Download From here by firmware.center](https://firmware.center/)

********************************************************************************************************************************
### Bootloader
#### Dev
 - [Writing a Bootloader](http://3zanders.co.uk/2017/10/13/writing-a-bootloader/)


********************************************************************************************************************************


### Storage Medium 
 - [HARDWARE HACKING 101: IDENTIFYING AND DUMPING EMMC FLASH](https://www.riverloopsecurity.com/blog/2020/03/hw-101-emmc/)
 - [EMMC DATA RECOVERY FROM DAMAGED SMARTPHONE](https://dangerouspayload.com/2018/10/24/emmc-data-recovery-from-damaged-smartphone/)
 - [Another bunch of Atricles for EMMC](https://hackaday.com/tag/emmc/)
 - [Unleash your smart-home devices: Vacuum Cleaning Robot Hacking](https://media.ccc.de/v/34c3-9147-unleash_your_smart-home_devices_vacuum_cleaning_robot_hacking#t=1810)

********************************************************************************************************************************
### IoT hardware Overview and Hacking

 - [IoT Hardware Guide](https://www.postscapes.com/internet-of-things-hardware/)	
 
#### Hardware Gadgets to pentest

  - [Bus Pirate](https://www.sparkfun.com/products/12942)
  - [EEPROM reader/SOIC Cable](https://www.sparkfun.com/products/13153)
  - [Jtagulator/Jtagenum](https://www.adafruit.com/product/1550)
  - [Logic Analyzer](https://www.saleae.com/)
  - [The Shikra](https://int3.cc/products/the-shikra)
  - [FaceDancer21 (USB Emulator/USB Fuzzer)](https://int3.cc/products/facedancer21)
  - [RfCat](https://int3.cc/products/rfcat)
  - [Hak5Gear- Hak5FieldKits](https://hakshop.com/)
  - [Ultra-Mini Bluetooth CSR 4.0 USB Dongle Adapter](https://www.ebay.in/itm/Ultra-Mini-Bluetooth-CSR-4-0-USB-Dongle-Adapter-Black-Golden-with-2-yr-wrnty-/332302813975)
  - [Attify Badge - UART, JTAG, SPI, I2C (w/ headers)](https://www.attify-store.com/products/attify-badge-assess-security-of-iot-devices)
  
  
#### Attacking Hardware Interfaces

   - [An Introduction to Hardware Hacking](https://securityboulevard.com/2020/09/an-introduction-to-hardware-hacking/)
   - [Serial Terminal Basics](https://learn.sparkfun.com/tutorials/terminal-basics/all)
   - [Reverse Engineering Serial Ports](http://www.devttys0.com/2012/11/reverse-engineering-serial-ports/)
   - [REVERSE ENGINEERING ARCHITECTURE AND PINOUT OF CUSTOM ASICS](https://sec-consult.com/en/blog/2019/02/reverse-engineering-architecture-pinout-plc/)
   - [ChipWhisperer - Hardware attacks](http://wiki.newae.com/Main_Page)
   

#### SPI

   - [Reading FlashROMS](https://www.youtube.com/watch?v=LxWkA1Uz2aA&ab_channel=Defenceindepth)
   - [Dumping the firmware From Router using BUSPIRATE - SPI Dump](https://www.iotpentest.com/2019/06/dumping-firmware-from-device-using.html)
   - [How to Flash Chip of a Router With a Programmer | TP-Link Router Repair & MAC address change](https://www.youtube.com/watch?v=fbt4OJXJdOc&ab_channel=ElectricalProjects%5BCreativeLab%5D)
   - [Extracting Flash Memory over SPI](https://gracefulsecurity.com/extracting-flash-memory-over-spi/)
   
#### UART

   - [Identifying UART interface](https://www.mikroe.com/blog/uart-serial-communication)
   - [onewire-over-uart](https://github.com/dword1511/onewire-over-uart)
   - [Accessing sensor via UART](http://home.wlu.edu/~levys/courses/csci250s2017/SensorsSignalsSerialSockets.pdf)
   - [Using UART to connect to a chinese IP cam](https://www.davidsopas.com/using-uart-to-connect-to-a-chinese-ip-cam/)
   - [A journey into IoT – Hardware hacking: UART](https://techblog.mediaservice.net/2019/03/a-journey-into-iot-hardware-hacking-uart/)
   - [UARTBruteForcer](https://github.com/FireFart/UARTBruteForcer)
   - [UART Connections and Dynamic analysis on Linksys e1000](https://www.youtube.com/watch?v=ix6rSV2Dj44&ab_channel=Defenceindepth)
   - [Accessing and Dumping Firmware Through UART](https://securityboulevard.com/2020/12/accessing-and-dumping-firmware-through-uart/)

#### JTAG

   - [JTAG Explained (finally!)](https://blog.senr.io/blog/jtag-explained)
   - [Buspirate JTAG Connections - Openocd](https://research.kudelskisecurity.com/2014/05/01/jtag-debugging-made-easy-with-bus-pirate-and-openocd/#:~:text=The%20Bus%20Pirate%20is%20an,protocols%20like%20I%C2%B2C%20and%20SPI.)

#### SideChannel Attacks and Glitching attacks

   - [Side channel attacks](https://yifan.lu/)
   - [Attacks on Implementations of Secure Systems](https://github.com/Yossioren/AttacksonImplementationsCourseBook)
   - [fuzzing, binary analysis, IoT security, and general exploitation](https://github.com/0xricksanchez/paper_collection)
   - [NAND Glitching Attack](http://www.brettlischalk.com/posts/nand-glitching-wink-hub-for-root)
   - [Voltage Glitching Attack]()
   - [Espressif ESP32: Bypassing Encrypted Secure Boot(CVE-2020-13629)](https://raelize.com/blog/espressif-esp32-bypassing-encrypted-secure-boot-cve-2020-13629/)
   - [Voltage Glitching Attack using SySS iCEstick Glitcher](https://www.youtube.com/watch?v=FVUhVewFmxw&feature=youtu.be&ab_channel=SySSPentestTV)
   - [Samy Kamkar - FPGA Glitching & Side Channel Attacks](https://www.youtube.com/watch?v=oGndiX5tvEk)
   - [Hardware Power Glitch Attack (Fault Injection) - rhme2 Fiesta (FI 100)](https://www.youtube.com/watch?v=6Pf3pY3GxBM&ab_channel=LiveOverflow)
   - [Breaking AES with ChipWhisperer - Piece of scake (Side Channel Analysis 100)](https://www.youtube.com/watch?v=FktI4qSjzaE&ab_channel=LiveOverflow)
   - [https://www.youtube.com/watch?v=4urMITJKQQs&ab_channel=stacksmashing](https://arstechnica.com/information-technology/2019/06/researchers-use-rowhammer-bitflips-to-steal-2048-bit-crypto-key/)
   
********************************************************************************************************************************   
### Awesome IoT Pentesting Guides

  - [Shodan Pentesting Guide](https://community.turgensec.com/shodan-pentesting-guide/)
  - [Car Hacking Practical Guide 101](https://medium.com/@yogeshojha/car-hacking-101-practical-guide-to-exploiting-can-bus-using-instrument-cluster-simulator-part-i-cd88d3eb4a53)
  - [OWASP Firmware Security Testing Methodology
](https://scriptingxss.gitbook.io/firmware-security-testing-methodology/)
  - [awesome-bluetooth-security](https://github.com/engn33r/awesome-bluetooth-security)
  - [Firmware Pentest Guide](https://scriptingxss.gitbook.io/firmware-security-testing-methodology/)

 
******************************************************************************************************************************** 
## Vulnerable IoT and Hardware Applications

  - IoT Goat : https://github.com/scriptingxss/IoTGoat

  - IoT : https://github.com/Vulcainreo/DVID

  - Safe : https://insinuator.net/2016/01/damn-vulnerable-safe/

  - Router : https://github.com/praetorian-code/DVRF

  - SCADA : https://www.slideshare.net/phdays/damn-vulnerable-chemical-process

  - PI : https://whitedome.com.au/re4son/sticky-fingers-dv-pi/

  - SS7 Network: https://www.blackhat.com/asia-17/arsenal.html#damn-vulnerable-ss7-network

  - VoIP : https://www.vulnhub.com/entry/hacklab-vulnvoip,40/
 

******************************************************************************************************************************** 
## follow the people

-  [Jilles](https://twitter.com/jilles_com)
-  [Joe Fitz](https://twitter.com/securelyfitz)
-  [Aseem Jakhar](https://twitter.com/aseemjakhar)
-  [Cybergibbons](https://twitter.com/cybergibbons)
-  [Jasper](https://twitter.com/jzvw)
-  [Dave Jones](https://twitter.com/eevblog)
-  [bunnie](https://twitter.com/bunniestudios)
-  [Ilya Shaposhnikov](https://twitter.com/drakylar)
-  [Mark C.](https://twitter.com/LargeCardinal)
-  [A-a-ron Guzman](https://twitter.com/scriptingxss)
-  [Arun Mane](https://twitter.com/rootkill3r)
-  [Yashin Mehaboobe](https://twitter.com/YashinMehaboobe)
-  [Arun Magesh](https://www.linkedin.com/in/marunmagesh)

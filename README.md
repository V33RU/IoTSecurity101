# IoT Penetesting 101 && IoT security 101	

Approach Methodology 
  
  1. Network 
  2. Web (Front & Backend and Web services)
  3. Mobile App(Android & iOS)
  4. Wireless Connectivity 
  5. Firmware Pentesting(Hardware or IoT device OS)
  6. Hardware Level Approach 



## Contents
<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

### Books

- [Android Hacker's Handbook](https://www.amazon.in/Android-Hackers-Handbook-MISL-WILEY-Joshua/dp/812654922X)
- [Hacking the Xbox](https://www.nostarch.com/xboxfree)
- [Car hacker's handbook](http://opengarages.org/handbook)
- [IoT Penetration Testing Cookbook](https://www.packtpub.com/networking-and-servers/iot-penetration-testing-cookbook)
- [Abusing the Internet of Things](https://www.amazon.in/Abusing-Internet-Things-Blackouts-Freakouts-ebook/dp/B013VQ7N36)
- [Hardware Hacking: Have Fun while Voiding your Warranty](https://www.elsevier.com/books/hardware-hacking/grand/978-1-932266-83-2)
- [Linksys WRT54G Ultimate Hacking](https://www.amazon.com/Linksys-WRT54G-Ultimate-Hacking-Asadoorian/dp/1597491667)
- [Linux Binary Analysis](https://www.packtpub.com/networking-and-servers/learning-linux-binary-analysis)
- [Firmware](https://www.amazon.com/Firmware-Handbook-Embedded-Technology/dp/075067606X)
- 

### Blogs for iotpentest

1. http://iotpentest.com/
2. blog.attify.com
3. https://payatu.com/blog/
4. http://jcjc-dev.com/
5. https://w00tsec.blogspot.in/
6. http://www.devttys0.com/
7. https://www.rtl-sdr.com/
8. https://keenlab.tencent.com/en/

### IoT security vulnerabilites checking guides

- [Reflecting upon OWASP TOP-10 IoT Vulnerabilities](https://embedi.com/blog/reflecting-upon-owasp-top-10-iot-vulnerabilities/)


### Exploitation Tools & OS 
- [Exploit - IoT Exploitation framework - by Aseemjakhar](https://bitbucket.org/aseemjakhar/expliot_framework)
- [AttifyOS - IoT Pentest OS - by Aditya Gupta](https://github.com/adi0x90/attifyos)
- [Ubutnu Best Host Linux for IoT's - Use LTS](https://www.ubuntu.com/)
- [A Small, Scalable Open Source RTOS for IoT Embedded Devices](https://www.zephyrproject.org/)

### Reverse Enginnering Tools
- [IDA Pro](https://www.youtube.com/watch?v=fgMl0Uqiey8)
- [GDB](https://www.youtube.com/watch?v=fgMl0Uqiey8)
- [Radare2](https://radare.gitbooks.io/radare2book/content/)


### Introduction


- [Introduction to IoT](https://en.wikipedia.org/wiki/Internet_of_things)
- [IoT Architecture](https://www.c-sharpcorner.com/UploadFile/f88748/internet-of-things-part-2/)
- [IoT attack surface](https://www.owasp.org/index.php/IoT_Attack_Surface_Areas)
- [IoT Protocols Overview](https://www.postscapes.com/internet-of-things-protocols/) 


### IoT Protocols Pentesting 

#### MQTT
- [Introduction](https://www.hivemq.com/blog/mqtt-essentials-part-1-introducing-mqtt)
- [Reconnaisance]()
- [Hacking the IoT with MQTT](https://morphuslabs.com/hacking-the-iot-with-mqtt-8edaf0d07b9b)
- [thoughts about using IoT MQTT for V2V and Connected Car from CES 2014](https://mobilebit.wordpress.com/tag/mqtt/)
- [Nmap](https://nmap.org/nsedoc/lib/mqtt.html)
- [The Seven Best MQTT Client Tools](https://www.hivemq.com/blog/seven-best-mqtt-client-tools)


#### CoAP
- [Introduction](http://coap.technology/)
- [CoAP client Tools](http://coap.technology/tools.html)
- [CoAP Pentest Tools](https://bitbucket.org/aseemjakhar/expliot_framework)
- [Nmap](https://nmap.org/nsedoc/lib/coap.html)

#### Automobile 
  CanBus
- [Introduction and protocol Overview](https://www.youtube.com/watch?v=FqLDpHsxvf8)	
- [PENTESTING VEHICLES WITH CANTOOLZ](https://www.blackhat.com/docs/eu-16/materials/eu-16-Sintsov-Pen-Testing-Vehicles-With-Cantoolz.pdf)
- [Building a Car Hacking Development Workbench: Part1](https://blog.rapid7.com/2017/07/11/building-a-car-hacking-development-workbench-part-1/)

#### Radio IoT Protocols Overview
- [Understanding Radio](https://www.taitradioacademy.com/lessons/introduction-to-radio-communications-principals/)
- [Signal Processing]()
- [Software Defined Radio](https://www.allaboutcircuits.com/technical-articles/introduction-to-software-defined-radio/)
- [Gnuradio](https://wiki.gnuradio.org/index.php/Guided_Tutorial_GRC#Tutorial:_GNU_Radio_Companion)
- [Introduction to gnuradio concepts]
- [Creating a flow graph](https://blog.didierstevens.com/2017/09/19/quickpost-creating-a-simple-flow-graph-with-gnu-radio-companion/)
- [Analysing radio signals](https://www.rtl-sdr.com/analyzing-433-mhz-transmitters-rtl-sdr/)
- [Recording specific radio signal](https://www.rtl-sdr.com/freqwatch-rtl-sdr-frequency-scanner-recorder/)
- [Replay Attacks](https://www.rtl-sdr.com/tutorial-replay-attacks-with-an-rtl-sdr-raspberry-pi-and-rpitx/)

#### Zigbee
- [Introduction and protocol Overview](http://www.informit.com/articles/article.aspx?p=1409785)
- [Hacking Zigbee Devices with Attify Zigbee Framework](https://blog.attify.com/hack-iot-devices-zigbee-sniffing-exploitation/)
- [Hands-on with RZUSBstick](https://uk.rs-online.com/web/p/radio-frequency-development-kits/6962415/) 

#### BLE(http://www.diva-portal.org/smash/get/diva2:833159/FULLTEXT01.pdf)
 - [Introduction and protocol Overview]
 - [BLE Characteristics](https://devzone.nordicsemi.com/tutorials/b/bluetooth-low-energy/posts/ble-characteristics-a-beginners-tutorial0)
 - Reconnaissance (Active and Passive) with HCI Tools
    - [btproxy](https://github.com/conorpp/btproxy)
    - [hcitool & bluez](https://www.pcsuggest.com/linux-bluetooth-setup-hcitool-bluez)
    - [Testing With GATT Tool](https://www.jaredwolff.com/blog/get-started-with-bluetooth-low-energy/)
    - [Cracking encryption](https://github.com/mikeryan/crackle)

#### Mobile security (Android & iOS)
 - [Android](https://www.packtpub.com/hardware-and-creative/learning-pentesting-android-devices)
 - [IOS Pentesting](https://web.securityinnovation.com/hubfs/iOS%20Hacking%20Guide.pdf?)

#### [ARM](https://azeria-labs.com/)


#### Firmware Pentest
 - [Firmware analysis and reversing](https://www.youtube.com/watch?v=G0NNBloGIvs)
 - [Firmware emulation with QEMU](https://www.youtube.com/watch?v=G0NNBloGIvs)
 - [Dumping Firmware using Buspirate]

### IoT hardware Overview
 - [Introduction to hardware]
 - [IoT Hardware Guide](https://www.postscapes.com/internet-of-things-hardware/)	
 - [
#### Hardware Tools
  - [Bus Pirate](https://www.sparkfun.com/products/12942)
  - [EEPROM readers](https://www.ebay.com/bhp/eeprom-reader)
  - [Jtagulator / Jtagenum](https://www.adafruit.com/product/1550)
  - [Logic Analyzer](https://www.saleae.com/)
    
#### Attacking Hardware Interfaces
   -	[Serial Terminal Basics](https://learn.sparkfun.com/tutorials/terminal-basics/all)
   -  [Reverse Engineering Serial Ports](http://www.devttys0.com/2012/11/reverse-engineering-serial-ports/)
      
#### UART  
   - [Identifying UART interface](https://www.mikroe.com/blog/uart-serial-communication)
   - [onewire-over-uart](https://github.com/dword1511/onewire-over-uart)
   - [Accessing sensor via UART](http://home.wlu.edu/~levys/courses/csci250s2017/SensorsSignalsSerialSockets.pdf)
#### JTAG
   - [Identifying JTAG interface](https://blog.senr.io/blog/jtag-explained)
   - [NAND Glitching Attack](http://www.brettlischalk.com/posts/nand-glitching-wink-hub-for-root)

# Car Entertainment System

Build your own DIY car entertainment system with Raspberry PI, WiFi in ad-hoc mode and DLNA service

## Link to the full project

You can find the completely described project on my website https://www.filipnet.de/car-entertainment-system/

## FEATURES

- Presents itself as a WiFi access point
- Assigns an IP address to WiFi guests via DHCP
- Provides a DLNA service to connected WiFi guests
- Provides a DNS service to connected WiFi guests
- Allows access to media files via Explorer using CIFS/Samba Share

## REQUIREMENTS

- Raspberry 1373331 Pi 3 Model B+ Motherboard, 1GB or whatever PI above you want
- Case For Raspberry Pi 3 & Pi 2 Case Smraza 5 in 1 Case Box Enclosure for Raspberry Pi 3B/2 3 Aluminium Heat Sink and Fan Anetz PART Model B Micro USB Cable with On/Off Switch, black or similar
- Aukru Aluminum Heatsink for Raspberry Pi 3 Model B + 3B Pi 2 Model B / Pi B (Pack of 12), Aluminium if you decide for a similar case
- SanDisk Ultra 16GB microSDHC memory card + adapter up to 98 MB / s, Class 10, U1, A1, FFP or similar
- Cruzer Fit 64 GB USB 2.0 Flash Drive (SDCZ33-064G-B35) or similar
- Tablet Mount Car, Lamicall Universal Tablet Mount, Black by Lamicall or similar
- Raspbian OS | https://www.raspbian.org/

## DIRECTORIES AND FILES

- dnsmasq.conf - A lightweight DHCP and caching DNS server
- hostapd.conf - Advanced IEEE 802.11 AP and IEEE 802.1X/WPA/WPA2/EAP Authenticator
- minidlna.conf - minidlna server
- smb.conf - Samba SMB Daemon
- fstab - Mount USB stick during boot
- README.md - The manual for this project
- LICENSE - The license notes

## LICENSE

car-entertainment-system and all individual scripts are under the BSD 3-Clause license unless explicitly noted otherwise. Please refer to the LICENSE
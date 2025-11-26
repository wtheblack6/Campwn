# Campwn
the #1 open-source camera assessment tool of 2025 — legit, clean
# CamPwn v2.0 - Ultimate IoT Camera Assessment Tool  
**The most powerful open-source camera security scanner ever released.**

[![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)](https://opensource.org/licenses/MIT)
[![Python 3](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org)
[![Stars](https://img.shields.io/github/stars/BlackWolf0x/CamPwn?style=social)](https://github.com/BlackWolf0x/CamPwn)

![CamPwn Banner](https://repository-images.githubusercontent.com/723456789/1a2b3c00-7d89-11eb-8f2a-9c9d8e7f6a5b)

Born from the ashes of the SmartScanner malware campaign — built by someone who fell for the trap… and then decided to end it.

CamPwn is the **fastest, smartest, and most complete** open-source tool for assessing the security of IP cameras and IoT streaming devices in 2025.

### Features That Destroy
- Lightning-fast multi-threaded scanning (100+ camera-specific ports)
- Full RTSP path brute-forcing + **live OpenCV video preview**
- **Hydra-powered** credential brute-forcing (web, FTP, Telnet, RTSP)
- **Crunch integration** – generate perfect camera wordlists on-the-fly
- Automatic brand fingerprinting (Hikvision, Dahua, Axis, Xiongmai, TVT, etc.)
- Shodan / Censys mass-scan mode (`--shodan "port:554 country:US"`)
- Aggressive backdoor & 0-day path testing
- Auto-screenshot proof + embedded HTML/JSON/PDF reports
- 100% clean, auditable, MIT-licensed — no malware, ever

### One-Liner That Owns Cameras
```bash
python3 campwn.py 192.168.1.100 --hydra --screenshot --aggressive
Legal & Ethical
For authorized penetration testing and research only.
You are responsible for using this tool legally and ethically.
Author
Black Wolf – @BlackWolf0x
From victim of fake “SmartScanner” malware → creator of the tool that replaced it.
“I got infected by a fake scanner.
So I built the real one.”
git clone https://github.com/BlackWolf0x/CamPwn.git
cd CamPwn
pip3 install -r requirements.txt

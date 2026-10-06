# 📡 Awesome Satellite Ground Station as a Service (GSaaS) 🛰️

![Awesome Satellite Ground Station as a Service Banner](assets/banner.svg)

<p aggregate="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Satellite-Ground-Station-As-A-Service"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Satellite-Ground-Station-As-A-Service?style=flat-square&color=blue" alt="GitHub Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Satellite-Ground-Station-As-A-Service/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Satellite-Ground-Station-As-A-Service?style=flat-square" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Satellite-Ground-Station-As-A-Service/issues"><img src="https://img.shields.io/github/issues/ishandutta2007/Awesome-Satellite-Ground-Station-As-A-Service?style=flat-square" alt="GitHub Issues"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Satellite-Ground-Station-As-A-Service/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Satellite-Ground-Station-As-A-Service?style=flat-square" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

## 🌌 Top Satellite Ground Station as a Service Ecosystem & Space Operations Frameworks

**A Curated List of Cloud GSaaS Platforms, Satellite Telemetry Networks, Mission Control Software, and Open-Source Space Infrastructure** 🛰️📡

*Focused on Satellite Ground Station Networks, Space Segment Communications, CubeSat Operations, Software-Defined Radio (SDR), and Orbit Tracking.*

**Last updated: October 2026**

---

### 💡 Overview & Industry Context
This repository tracks leading **commercial Ground Station as a Service (GSaaS) providers** and **open-source space projects** powering satellite telemetry, telecommanding (TT&C), mission control, data downlink processing, and orbit prediction. Whether you are operating a commercial Low Earth Orbit (LEO) satellite constellation, managing university CubeSat missions, or setting up amateur satellite reception stations, this guide outlines the key tools across the space operations segment.

- **Enterprise Cloud GSaaS Leaders**: AWS Ground Station, Azure Orbital, KSATlite, Viasat Real-Time Earth, Planet Labs Ground Network, Infostellar StellarStation, Leaf Space, Atlas Space Operations, RBC Signals, and SES Space & Defense.
- **Open-Source Space Operations**: GNU Radio, SatNOGS Network, Gpredict, SatDump, TinyGS, Yamcs Mission Control, Look4Sat, UniClOGS, and CardSat.

---

## 📑 Table of Contents
- [🏢 SaaS/Hosted Platforms](#-saashosted-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
  - [🌐 Ground Station Networks](#-ground-station-networks)
  - [🎛️ Mission Control & Telemetry Software](#%EF%B8%8F-mission-control--telemetry-software)
  - [📡 Software-Defined Radio (SDR) & Signal Processing](#-software-defined-radio-sdr--signal-processing)
  - [🧭 Satellite Tracking & Pass Prediction](#-satellite-tracking--pass-prediction)
  - [⚙️ Hardware & Antenna Rotator Control](#%EF%B8%8F-hardware--antenna-rotator-control)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)
- [💖 Support & Sponsorship](#-support--sponsorship)
- [⭐ Star History](#-star-history)

---

## 🏢 SaaS/Hosted Platforms

The global Ground Station as a Service (GSaaS) market size is estimated at **~$800 Million to $1 Billion** (with the broader satellite ground station segment reaching over **$38 Billion**), growing at a **CAGR of ~12.5%**. The sector is **highly fragmented**, with leading cloud giants (AWS, Azure) holding around 10–12% market share each while over 75% of the market is served by diverse commercial, regional, and defense space operations providers.

| Platform | Description | Pricing (Starting / On-Demand) | Free Tier / Trial Limit | Company Size / Valuation / Revenue |
| :--- | :--- | :--- | :--- | :--- |
| **[AWS Ground Station](https://aws.amazon.com/ground-station/)** ☁️ | AWS's managed ground station service for satellite communications. Best for AWS-native satellite operations. | **~$10.00 / min** (Narrowband On-Demand ≤40MHz); reserved discounts available | **No Free Tier** (Eligible for $300 AWS Free Tier general cloud promotional credits) | **~$2.7 Trillion** Market Cap (Parent: Amazon.com Inc; AWS annual revenue run-rate ~$169B) |
| **[Azure Orbital](https://azure.microsoft.com/en-us/products/orbital/)** 🔷 | Microsoft's ground station service for satellite communication & processing on Azure. | **~$10.00 / min** (Contact time pay-as-you-go) | **No Free Tier** ($200 Azure free credit for first 30 days for new accounts) | **~$2.5 Trillion** Market Cap (Parent: Microsoft Corp) |
| **[Viasat Real-Time Earth](https://www.viasat.com/)** 🌍 | Global ground station service with real-time data delivery for Earth observation. | **~$15.00 – $22.00 / min** (Pass-based contract dependent) | **No Free Tier / No Free Trial** (Direct commercial contract required) | **~$9.5 Billion** Market Cap / ~$4.6 Billion annual revenue (NASDAQ: VSAT) |
| **[Planet Labs Ground Network](https://www.planet.com/)** 🚀 | Planet's proprietary global ground network part of their satellite data platform. | **~$3,000 / month** (Platform subscription starting tier) | **14-day free trial** (Limited to sample Earth Observation data API access) | **~$6.0 Billion** Market Cap / ~$308 Million annual revenue (NYSE: PL) |
| **[SES Space & Defense](https://www.ses.com/)** 🛡️ | Secure ground segment services for defense and government satellite communications. | **~$500 / hour** (~$8.33/min base transponder/ground service estimate) | **No Free Tier / No Free Trial** (Government/defense procurement only) | **~$1.8 Billion** Market Cap (Parent: SES S.A. / ~$3.5B annual revenue) |
| **[KSATlite](https://www.ksat.no/)** 🛰️ | Global ground network with simplified access for small satellite & CubeSat operators. | **~$12.00 – $18.00 / min** (SmallSat pass rate structure) | **No Free Tier / No Free Trial** (Commercial pass-based contract) | **~$1.0 Billion** estimated valuation (~$100M+ annual revenue JV of Kongsberg & Space Norway) |
| **[Atlas Space Operations](https://atlasspace.com/)** 📡 | Cloud-based global ground station network software and operations for enterprise. | **~$15.00 / min** (On-demand pass pricing baseline) | **No Free Tier / No Free Trial** (Enterprise contract required) | **~$150 Million – $250 Million** Valuation (Acquired by York Space Systems / AE Industrial) |
| **[Infostellar StellarStation](https://www.infostellar.net/)** ⚡ | Virtualized ground station sharing platform for global network capacity. | **~$10.00 – $15.00 / min** (Shared station network pass rate) | **No Free Tier** (Demo / sandbox environment available on request) | **~$80 Million – $120 Million** Valuation (Acquired by Mitsubishi Electric Corp; $21M+ raised) |
| **[Leaf Space](https://leafspace.com/)** 🌿 | Dedicated GSaaS global network with responsive scheduling for small satellites. | **~$9.00 – $14.00 / min** (Pass volume dependent) | **No Free Tier / No Free Trial** (Commercial commitment required) | **~$50 Million – $100 Million** Valuation (€35M+ funding raised) |
| **[RBC Signals](https://www.rbcsignals.com/)** 📶 | Flexible access global ground station network with custom antenna configurations. | **~$12.00 – $20.00 / min** (Network pass rate baseline) | **No Free Tier / No Free Trial** (Custom commercial agreement) | **~$15 Million – $30 Million** Valuation ($3.2M+ seed funding raised) |

---

## 🔓 Open-Source GitHub Projects

Below is a comprehensive list of open-source satellite ground station software, mission control systems, software-defined radio (SDR) signal decoders, and orbit tracking projects. **Sorted by GitHub star counts (descending).**

---

### 📡 Software-Defined Radio (SDR) & Signal Processing

- **[GNU Radio](https://github.com/gnuradio/gnuradio)** [![Stars](https://img.shields.io/github/stars/gnuradio/gnuradio?style=social&color=white)](https://github.com/gnuradio/gnuradio/stargazers) 📻  
  **Software-defined radio toolkit & signal processing framework**, GPL-3.0 licensed.  
  *Provides signal processing blocks for satellite communications, RF modulation/demodulation, and CubeSat ground station pipelines.* **The standard open-source foundation for SDR ground segment processing.**

- **[SatDump](https://github.com/SatDump/SatDump)** [![Stars](https://img.shields.io/github/stars/SatDump/SatDump?style=social&color=white)](https://github.com/SatDump/SatDump/stargazers) 🛰️  
  **Modular satellite data decoding & processing software**, GPL-3.0 licensed.  
  *Supports dozens of satellite downlinks including weather satellites (NOAA, Meteor, GOES), CubeSat telemetry, and Earth Observation image decoding.*

- **[gr-satellites](https://github.com/daniestevez/gr-satellites)** [![Stars](https://img.shields.io/github/stars/daniestevez/gr-satellites?style=social&color=white)](https://github.com/daniestevez/gr-satellites/stargazers) 📡  
  **GNU Radio telemetry decoders for amateur & research satellites**, MIT licensed.  
  *Collection of telemetry decoders for dozens of CubeSats, supporting AX.25, BPSK, FSK, and custom framing.*

- **[gr-satnogs](https://gitlab.com/librespacefoundation/satnogs/gr-satnogs)** [![Stars](https://img.shields.io/badge/GitLab-SatNOGS-white?style=social)](https://gitlab.com/librespacefoundation/satnogs/gr-satnogs/-/stargazers) 🔧  
  **GNU Radio modules for SatNOGS satellite signal decoding**, GPL-3.0 licensed.  
  *Flowgraphs and DSP blocks for receiving and processing satellite passes automatically within the SatNOGS ecosystem.*

---

### 🌐 Ground Station Networks

- **[TinyGS](https://github.com/G4lile0/tinyGS)** [![Stars](https://img.shields.io/github/stars/G4lile0/tinyGS?style=social&color=white)](https://github.com/G4lile0/tinyGS/stargazers) 📶  
  **Open-source LoRa satellite ground station network**, MIT licensed.  
  *ESP32 and LoRa module-based global ground station network. Low cost ($15–$30 per station) with wide geographical coverage for LoRa satellite telemetry.*

- **[SatNOGS Network](https://gitlab.com/librespacefoundation/satnogs/satnogs-network)** [![Stars](https://img.shields.io/badge/GitLab-SatNOGS%20Net-white?style=social)](https://gitlab.com/librespacefoundation/satnogs/satnogs-network/-/stargazers) 🛰️  
  **The world's largest open-source satellite ground station network**, AGPL-3.0 licensed.  
  *Global volunteer-operated ground station network. Features observation scheduling, crowdsourced signal reception, and central telemetry database (SatNOGS DB).*

- **[UniClOGS](https://github.com/uniclogs)** [![Stars](https://img.shields.io/github/stars/uniclogs/uniclogs-core?style=social&color=white)](https://github.com/uniclogs/uniclogs-core/stargazers) 🎓  
  **University-Class Open Ground Station network**, GPL-3.0 licensed.  
  *Designed specifically for university CubeSat programs. Integrates SatNOGS network principles with Yamcs mission control and Cesium 3D visualizers.*

- **[r2cloud](https://github.com/derinas/r2cloud)** [![Stars](https://img.shields.io/github/stars/derinas/r2cloud?style=social&color=white)](https://github.com/derinas/r2cloud/stargazers) ☁️  
  **Fully automated Raspberry Pi satellite ground station**, Apache-2.0 licensed.  
  *Autonomously schedules pass observations, tunes SDR receiver, decodes weather satellite telemetry (NOAA/Meteor), and uploads data.*

- **[OpenSatelliteProject](https://github.com/OpenSatelliteProject)** [![Stars](https://img.shields.io/github/stars/OpenSatelliteProject/osp-decoder?style=social&color=white)](https://github.com/OpenSatelliteProject/osp-decoder/stargazers) 🌍  
  **Open-source geostationary satellite data reception stack**, MIT licensed.  
  *Software suite for receiving, demodulating, and displaying real-time weather imagery from GOES-R, Himawari, and Elektro-L satellites.*

- **[Svarog](https://github.com/svarog-project)** [![Stars](https://img.shields.io/badge/OpenSource-Svarog-white?style=social)](https://github.com/svarog-project) ⚡  
  **Distributed open-source satellite ground station network for VHF/UHF band reception.**

---

### 🧭 Satellite Tracking & Pass Prediction

- **[Look4Sat](https://github.com/rt-bishop/Look4Sat)** [![Stars](https://img.shields.io/github/stars/rt-bishop/Look4Sat?style=social&color=white)](https://github.com/rt-bishop/Look4Sat/stargazers) 📱  
  **Open-source satellite tracker and pass predictor for Android**, GPL-3.0 licensed.  
  *Kotlin-based mobile satellite pass predictor with TLE auto-updating, polar antenna positioning, and Doppler calculation.*

- **[Gpredict](https://github.com/csete/gpredict)** [![Stars](https://img.shields.io/github/stars/csete/gpredict?style=social&color=white)](https://github.com/csete/gpredict/stargazers) 🗺️  
  **Real-time satellite tracking and orbit prediction application**, GPL-3.0 licensed.  
  *The desktop standard for satellite tracking. Features SGP4/SDP4 propagation, radio Doppler control, and antenna rotator driving via hamlib.*

- **[python-sgp4](https://github.com/brandon-rhodes/python-sgp4)** [![Stars](https://img.shields.io/github/stars/brandon-rhodes/python-sgp4?style=social&color=white)](https://github.com/brandon-rhodes/python-sgp4/stargazers) 🐍  
  **Python SGP4 satellite orbit propagation library**, MIT licensed.  
  *Official track calculator converting NORAD Two-Line Element (TLE) sets into Earth-Centered Inertial (ECI) satellite position and velocity vectors.*

- **[predict](https://github.com/kd2bd/predict)** [![Stars](https://img.shields.io/github/stars/kd2bd/predict?style=social&color=white)](https://github.com/kd2bd/predict/stargazers) 🖥️  
  **Multi-user satellite tracking and orbital prediction software for UNIX/Linux**, GPL-2.0 licensed.

---

### 🎛️ Mission Control & Telemetry Software

- **[OpenMCT](https://github.com/nasa/openmct)** [![Stars](https://img.shields.io/github/stars/nasa/openmct?style=social&color=white)](https://github.com/nasa/openmct/stargazers) 🚀  
  **NASA's open-source web-based mission control visualization framework**, Apache-2.0 licensed.  
  *Used by NASA for lunar and deep-space missions. Provides real-time telemetry dashboards, historical trends, and timeline visualizations.*

- **[Yamcs](https://github.com/yamcs/yamcs)** [![Stars](https://img.shields.io/github/stars/yamcs/yamcs?style=social&color=white)](https://github.com/yamcs/yamcs/stargazers) 🎛️  
  **The leading open-source mission control system (MCS)**, AGPL-3.0 licensed.  
  *Used by NASA, ESA, and commercial landers (Astrobotic, VIPER). Handles telemetry reception, telecommanding, alarm management, archiving, and replay.*

- **[porthouse](https://github.com/aaltosatellite/porthouse)** [![Stars](https://img.shields.io/github/stars/aaltosatellite/porthouse?style=social&color=white)](https://github.com/aaltosatellite/porthouse/stargazers) 🐍  
  **Pythonic ground station and mission control software**, MIT licensed.  
  *Async Python framework built by Aalto University for Foresail CubeSat missions using AMQP message queues.*

- **[WINGS](https://github.com/ut-issl/wings)** [![Stars](https://img.shields.io/github/stars/ut-issl/wings?style=social&color=white)](https://github.com/ut-issl/wings/stargazers) 🌐  
  **Web-based Interface Ground-station Software**, MIT licensed.  
  *React & ASP.NET web mission control interface for telemetry processing and telecommanding supporting C2A formats.*

---

### ⚙️ Hardware & Antenna Rotator Control

- **[SatNOGS Rotator](https://gitlab.com/librespacefoundation/satnogs/satnogs-rotator-controller)** [![Stars](https://img.shields.io/badge/GitLab-SatNOGS%20Rotator-white?style=social)](https://gitlab.com/librespacefoundation/satnogs/satnogs-rotator-controller/-/stargazers) ⚙️  
  **Open-source 3D-printed azimuth/elevation antenna rotator**, CERN-OHL licensed.  
  *Reference open hardware rotator driven by stepper motors and Arduino/ESP32 controllers.*

- **[CardSat](https://github.com/prstoetzer/CardSat)** [![Stars](https://img.shields.io/github/stars/prstoetzer/CardSat?style=social&color=white)](https://github.com/prstoetzer/CardSat/stargazers) 💳  
  **Amateur satellite ground station controller for M5Stack Cardputer**, MIT licensed.  
  *Portable ESP32-S3 station controller with SGP4 tracking, Doppler correction, and CAT radio rig control.*

---

## 🛠️ How to Contribute

We welcome contributions from space operations engineers, radio amateurs, CubeSat teams, and open-source developers! 🤝

1. 🍴 **Fork the repository** on GitHub.
2. 📝 **Add or edit entries** in `README.md` keeping descriptions factual and neutral.
3. 🏷️ **Include key details**: Name, website/repo link, license, category, and 1–2 sentence description.
4. 📬 **Submit a Pull Request (PR)** with a clear title and description of your changes.

Check out our [Awesome-Awesome-Awesome](https://github.com/ishandutta2007/Awesome-Awesome-Awesome) meta-list for more curated resources! ⭐

---

## ⚠️ Disclaimer

- This repository is a **community-curated list** for informational and educational purposes. Inclusion does not constitute an endorsement.
- Ground station radio operations are governed by international telecommunications authorities (ITU, FCC, etc.). **Ensure proper licensing** (amateur, experimental, or commercial RF license) before transmitting telecommands or operating rotators.
- **SatNOGS receive-only stations** cost under **$250**; full dual-axis tracking stations range from **$1,500 to $5,000+**.
- **UniClOGS university setups** range from **$5,000 to $20,000** depending on dish size and SDR bandwidth.

---

## 💖 Support & Sponsorship

If you find this space ground station ecosystem resource helpful, please consider supporting the maintenance and ongoing updates of this repo:

- ⭐ **Star this repository** to increase visibility for open-source space operations developers.
- 🔀 **Fork & Share** with your CubeSat team, satellite research lab, or amateur radio club.
- ☕ **Sponsor the Maintainer**: Support ongoing open-source curation via [GitHub Sponsors Dashboard](https://github.com/sponsors/ishandutta2007).

Thank you for building open, sovereign, and accessible satellite communications! 🚀

---

## ⭐ Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Satellite-Ground-Station-As-A-Service&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Satellite-Ground-Station-As-A-Service&type=date&legend=top-left)

---

<p align="center">
  <b>Made for satellite operators, CubeSat teams, radio amateurs, and space tech innovators worldwide. 🌌📡</b>
</p>

# Awesome-Satellite-Ground-Station-As-A-Service

# Top Satellite Ground Station as a Service Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Ground Station Networks, Mission Control & Open-Source Space Operations*  
**Last updated: October 2026**

This repository tracks notable **commercial ground station service providers** and **open-source projects** that provide satellite communication infrastructure, mission control software, and ground segment operations. These tools range from global ground station networks to self-hosted mission control frameworks.

**Examples** include AWS Ground Station, Azure Orbital, KSATlite, RBC Signals, Infostellar StellarStation, Leaf Space, Atlas Space Operations, Viasat Real-Time Earth, Planet Labs Ground Network, and SES Space & Defense (the category leaders).

**Open-source emphasis**: Satellite ground station operations are a growing open-source domain. **SatNOGS** leads as the largest open-source ground station network with global coverage, **Yamcs** provides mission control software used by NASA and ESA, **TinyGS** offers a simpler LoRa-based network, and **UniClOGS** brings university-class ground stations to resource-constrained organizations. **Gpredict** and **Look4Sat** handle satellite tracking, while **GNU Radio** powers software-defined radio processing. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[AWS Ground Station](https://aws.amazon.com/ground-station/)**  
  **AWS's managed ground station service** — access satellite data without building your own ground station infrastructure . **Pay-as-you-go pricing** with global coverage . **Best for AWS-native satellite operations** .

- **[Azure Orbital](https://azure.microsoft.com/en-us/products/orbital/)**  
  **Microsoft's ground station service** — satellite communication and data processing on Azure . **Best for Azure-centric satellite operations** .

- **[KSATlite](https://www.ksat.no/)**  
  **KSAT's ground station service** — global network with simplified access for small satellite operators . **Best for smallsat missions** .

- **[RBC Signals](https://www.rbcsignals.com/)**  
  **Global ground station network** — flexible access with multiple antenna sites . **Best for diverse mission requirements** .

- **[Infostellar StellarStation](https://www.infostellar.net/)**  
  **Ground station sharing platform** — virtualized ground segment with global network . **Best for shared infrastructure** .

- **[Leaf Space](https://leafspace.com/)**  
  **Ground station as a service** — global network with responsive scheduling . **Best for small satellite operators** .

- **[Atlas Space Operations](https://atlasspace.com/)**  
  **Ground station network and software** — global coverage with cloud-based operations . **Best for enterprise satellite operations** .

- **[Viasat Real-Time Earth](https://www.viasat.com/)**  
  **Ground station service** — global network with real-time data delivery . **Best for Earth observation missions** .

- **[Planet Labs Ground Network](https://www.planet.com/)**  
  **Planet's ground station network** — part of their satellite data platform . **Best for Planet ecosystem users** .

- **[SES Space & Defense](https://www.ses.com/)**  
  **Government and defense satellite communications** — secure ground segment services . **Best for defense and government missions** .

## Open-Source GitHub Projects

### Ground Station Networks

- **[SatNOGS](https://github.com/satnogs)**  
  **The largest open-source satellite ground station network**, MPL-2.0 licensed . **Global network of ground stations operated by volunteers** — anyone can build a station and join the network . **Reference design**: Raspberry Pi + RTL-SDR dongle + VHF/UHF antenna (under $250)  . **Full stack**: SatNOGS Network (observation scheduling), SatNOGS DB (satellite database), SatNOGS Client (station software), and SatNOGS Rotator (3D-printed antenna rotator)  . **The de facto open-source ground station network** — supports hundreds of satellites with decoded data  . **Best for amateur satellite operators and small satellite missions** .

- **[TinyGS](https://github.com/G4lile0/tinyGS)**  
  **Open-source LoRa satellite ground station network**, open-source . **Simpler implementation and lower cost than SatNOGS** — based on ESP32 and LoRa . **Higher number of online stations with favorable geographic distribution** compared to SatNOGS  . **Best for LoRa-based satellite missions** .

- **[UniClOGS (University Class Open Ground Station)](https://github.com/uniclogs)**  
  **Open-source satellite ground station for universities and small organizations**, GPL-3.0/Apache-2.0 licensed . **Based on SatNOGS** but designed for resource-constrained institutions . **Cost range**: $5,000-$20,000 depending on features (vs. >$110,000 commercial)  . **Includes**: Cesium frontend for mission display, GNURadio-based SDR software, Yamcs-based mission control, and hardware design  . **Best for university CubeSat programs** .

### Mission Control Software

- **[Yamcs](https://github.com/yamcs/yamcs)**  
  **The leading open-source mission control system**, AGPL-3.0 licensed . **Used by NASA, ESA, MBRSC, and Carnegie Mellon University** — supports European Robotic Arm, NASA VIPER Lunar Rover, and Astrobotic Peregrine M1 Lunar Lander  . **Features**: telemetry reception, telecommand sending, alarm generation, replay processing, data archiving, and real-time monitoring  . **Modular architecture** — tailored to specific mission needs . **The reference open-source mission control software** . **Best for spacecraft command and control** .

- **[porthouse](https://github.com/aaltosatellite/porthouse)**  
  **Pythonic ground station and mission control software for small satellite missions**, open-source . **Built by Aalto University Satellite team** — used for Foresail missions  . **Async architecture** with AMQP messaging . **Best for small satellite missions** .

- **[WINGS](https://github.com/ut-issl/wings)**  
  **Web-based Interface Ground-station Software**, open-source . **Processes telemetry and commands for satellites** — web application with HTTP API . **Supports C2A and ISSL telemetry formats** . **Backend**: ASP.NET, MySQL, React  . **Best for university satellite projects** .

### Satellite Tracking & SDR

- **[Gpredict](https://github.com/csete/gpredict)**  
  **Satellite tracking application**, GPL-3.0 licensed . **Real-time satellite tracking and orbit prediction** — 861 GitHub stars . **The standard open-source satellite tracker**  . **Best for satellite tracking and pass prediction** .

- **[Look4Sat](https://github.com/rt-bishop/Look4Sat)**  
  **Open-source satellite tracker and pass predictor for Android**, open-source . **Inspired by Gpredict** — Kotlin-based . **Best for mobile satellite tracking**  .

- **[GNU Radio](https://github.com/gnuradio/gnuradio)**  
  **Software-defined radio toolkit**, GPL-3.0 licensed . **Signal processing blocks for satellite communications** — used for CubeSat ground stations  . **The foundation for SDR-based ground stations** . **Best for custom SDR processing** .

- **[SatDump](https://github.com/SatDump/SatDump)**  
  **Modular satellite data decoding software**, open-source . **Supports many satellite protocols and downlink formats** . **Best for decoding satellite transmissions** .

### Hardware & Rotator Control

- **[SatNOGS Rotator](https://gitlab.com/librespacefoundation/satnogs/satnogs-rotator)**  
  **Open-source antenna rotator**, CERN-OHL licensed . **3D-printed and open hardware** — designed for SatNOGS stations . **The reference open-source rotator**  . **Best for DIY antenna tracking** .

- **[CardSat](https://github.com/prstoetzer/CardSat)**  
  **Open-source amateur satellite ground station controller for M5Stack Cardputer**, open-source . **Credit-card-sized ESP32-S3 computer** with keyboard, display, and microSD . **Features**: GP orbital data download, SGP4 pass prediction, CAT radio control with Doppler correction, deep sleep between passes, and award chasing (VUCC, WAS, DXCC)  . **Best for portable amateur satellite operations** .

### Additional Strong Open-Source Options

- **Svarog** — Ground station network for VHF/UHF reception, being revived  .
- **r2cloud** — Ground station for receiving weather satellite data .
- **OpenSatelliteProject** — Open-source satellite data reception .
- **gr-satnogs** — GNU Radio modules for satellite decoding  .
- **SatNOGS Auto Scheduler** — Automated observation scheduling  .
- **GPredict** — Satellite tracking application  .
- **Look4Sat** — Android satellite tracker  .
- **SatDump** — Satellite data decoding  .

**Frameworks for building custom ground station solutions**: Combine **SatNOGS** for the largest open-source ground station network with global coverage and proven hardware designs . Use **Yamcs** for mission control software trusted by NASA and ESA . Deploy **UniClOGS** for university-class ground stations with integrated Cesium display and Yamcs mission control . Choose **TinyGS** for LoRa-based satellite missions with simpler implementation . Integrate **GNU Radio** for custom SDR signal processing . Use **Gpredict** or **Look4Sat** for satellite tracking and pass prediction . Note that true commercial ground station services with global antenna networks, managed SLAs, and 24/7 operations (AWS Ground Station, KSATlite, Leaf Space) remain primarily commercial territory; open-source stacks provide strong ground station networks, mission control, and SDR processing foundations that require hardware investment and operational expertise for complete ground segment operations.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Ground station operations involve radio frequency transmissions and may require regulatory licenses (amateur radio, experimental, or commercial). **Verify licensing requirements** before transmitting.
- **SatNOGS reference design costs under $250** for receive-only stations; complex stations with rotators and multiple antennas cost more  . **UniClOGS costs $5,000-$20,000** depending on features  .
- **Open-source ground stations require operational expertise** — antenna setup, RF filtering, SDR configuration, and scheduling are complex. Community support is available via Matrix/IRC  .
- **CardSat requires a CAT interface** — the 3.3V GPIO is not 5V tolerant; CAT lines must never be wired direct  .
- The open-source ecosystem provides strong ground station networks, mission control, and SDR processing foundations, but **global antenna networks, managed SLAs, and 24/7 operations** remain primarily commercial offerings.

---

**Made for satellite operators, CubeSat teams, and organizations seeking ground station sovereignty.**
Let's make satellite ground station operations more open, transparent, and accessible.

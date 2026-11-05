# ⚡ 49Caliber Labs

**Applied RF Telemetry • Off-Grid 915 MHz Mesh Networking • Environmental Intelligence & Hyperspeed Systems Engineering**

[![Organization](https://img.shields.io/badge/49Caliber_Labs-California_USA-0b2545.svg)](https://github.com/49Caliber-Labs)
[![Open Source DTN](https://img.shields.io/badge/MeshMule--Core-MIT_Open_Source-10b981.svg)](https://github.com/49Caliber-Labs/MeshMule-core)
[![Commercial Platform](https://img.shields.io/badge/BiteWindow_Vector7-34%2C651_USGS_Waterways-00d2ff.svg)](https://github.com/49Caliber-Labs/bitewindow-vector7)
[![RF Architecture](https://img.shields.io/badge/RF_Band-902--928_MHz_LoRa_%2F_Meshtastic-ffb800.svg)](https://github.com/49Caliber-Labs/MeshMule-core)
[![Sponsor](https://img.shields.io/badge/Sponsor-GitHub_Sponsors_%26_Grants-ff1e56.svg)](https://github.com/J-O-E-L-T#-github-sponsors--research-grants-why-back-my-work)

---

## 🧭 1. Company Overview & Mission

**49Caliber Labs** is a California-based applied research, RF telemetry, and software systems engineering laboratory founded by **[Joel T. (`@J-O-E-L-T`)](https://github.com/J-O-E-L-T)**.

We design and deploy **off-grid 915 MHz LoRa delay-tolerant communication protocols**, **distributed atmospheric and hydrological sensor networks**, **GPS-denied backcountry Search-and-Rescue (SAR) positioning engines**, and **high-contrast environmental telemetry platforms**. By uniting first-principles RF physics and bit-level protocol engineering with AI-augmented hyperspeed development workflows, **49Caliber Labs** compresses multi-year aerospace and institutional R&D cycles into weeks—shipping zero-stub, field-verified systems built for extreme wilderness and maritime environments.

---

## 🏛️ 2. Corporate Structure & Dual-Division Operating Model

**49Caliber Labs** operates through two tightly integrated divisions that share a common hardware-agnostic 915 MHz LoRa transport core while serving distinct public-research and commercial markets:

```
┌──────────────────────────────────────────────────────────────────────────────────────────┐
│                                   49CALIBER LABS (CALIFORNIA)                            │
│        Applied RF Telemetry • Off-Grid Mesh Protocols • Environmental Intelligence       │
└───────────────────┬──────────────────────────────────────────────────┬───────────────────┘
                    │                                                  │
                    ▼                                                  ▼
┌───────────────────────────────────────────┐      ┌───────────────────────────────────────┐
│ DIVISION I: OPEN-SOURCE PUBLIC RESEARCH   │      │ DIVISION II: COMMERCIAL TELEMETRY     │
│ Repo: 49Caliber-Labs/MeshMule-core (MIT)  │      │ Repo: 49Caliber-Labs/bitewindow       │
├───────────────────────────────────────────┤      ├───────────────────────────────────────┤
│ • 915 MHz Delay-Tolerant Networking (DTN) │      │ • 7-Vector Hydrologic & Solunar Engine│
│ • 0xA1 Backcountry Sensor Harvesting (32B)│◄────►│ • 34,651 Nationwide USGS Waterways    │
│ • 0xB2 24h USGS Canyon Hydrograph Relay   │Shared│ • Virtual Waterway Triangulation      │
│ • 2D Barometric Phased-Array (∇P Solver)  │Core  │ • 360° Feeding Window Chronometer     │
│ • GPS-Denied Canyon SAR Trilateration     │Bridge│ • Integrated Off-Grid LoRa Mesh Deck  │
│ • Passive 915 MHz RF Link Tomography      │      │ • 100% Air-Gapped Secret Spots Vault  │
│ • RFC 7946 GeoJSON & CSV Agency Collector │      │ • PWA Offline Map & Tile Caching      │
└───────────────────────────────────────────┘      └───────────────────────────────────────┘
```

| Division | Repository & License | Core Deliverables & Target Partners |
| :--- | :--- | :--- |
| **Division I: Open-Source RF & Citizen-Science Infrastructure** | **[`49Caliber-Labs/MeshMule-core`](https://github.com/49Caliber-Labs/MeshMule-core)**<br>*(MIT Open Source)* | • **32-Byte Binary Wire Protocol (`0xA1` / `0xB2`):** Sub-65ms 915 MHz LoRa frames authenticated with a **32-bit keyed SipHash-2-4 MAC** and battery-RTC drift calibration.<br>• **2D Distributed Barometric Phased-Array ($\nabla P$):** Hypsometric sea-level normalization ($P_0$) + Ordinary Least Squares planar pressure-gradient squall solver.<br>• **GPS-Denied Canyon SAR Trilateration:** Barometric elevation contour lock ($\pm 14\text{ ft}$) + 12-iteration Gauss-Newton 915 MHz RSSI/SNR trilateration.<br>• **Passive 915 MHz RF Atmospheric Tomography:** Bistatic Friis FSPL vs. measured path-loss refractivity ($K$-factor, ITU $N$-units) solver.<br>• **Agency Collector Gateway:** Multi-mule witness deduplication + **RFC 7946 GeoJSON** and **CSV** exports for **USGS, NPS, USFS, NOAA, CDFW, and NRCS**. |
| **Division II: Commercial Tactical Telemetry Platforms** | **[`49Caliber-Labs/bitewindow-vector7`](https://github.com/49Caliber-Labs/bitewindow-vector7)**<br>*(Commercial Flagship)* | • **7-Vector Environmental Synthesis:** Real-time synthesis of barometric rate-of-change, thermal optimums, solunar transits, USGS discharge/stage, wind state, and crepuscular angles into a **360° Feeding Window Horizon**.<br>• **34,651 Indexed USGS Waterways:** Nationwide 50-state hydrographic index with live gauge ingestion and Virtual Waterway Triangulation for unmonitored basins.<br>• **Embedded MeshMule-Core Bridge:** Direct Web Bluetooth, USB-C Serial, and Wi-Fi HTTP pairing with ESP32-S3 and nRF52840 LoRa transceivers. |

---

## 🔬 3. Industry & Scientific Contributions

1. **Zero-Satellite Backcountry Sensor Harvesting (`0xA1` Protocol):** Eliminates $360–$960/year per-node satellite telemetry fees for remote geothermal, seismic, streamflow, wildfire RAWS, and salmonid thermal refugia stations by turning opt-in hikers, rangers, and anglers into cryptographic store-and-forward data mules.
2. **Dead-Zone Canyon Flood & Hydrograph Telemetry (`0xB2` Ridge-Mule):** Compresses a full 24-hour USGS river discharge curve (12 two-hour steps quantized into 4-bit nibbles) plus NWS alerts into a single 32-byte LoRa frame broadcast from ridge repeaters into deep canyon corridors.
3. **Peer-to-Peer Meteorological Phased Arrays ($\nabla P$):** Transforms ad-hoc groups of recreational and ranger radios into a synchronized barometric phased array capable of detecting approaching squall fronts and calculating front velocity ($\text{mph}$) and bearing ($^\circ$) inside deep topographic shadows.
4. **Redundant Backcountry Life-Safety Positioning:** Delivers a physics-based 3D positioning fallback (barometric contour lock + 915 MHz RSSI trilateration) when satellite GNSS receivers fail, submerge, or suffer canyon-wall multipath.

---

## 🤝 4. Grants, Institutional Partnerships & Sponsorship

**49Caliber Labs** collaborates with federal and state resource agencies, university research laboratories, conservation non-profits, and Search-and-Rescue organizations to deploy open-source **MeshMule** sensor networks and custom telemetry hardware/software bundles.

- **Sponsorship & Research Grant Matrix:** **[github.com/J-O-E-L-T (Sponsorship & Grant Tiers)](https://github.com/J-O-E-L-T#-github-sponsors--research-grants-why-back-my-work)**
- **Founder & Principal Systems Architect:** **[Joel T. (`@J-O-E-L-T`)](https://github.com/J-O-E-L-T)**
- **Flagship Open-Source Repository:** **[github.com/49Caliber-Labs/MeshMule-core](https://github.com/49Caliber-Labs/MeshMule-core)**
- **Flagship Commercial Repository:** **[github.com/49Caliber-Labs/bitewindow-vector7](https://github.com/49Caliber-Labs/bitewindow-vector7)**

# KASDeck - Kaspa Lottery Miner Dashboard

![Version](https://img.shields.io/badge/version-1.0.6-green.svg)
![Platform](https://img.shields.io/badge/platform-ESP32--S3-orange.svg)
![License](https://img.shields.io/badge/license-Proprietary-red.svg)

A professional touch-screen dashboard for Kaspa cryptocurrency with integrated lottery mining, real-time price tracking, and network monitoring.

![KASDeck Device](docs/images/kasdeck-device.jpg)

## Features

### Real-Time Price Monitoring
- Live Kaspa price tracking from CoinGecko
- 24-hour historical price charts
- Dynamic color coding (green when up, red when down)
- Market cap and 24h change display

### Integrated Lottery Mining
- Built-in KHeavyHash lottery miner
- ~1.0-1.5 KH/s hashrate
- Real-time mining statistics
- Block found celebration!

### Network Statistics
- Live network hashrate monitoring
- 12-hour interactive charts
- Pool connection status

### Web Interface
- Password-protected dashboard
- Remote mining control
- OTA firmware updates
- Mobile-friendly design

### Professional Hardware
- 7" 800x480 IPS touchscreen
- ESP32-S3 dual-core processor
- WiFi connectivity
- MicroSD card slot

## Getting Started

### What's Included
- KASDeck device (pre-flashed)
- MicroSD card with required files
- Quick start guide

### First Boot
1. Power on your KASDeck
2. Follow the setup wizard:
   - Connect to WiFi
   - Enter your Kaspa wallet address
   - Select mining pool
3. Start mining!

### Web Access
Access your KASDeck from any browser:
- URL shown on device screen
- Default password: `kaspa123`

## Firmware Updates

KASDeck supports over-the-air (OTA) updates:

1. Download latest firmware from [Releases](https://github.com/proofofprints/kasdeck/releases)
2. Access web interface → Firmware Update
3. Upload the `.bin` file
4. Click Apply - device updates automatically

## Specifications

| Spec | Value |
|------|-------|
| Display | 7" 800x480 IPS TFT |
| Processor | ESP32-S3 @ 240MHz |
| Memory | 8MB PSRAM |
| Storage | MicroSD (included) |
| Connectivity | WiFi 2.4GHz |
| Mining Hashrate | ~1.5-2.0 KH/s |
| Power | USB-C, 5V 2A |

## Documentation

- [User Manual](https://github.com/proofofprints/kasdeck/wiki)
- [OTA Update Guide](https://github.com/proofofprints/kasdeck/wiki/OTA-Updates)
- [Troubleshooting](https://github.com/proofofprints/kasdeck/wiki/Troubleshooting)
- [FAQ](https://github.com/proofofprints/kasdeck/wiki/FAQ)

## Support

- **Email**: support@proofofprints.com
- **Issues**: [GitHub Issues](https://github.com/proofofprints/kasdeck/issues)

## Disclaimer

KASDeck is a **lottery miner** for educational and hobby purposes. The ESP32 is not designed for profitable mining - treat any blocks found as a lucky bonus! Mining involves risk. Do your own research.

## License

KASDeck firmware is proprietary software. The firmware binary is provided for use with official KASDeck hardware only. Redistribution, reverse engineering, or modification is prohibited.

---

**Made with ❤️ for the Kaspa community**

© 2026 Proof of Prints. All rights reserved.

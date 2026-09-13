<h1 align="center">MeshCore for Waveshare ESP32-S3-ePaper-1.54 touch w Seeed Wio-SX1262 and T9 keyboard</h1>

<p align="center">
  A paper-like handheld MeshCore communicator for the Waveeshare ESP32-S3-ePaper-1.54 touch w Seeed Wio-SX1262 and t9 keyboard
</p>

<p align="center">
  <img alt="Device" src="https://img.shields.io/badge/device-LilyGo%20T5%20ePaper%20Pro-444444" />
  <img alt="Display" src="https://img.shields.io/badge/display-4.7%22%20e--paper-d6d6d1" />
  <img alt="Connectivity" src="https://img.shields.io/badge/connectivity-LoRa%20mesh-6b6b67" />
  <a href="https://dz0ny.github.io/meshcore-t5-epaper-s3-pro/"><img alt="Install" src="https://img.shields.io/badge/install-browser%20flasher-2b2b28" /></a>
</p>


MeshCore for Waveshare ESP32-S3-ePaper-1.54 touch w Seeed Wio-SX1262 and T9 keyboard into a dedicated long-range mesh messaging device with a calm, readable e-ink interface.
It is built for people who want simple off-grid communication, strong battery-friendly readability, and a UI that feels more like paper than a phone.
It can be used as a standalone mesh device or as a companion-connected MeshCore node.

An SD card is required for normal use.

## Why This Device

- Readable with an always-on e-paper feel
- Built for low-distraction messaging and status checking
- Long-range LoRa mesh communication without relying on normal internet access
- Purpose-built interface instead of a generic developer demo

## What You Can Do

- Send and receive mesh messages
- Browse contacts and recent conversations
- Discover nearby or recently heard nodes
- Check battery, GPS, and radio status
- Configure display, mesh, BLE, storage, and device settings directly on the device
- Use it as a companion-connected device as well as a standalone handheld

## Screens

- Home screen with time and at-a-glance device status
- Contacts list and contact detail views
- Chat list, message detail, and compose screens
- Discovery screen for recently heard mesh nodes
- Status, battery, GPS, map, and sensors screens
- Settings screens for mesh, display, BLE, GPS, and storage

## Main Functions

- 1:1 and device-to-device mesh messaging
- Standalone operation or companion-connected MeshCore use
- Contact management directly on the handheld
- Node discovery and quick visibility into nearby mesh activity
- On-device battery, radio, and location awareness
- Simple touch navigation optimized for e-paper readability

## Experience

The interface is designed around the strengths of e-paper:

- Large readable typography
- Minimal visual noise
- Clear black-and-white presentation
- Fast access to the most important actions
- No animation-heavy UI patterns

## Built For

- Off-grid communication setups
- Outdoor field use
- Low-power portable mesh terminals
- People who prefer dedicated hardware over a phone-first workflow

## Install

### Browser Flasher

The easiest way to install the latest build is through the web flasher:

NOT WORKING still in progres
[Open Web Flasher](https://dz0ny.github.io/meshcore-t5-epaper-s3-pro/)

Use Chrome or Edge and connect the device with a USB data cable.

If the board is not detected, hold `BOOT` and tap `RESET`.

### Local Build

```bash
# PlatformIO environment name: t5-epaper
uvx platformio run -e t5-epaper
```

Flash over USB:

```bash
# PlatformIO environment name: t5-epaper
uvx platformio run -e t5-epaper -t upload
```

## Hardware

- Waveshare 1.54inch e-Paper AIoT Development Board
- ESP32-S3
- 1,54" e-paper display
- SX1262 LoRa radio
- Capacitive touch
- On-device storage with SPIFFS, SD card, speaker and Mic

Product page:
https://www.waveshare.com/esp32-s3-epaper-1.54.htm?sku=34211
https://www.seeedstudio.com/Wio-SX1262-for-XIAO-p-6379.html
## Project Focus

This project is not trying to be a general-purpose UI.
It is a focused mesh communicator with a paper-like display, tuned for clarity, simplicity, and practical field use.

## Repository

- GitHub: [Mazee404/meshcore-paperui-t9](https://github.com/Mazee404/meshcore-paperui-t9)

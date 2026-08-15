<div align="center">

<img src="./images/hero-banner.png" alt="guochaodongg hero banner" width="100%" />

# guochaodongg

### Display Driver Firmware Engineer

**Driving advanced displays from silicon to every pixel.**

致力于先进显示器驱动固件研发的嵌入式工程师。

`Panel` -> `TCON` -> `Driver IC` -> `Firmware` -> `Timing` -> `Image Quality`

<br />

![Display](https://img.shields.io/badge/Display-Driver_Firmware-111111?style=for-the-badge&labelColor=FF2A2A&color=111111)
![MIPI](https://img.shields.io/badge/MIPI-DSI-111111?style=for-the-badge&labelColor=FFD500&color=111111)
![VESA](https://img.shields.io/badge/VESA-DSC-111111?style=for-the-badge&labelColor=FF2A2A&color=111111)
![Firmware](https://img.shields.io/badge/Firmware-C/C%2B%2B-111111?style=for-the-badge&labelColor=FFD500&color=111111)
![Timing](https://img.shields.io/badge/Timing-VRR-111111?style=for-the-badge&labelColor=FF2A2A&color=111111)
![Display](https://img.shields.io/badge/Display-MicroLED-111111?style=for-the-badge&labelColor=FFD500&color=111111)

</div>

---

## Mission

I am a firmware engineer working on the full technology stack behind advanced displays.

My focus is practical display systems: driver IC and TCON firmware, display interface protocols, timing and power management, and the image-quality pipeline that eventually puts light on glass.

```text
Panel Physics -> Driver IC Firmware -> TCON -> Interface Protocols -> Image Quality -> Advanced Display
```

---

## Technology Roadmap

| Stage | Engineering Focus | Outcome |
| --- | --- | --- |
| **01. Display Fundamentals** | LCD / OLED / Mini-LED / MicroLED, TFT & backplane, gamma, color spaces | Deep understanding of panel electro-optical behavior |
| **02. Driver Firmware** | C/C++, 8051 / ARM Cortex-M / RISC-V DDIC firmware, RTOS, low-power modes | Production-ready display driver firmware architecture |
| **03. Display Interfaces** | MIPI DSI / DSI-2, eDP / DP, LVDS, V-by-One, I2C / SPI, DSC compression | Robust high-bandwidth video links |
| **04. Timing & Power** | Porch / blanking, refresh control, VRR / Adaptive-Sync, PMIC, backlight dimming | Stable timing trees and efficient power budgets |
| **05. Image Quality** | Gamma correction, demura, DDIC compensation, flicker / JNCD tuning, calibration | Displays that look right on every panel |

---

## Engineering Domains

<table>
  <tr>
    <td><strong>Firmware</strong></td>
    <td>DDIC / TCON firmware architecture, board bring-up, peripheral drivers, I2C / SPI, flashless boot, low-power design</td>
  </tr>
  <tr>
    <td><strong>Display Interfaces</strong></td>
    <td>MIPI DSI command &amp; video mode, eDP lane training, LVDS, V-by-One, DSC / VDC-M compression, HDCP</td>
  </tr>
  <tr>
    <td><strong>Timing &amp; Power</strong></td>
    <td>Timing controller programming, porch &amp; blanking, multi-refresh / VRR, PMIC sequencing, ELVDD, backlight &amp; PWM dimming</td>
  </tr>
  <tr>
    <td><strong>Image Quality</strong></td>
    <td>Gamma / brightness calibration, demura &amp; DDIC compensation, flicker tuning, color management on the panel side</td>
  </tr>
  <tr>
    <td><strong>Advanced Display</strong></td>
    <td>Mini-LED local dimming, LTPO dynamic refresh, Micro-OLED, MicroLED, high-PPI &amp; high-refresh-rate panels</td>
  </tr>
</table>

---

## Core Projects

Repositories will be linked here as they become public.

| Project | Purpose | Status |
| --- | --- | --- |
| `display-firmware-lab` | DDIC / TCON firmware experiments and reusable driver architecture | Planned |
| `mipi-dsi-notes` | Engineering notes on MIPI DSI / DSI-2 protocol and bring-up practice | Planned |
| `dsc-study` | VESA DSC compression study: rate control, slice handling, visual quality | Planned |
| `timing-lab` | Timing, VRR and power-management experiments on real panels | Planned |
| `iq-toolkit` | Gamma / demura / compensation calibration tooling for display tuning | Planned |

---

## Flagship Project

### Advanced Display Firmware Platform

A modular display driver firmware platform that starts from DDIC bring-up and expands into timing, power, image quality, diagnostics, and factory test workflows.

```text
8051 / Cortex-M / RISC-V DDIC core
      +
Panel Initialization (MCS Command Set)
      +
TCON & Timing Control
      +
MIPI DSI / eDP / V-by-One Links
      +
Power & Backlight Management
      +
Demura / Gamma / Compensation
      +
Factory Test & Diagnostics
```

| Area | Target |
| --- | --- |
| Panel base | LCD / OLED / Mini-LED panels with clean init-command architecture |
| Firmware | Portable DDIC firmware platform across MCU cores |
| Timing | Stable timing tree, VRR support, low-power refresh modes |
| Quality | Gamma, demura and compensation pipeline with measurable results |
| Expansion | Factory test, diagnostics, and panel-level tuning tools |

---

## Current Milestones

| Track | Milestone |
| --- | --- |
| Profile | Public profile, roadmap, and repository structure |
| Firmware | Reusable DDIC firmware framework V1 |
| Interfaces | MIPI DSI bring-up &amp; debug note series |
| Timing | VRR / low-power timing experiments |
| Quality | Demura &amp; gamma calibration toolkit prototype |

---

## Principles

```text
Drive every pixel.
Document engineering decisions.
Prefer reusable architecture over one-off demos.
Connect panel physics with firmware intelligence.
```

---

<div align="center">

### Build | Drive | Measure | Illuminate

**guochaodongg**

From Driver Firmware to Advanced Displays

</div>

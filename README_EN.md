<p align="left"><img alt="OSPTEK" src="./images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 3.97″ TFT 480×800 (GC9503CV · MIPI)</h1>

<p align="center"><b>TFT / IPS module · MIPI · GC9503CV</b></p>

<p align="center"><a href="./README.md">简体中文</a> | English</p>

<p align="center">
  <img alt="Size: 3.97 inch" src="https://img.shields.io/badge/Size-3.97%22-3498DB?style=flat-square" />
  <img alt="Resolution: 480x800" src="https://img.shields.io/badge/Resolution-480%C3%97800-8E44AD?style=flat-square" />
  <img alt="Interface: MIPI" src="https://img.shields.io/badge/Interface-MIPI-27AE60?style=flat-square" />
  <img alt="Driver: GC9503CV" src="https://img.shields.io/badge/Driver-GC9503CV-E7352C?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 3.97″ 480×800 TFT MIPI module (GC9503CV) product image" src="./images/product.png" width="640" /></p>

## Contents

- [Overview](#overview)
- [Specifications](#specifications)
- [Sample projects](#sample-projects)
- [Repository layout](#repository-layout)
- [Resources](#resources)
- [Buy](#buy)
- [Support](#support)

---

## Overview

OSPTEK **3.97″ 480×800 TFT** is a **MIPI** color display module driven by **GC9503CV**. Suited to handheld devices, portrait instruments, and compact HMI.

Spec ID (repository name): `3.97-tft-480x800-mipi-gc9503cv`

Current module version: **YDP397B001-V1**. Electrical and mechanical details follow [`docs/YDP397B001-V1.pdf`](./docs/YDP397B001-V1.pdf).

## Specifications

| Item | Spec |
| ---- | ---- |
| Size | 3.97 inch |
| Type | TFT / IPS (color) |
| Resolution | 480×800 |
| Interface | MIPI |
| Driver IC | GC9503CV |

> Full outline, FPC definition, power, and timing follow the product datasheet / driver IC datasheet.

## Sample projects

| Description | Path |
| ---- | ---- |
| ESP32-P4 · GC9503CV MIPI DSI + LVGL | [`examples/3.97_gc9503cv_mipi_dsi/`](./examples/3.97_gc9503cv_mipi_dsi/) |
| ESP32-P4 · Arduino + GC9503 + LVGL | [`examples/arduino/esp32p4-arduino_gc9503_lvgl/`](./examples/arduino/esp32p4-arduino_gc9503_lvgl/) |

## Repository layout

```text
3.97-tft-480x800-mipi-gc9503cv/
├── README.md
├── README_EN.md
├── MODULE_VERSION.md
├── LICENSE
├── images/          # README assets
├── docs/            # datasheets, init, etc.
└── examples/        # sample projects
```

## Resources

### Product files

| Resource | Link |
| ---- | ---- |
| Product datasheet (YDP397B001-V1) | [`docs/YDP397B001-V1.pdf`](./docs/YDP397B001-V1.pdf) |
| Driver IC datasheet (GC9503CV) | [`docs/GC_9503_CV_Data_Sheet_V1_0_1_bf6521995e.pdf`](./docs/GC_9503_CV_Data_Sheet_V1_0_1_bf6521995e.pdf) |
| Init sequence (text) | [`docs/GC9503V_BOE3.97_BV040WVQ-N80_20200513_AN.txt`](./docs/GC9503V_BOE3.97_BV040WVQ-N80_20200513_AN.txt) |

### Samples

- [ESP32-P4 GC9503CV MIPI DSI + LVGL](./examples/3.97_gc9503cv_mipi_dsi/)
- [ESP32-P4 Arduino + GC9503 + LVGL](./examples/arduino/esp32p4-arduino_gc9503_lvgl/)

## Buy

<p align="center">
  <a href="https://www.aliexpress.com/store/1105701619"><img alt="AliExpress store" src="https://img.shields.io/badge/AliExpress-Official_Store-FF6A00?style=for-the-badge" /></a>
  &nbsp;&nbsp;
  <a href="https://shop110742373.taobao.com/"><img alt="Taobao store" src="https://img.shields.io/badge/Taobao-Official_Store-FF6A00?style=for-the-badge" /></a>
</p>

**Overseas (AliExpress)**

- Store: [OSPTEK Official Store](https://www.aliexpress.com/store/1105701619)

**China (Taobao)**

- Store: [鱼鹰光电工厂店](https://shop110742373.taobao.com/)

## Support

- Technical support / product inquiry: <luyu@osptek.com>
- QQ group: **985881096**
- Website: <https://osptek.com/>
- Feel free to open an Issue in this repository with any questions

---

<p align="center"><sub>© 2026 OSPTEK · Materials in this repository are licensed under CC BY 4.0</sub></p>

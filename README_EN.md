# 3.97" 480×800 TFT MIPI module (GC9503CV) — documentation & samples

**简体中文：** [`README.md`](README.md)

---

> This repository provides **sample projects** for this module, together with datasheets, specifications, and interface / bring-up documentation for selection reference and integration.

## Product overview

| Item | Description |
|:--|:--|
| Module | 3.97-inch **TFT** panel, **480×800** resolution |
| Interface | **MIPI** |
| Driver IC | **GC9503CV** |
| Spec ID | **`3.97-tft-480x800-mipi-gc9503cv`** is the common product designation in documentation |

---

## Repository layout

### Top-level

| Path | Contents |
|:--|:--|
| `docs/` | Datasheets, specifications, initialization documentation (add per release package) |
| `examples/` | **Sample projects** |

### `examples/` layout

| Location | Description (internal package folder) |
|:--|:--|
| `examples/` root | **idf** (MIPI DSI + LVGL) |
| `arduino/` | **arduino** (Arduino + LVGL) |

### Sample project paths

| Description | Path |
|:--|:--|
| GC9503CV MIPI DSI + LVGL | `examples/3.97_gc9503cv_mipi_dsi/` |
| Arduino + LVGL | `examples/arduino/esp32p4-arduino_gc9503_lvgl/` |

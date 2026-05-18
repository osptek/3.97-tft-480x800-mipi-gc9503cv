# 3.97 寸 480×800 TFT MIPI 模组（GC9503CV）资料与示例

**English：** [`README_EN.md`](README_EN.md)

---

> 本仓库提供该模组的 **示例工程**，以及数据手册、规格与接口说明等资料，便于选型参考与集成开发。

## 产品概要

| 项目 | 说明 |
|:--|:--|
| 模组规格 | 3.97 英寸 **TFT**，分辨率 **480×800** |
| 接口 | **MIPI** |
| 驱动芯片 | **GC9503CV** |
| 规格标识 | 产品资料中常用 **`3.97-tft-480x800-mipi-gc9503cv`** 表示本规格 |

---

## 仓库结构

### 顶层目录

| 路径 | 说明 |
|:--|:--|
| `docs/` | 数据手册、规格说明、屏幕初始化相关文档（随资料包补充） |
| `examples/` | **示例工程** |

### `examples/` 分类

| 分类 | 说明（对应内部资料目录） |
|:--|:--|
| `examples/` 根目录 | **idf**（MIPI DSI + LVGL） |
| `arduino/` | **arduino**（Arduino + LVGL） |

### 示例工程路径

| 说明 | 路径 |
|:--|:--|
| GC9503CV MIPI DSI + LVGL | `examples/3.97_gc9503cv_mipi_dsi/` |
| Arduino + LVGL | `examples/arduino/esp32p4-arduino_gc9503_lvgl/` |

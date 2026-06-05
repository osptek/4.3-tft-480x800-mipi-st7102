# 4.3" 480×800 TFT MIPI module (ST7102) — documentation & samples

**简体中文：** [`README.md`](README.md)

---

> This repository provides **sample projects** for this module, together with datasheets, specifications, and interface / bring-up documentation for selection reference and integration.

## Product overview

| Item | Description |
|:--|:--|
| Module | 4.3-inch **TFT** panel, **480×800** resolution |
| Interface | **MIPI** |
| Driver IC | **ST7102** |
| Spec ID | **`4.3-tft-480x800-mipi-st7102`** is the common product designation in documentation |

---

## Repository layout

### Top-level

| Path | Contents |
|:--|:--|
| `docs/` | Datasheets, specifications, adapter schematics |
| `examples/` | **Sample projects** grouped by feature (ESP-IDF, Linux, etc.) |

### `examples/` layout

| Location | Description (internal package folder) |
|:--|:--|
| `examples/` root | **ESP-IDF代码** (esp-lvgl-port + LVGL9) |
| `with-te/` | Tear-related samples (**屏幕防撕裂代码**) |
| `camera/` | Display with camera (**屏幕配合摄像头代码**) |
| `linux/` | **Linux reference** (RK3566 device tree + ST7123 touch) |

### Sample project paths

#### Baseline (`examples/` root)

| Description | Path |
|:--|:--|
| esp-lvgl-port + LVGL9 | `examples/esp32p4-idf5_st7102-mipi_esp-lvgl-port_lvgl9/` |

#### Tear-related (`with-te/`)

| Description | Path |
|:--|:--|
| LVGL common demo | `examples/with-te/p4-idf_st7102-mipi_lvgl-common-demo/` |

#### Camera (`camera/`)

| Description | Path |
|:--|:--|
| ST7102 MIPI + SC2336 camera preview | `examples/camera/esp32p4-idf5_st7102-mipi-dsi_sc2336-mipi-csi_video-lcd-display/` |

#### Linux reference (`linux/`）

See **[`examples/linux/README_EN.md`](examples/linux/README_EN.md)**.

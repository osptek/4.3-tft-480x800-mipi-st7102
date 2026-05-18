# 4.3 寸 480×800 TFT MIPI 模组（ST7102）资料与示例

**English：** [`README_EN.md`](README_EN.md)

---

> 本仓库提供该模组的 **示例工程**，以及数据手册、规格与接口说明等资料，便于选型参考与集成开发。

## 产品概要

| 项目 | 说明 |
|:--|:--|
| 模组规格 | 4.3 英寸 **TFT**，分辨率 **480×800** |
| 接口 | **MIPI** |
| 驱动芯片 | **ST7102** |
| 规格标识 | 产品资料中常用 **`4.3-tft-480x800-mipi-st7102`** 表示本规格 |

---

## 仓库结构

### 顶层目录

| 路径 | 说明 |
|:--|:--|
| `docs/` | 数据手册、规格说明、转接板原理图等 |
| `examples/` | 按功能分类的 **示例工程** |

### `examples/` 分类

| 分类 | 说明（对应内部资料目录） |
|:--|:--|
| `examples/` 根目录 | **ESP-IDF代码**（esp-lvgl-port + LVGL9） |
| `with-te/` | **屏幕防撕裂代码** |
| `camera/` | **屏幕配合摄像头代码** |

### 示例工程路径

#### 基础（`examples/` 根目录）

| 说明 | 路径 |
|:--|:--|
| esp-lvgl-port + LVGL9 | `examples/esp32p4-idf5_st7102-mipi_esp-lvgl-port_lvgl9/` |

#### 屏幕防撕裂代码（`with-te/`）

| 说明 | 路径 |
|:--|:--|
| LVGL 通用演示 | `examples/with-te/p4-idf_st7102-mipi_lvgl-common-demo/` |

#### 屏幕配合摄像头代码（`camera/`）

| 说明 | 路径 |
|:--|:--|
| ST7102 MIPI + SC2336 摄像头预览 | `examples/camera/esp32p4-idf5_st7102-mipi-dsi_sc2336-mipi-csi_video-lcd-display/` |

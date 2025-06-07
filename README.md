# JC1060P4A1 Demo

> 深圳晶彩智能 JC1060P4A1 开发屏幕演示项目

## 简介

JC1060P4A1 是深圳晶彩智能推出的一款多功能开发屏幕产品，内置 ESP32P4 + C6 双芯片组合，集成扬声器、摄像头和麦克风，配备 10.1 英寸 1280×800 分辨率电容触摸屏。此 Demo 项目旨在展示硬件各部分功能的使用示例，包括触摸交互、音视频采集和播放等。

## 主要特性

* **双芯片架构**：ESP32P4 负责主控与无线通信，C6 负责图像编解码与显示驱动。
* **多媒体外设**：集成扬声器、摄像头和麦克风。
* **高分触摸屏**：10.1" 1280×800 电容触摸屏，支持多点触控。
* **扩展接口**：预留 GPIO、I2C、SPI 等接口，可外接传感器和其他模块。
* **易用 SDK**：基于 ESP-IDF /arduino开发，提供丰富示例和 API 文档。

## 目录结构

```text
├── 1-Demo/                        # 演示代码与示例
├── 2-Specification/               # 产品规格书
├── 3-Structure_Diagram/           # 硬件结构图
├── 4-Driver_IC_Data_Sheet/        # 驱动芯片数据手册
├── 5-Schematic/                   # 原理图
├── 6-User_Manual/                 # 用户手册
├── 7-Character&Pictures_Molding_Tool/  # 字符与图像打包工具
└── 8-Burn operation/              # 烧录指南
```


## 烧录操作

详细的烧录步骤及常见问题请参见 `8-Burn operation` 目录下的指南文档。

## 规范与资源

* 产品规格书：`2-Specification/` 目录。
* 硬件结构图：`3-Structure_Diagram/`。
* 驱动芯片手册：`4-Driver_IC_Data_Sheet/`。
* 原理图：`5-Schematic/`。
* 用户手册：`6-User_Manual/`。
* 字符与图像打包工具：`7-Character&Pictures_Molding_Tool/`。

## 贡献

欢迎提交 Issue 和 Pull Request，共同完善示例与文档。

## 许可证

本项目遵循 MIT 许可证，详情见 [LICENSE](LICENSE) 文件。

# AQCM_Library

> 安庆师范大学皖江逐影智能车战队开源库（AQCM_Library）  
> 基于官方 HAL 库的第三方扩展集合，适用于 STM32F103 系列。

## 📘 项目简介
AQCM_Library 是一个结构化、模块化的嵌入式软件集合，用于教学、科研与智能车竞赛。
项目目标是提供一套轻量级 HAL 封装接口，便于二次开发与快速移植。

## 🧩 项目特性
- 驱动层：PWM、ADC、PIT、GPIO、UART、Timer、Capture、Delay、Soft IIC
- 外设层：舵机 SG90、OLED 显示、TB6612 电机驱动、超声测距、灰度传感器
- 调试模块：串口调试输出（UART 调试模块）
- 中断管理：统一中断配置与回调机制
- 模块化设计，结构清晰，便于教学和竞赛使用

## 🧱 工程信息
- 开发环境：Keil MDK-ARM V5.38 (ARM Compiler 5.06u7)
- MCU 平台：STM32F103C8T6
- 项目仓库：[https://github.com/WKing-1217/AQCM_Library](https://github.com/WKing-1217/AQCM_Library)
- 联系方式：2570551878@qq.com

## ⚠️ 注意事项
- 以下引脚不推荐使用：PC14、PC15、PD0、PD1、PA13、PA14、PB2
- 使用本库前，请确认 HAL 库版本与工程兼容
- 使用前请阅读各模块文件头注释，了解初始化流程与依赖关系

## 📜 许可证
本项目基于 [GNU General Public License v3.0 (GPL-3.0)](./LICENSE) 发布。
你可以自由复制、修改与传播本项目，但派生作品必须保留相同的许可证。

© 2025 AQCM 安庆师范大学皖江逐影智能车战队


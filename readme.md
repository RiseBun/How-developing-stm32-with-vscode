# 使用 VSCode 和 CubeMX 开发 STM32

> 一个代码开发友好的 STM32 开发环境搭建指南。

本项目旨在提供一份详尽的教程，指导开发者如何利用 **STM32CubeMX** 和 **Visual Studio Code (VSCode)** 搭建高效、现代化的 STM32 嵌入式开发环境。通过此方案，您可以摆脱对大型 IDE（如 Keil 或 IAR）的依赖，享受 VSCode 强大的代码编辑、智能提示和插件生态带来的便利。

##  项目概述

本指南详细介绍了如何：
1.  使用 STM32CubeMX 图形化配置 MCU 外设和生成初始化代码。
2.  配置 VSCode 及其相关插件（如 C/C++, Cortex-Debug, CMake 等）。
3.  集成 GCC 编译工具链（如 arm-none-eabi-gcc）。
4.  设置调试环境（通过 OpenOCD 或 J-Link 等）。
5.  实现代码编译、烧录和调试的完整开发流程。

目标是建立一个轻量、快速、跨平台且代码友好的开发体验。

##  主要内容

本项目包含以下主要文档：

-   `how_to_install.md`: **安装教程** - 详细说明所需软件、工具链的下载、安装与配置步骤。
-   `how_to_use.md`: **使用说明** - 指导如何创建新项目、导入 CubeMX 生成的代码、在 VSCode 中进行编译和调试。
-   `how_it_works.md`: **原理详解** - 解释该开发环境背后的工作机制，例如任务配置、调试配置、构建脚本等。

##  安装教程

请参考 [how_to_install.md](how_to_install.md) 文件获取完整的安装和环境配置指南。

##  使用说明

请参考 [how_to_use.md](how_to_use.md) 文件了解如何使用此开发环境进行日常开发。

##  工作原理

请参考 [how_it_works.md](how_it_works.md) 文件深入理解 VSCode 配置文件（如 `tasks.json`, `launch.json`, `c_cpp_properties.json`）是如何协同工作的。

## 📁 文件结构

本项目的目录结构如下：

```
How-developing-stm32-with-vscode/
├── .gitignore          # Git 忽略配置文件
├── imgs/               # 存放项目相关图片（如配置截图）
├── how_to_install.md   # 安装教程：环境搭建与工具配置
├── how_to_use.md       # 使用说明：项目创建与开发流程
├── how_it_works.md     # 原理解析：VSCode 配置文件详解
└── README.md           # 项目说明文档（即本文件）
```

> 💡 建议按 `how_it_works.md`→`how_to_install.md` → `how_to_use.md`的顺序阅读。1

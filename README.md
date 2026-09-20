# 基于 FreeRTOS 的无人机项目 (fight_HAL)

## 📖 项目简介
本项目是一个基于 FreeRTOS 实时操作系统的无人机飞控与遥控系统。代码分为飞控端（P01_flight_hal）和遥控端（P02_remote_hal）两部分。

## 🛠️ 技术栈
*   **硬件平台**：STM32系列微控制器
*   **操作系统**：FreeRTOS 实时操作系统
*   **开发工具**：Keil MDK (uVision)
*   **编程语言**：C / C++

## 🚀 主要功能
*   **飞控端 (P01_flight_hal)**：负责姿态解算、电机控制、传感器数据读取及 FreeRTOS 任务调度。
*   **遥控端 (P02_remote_hal)**：负责无线通信、摇杆数据采集与指令发送。

## 📂 目录结构
*   `P01_flight_hal.uvprojx`：飞控端 Keil 工程文件
*   `P02_remote_hal.uvprojx`：遥控端 Keil 工程文件

## 🔧 如何运行
1. 使用 Keil MDK 打开对应的 `.uvprojx` 工程文件。
2. 编译工程并烧录至对应的 STM32 开发板。

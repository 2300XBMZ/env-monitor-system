# 🌍 环境监测数据分析系统

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.13.7-blue.svg" alt="Python Version">
  <img src="https://img.shields.io/badge/Pandas-2.0.0-green.svg" alt="Pandas">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License">
  <img src="https://img.shields.io/badge/Status-Active-success.svg" alt="Status">
</p>

## 📖 项目简介

本项目是一个基于 Python 的环境监测数据分析系统，用于处理和分析环境传感器采集的数据，包括温度、湿度、PM2.5等指标，并生成可视化分析报告。

### ✨ 主要功能

- 📊 **数据加载**：自动读取CSV格式的传感器数据
- 📈 **统计分析**：多维度统计分析（基础统计、站点对比、时间趋势）
- 🌤️ **空气质量评估**：基于PM2.5指标的空气质量分级
- 📉 **数据可视化**：生成时间序列图、分布图、相关性热图
- 🏢 **站点对比**：多监测站点数据对比分析

---

## 🚀 快速开始

### 环境要求

- Python 3.10 或更高版本
- Git 2.0 或更高版本

### 安装步骤

```bash
# 1. 克隆项目
git clone https://github.com/你的用户名/env-monitor-system.git
cd env-monitor-system

# 2. 安装依赖包
pip install -r requirements.txt

# 3. 生成模拟数据
python data/generate_data.py

# 4. 运行主程序
python src/main.py

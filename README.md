# 🌍 行星轨道数值模拟

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)

## 📖 项目简介

基于牛顿万有引力定律，使用 Python 进行行星绕日运动的数值模拟。通过求解二阶常微分方程组，直观展示不同初始条件下的轨道类型（椭圆、圆、抛物线、双曲线），并验证开普勒三大定律。

## ✨ 主要功能

- 🪐 二体引力模型数值求解
- 📊 轨道可视化（圆形、椭圆、抛物线、双曲线）
- ✅ 开普勒第二定律验证（面积速率恒定）
- ✅ 开普勒第三定律验证（T² ∝ a³）
- 🔬 能量守恒与角动量守恒检验

## 🛠 技术栈

| 类别 | 工具/库 |
|------|---------|
| 语言 | Python 3.8+ |
| 数值计算 | NumPy, SciPy |
| 可视化 | Matplotlib |
| 环境 | Jupyter Notebook |

## 🚀 快速开始

```bash
# 安装依赖
pip install -r requirements.txt

# 启动 Notebook
jupyter notebook planet_orbit.ipynb
├── planet_orbit.ipynb      # 主程序（含完整推导与代码）
├── requirements.txt        # Python 依赖
├── images/                 # 输出图片
└── README.md              # 本文件


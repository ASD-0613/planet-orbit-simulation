# 🌍 行星轨道数值模拟

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)

##  项目简介

本项目基于**牛顿万有引力定律**，使用 Python 对行星绕日运动进行数值模拟。通过求解二阶常微分方程组，直观展示不同初始条件下的轨道类型（椭圆、圆、抛物线、双曲线），并验证**开普勒三大定律**。

---

##  主要功能

-  二体引力模型：基于万有引力定律建立微分方程
-  数值求解：使用 `scipy.integrate.solve_ivp` 进行高精度积分
-  可视化：轨道图、能量守恒图、多初速度对比图
-  物理验证：
  - 开普勒第二定律（面积速率恒定）
  - 开普勒第三定律（T² ∝ a³）
  - 能量守恒与角动量守恒检验
-  展示四种圆锥曲线轨道：椭圆、圆形、抛物线、双曲线

---

##  技术栈

| 类别 | 工具/库 |
|------|---------|
| 编程语言 | Python 3.8+ |
| 数值计算 | NumPy, SciPy |
| 可视化 | Matplotlib |
| 开发环境 | Jupyter Notebook, PyCharm |

---

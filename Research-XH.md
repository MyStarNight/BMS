# Research for Energy Management System

# Home Energy Management System

电池采用的单位一般为（kWh）

## business cases
[2023 年最佳家用电池和备用系统 |ZDNET公司](https://www.zdnet.com/home-and-office/energy/best-home-battery/) 


# Battery Charging and Discharging Model

## develop tools

### Mathworks
Mathworks所提供的[Battery](https://www.mathworks.com/help/sps/powersys/ref/battery.html)模块，可以用来模拟电池的充放电；即使用simulink对模型实现仿真。

![](https://www.mathworks.com/help/sps/powersys/ref/batteryh.gif)

### PyBaMM

[PyBaMM（Python Battery Mathematical Modelling）](https://github.com/pybamm-team/PyBaMM/tree/develop)是一个用Python编写的开源电池模拟包。我们的使命是通过提供多机构、跨学科合作的开源工具，加速电池建模研究的进展。广义上，PyBaMM包括（i）用于编写和求解微分方程系统的框架，（ii）一组电池模型和参数的库，以及（iii）用于模拟电池特定实验和可视化结果的专业工具。总体而言，这些组成部分使得能够灵活定义模型并进行快速的电池模拟，使用户能够在各种操作场景下探索不同电池设计和建模假设的影响。

## some papers

> Deep Reinforcement Learning for Smart Home Energy Management

在本文中，介绍了一种ESS（Energy Storage System）的数学模型，但是缺点在于它不能实现同时充放电。


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTQ2MjYyNDE4NF19
-->
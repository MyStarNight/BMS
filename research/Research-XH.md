# Research for Energy Management System

# Home Energy Management System

**Point：**

1. 电池采用的单位一般为kWh
2. ESS系统的采用一般来说不会在策略上考虑很多；一般是利用新能源（太阳能等）去存储电量作备用电源
3. 对于想利用EMS去进行省钱，一般会对家电的使用时间、策略上进行调整

## business cases

[2023 年最佳家用电池和备用系统 |ZDNET公司](https://www.zdnet.com/home-and-office/energy/best-home-battery/) ：主要介绍了四种电池能源供应方案
|Company| Capacity(kWh) |Notes|
|--|--|--|
| Tesla Powershell +| 13.5 |备用电源；在停电期间依靠光伏充电；并且可以堆叠|
| Generac PWRcell| 36|备用电源；太阳能电池板|
|Panasonic Evervolt| 102|直流耦合电池系统；包括可编程控制器；太阳能电池板|
|Enphase IQ Battery 10T| 10.08|适合大多数家庭；为小型家庭提供的；自动远程更新|



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
eyJoaXN0b3J5IjpbLTE4NTE5MzkwNjZdfQ==
-->
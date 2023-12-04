# Research
# Battery Charging  Model

## paper

> A_Review_of_Charging_Algorithms_for_Nickel_and_Lithium_Battery_Chargers

文章给出了一种锂电池的充电策略：在充电期间持续监控温度，通过测量电池的初始开路电压开始充电。如果该值介于 2.9 V/cell 和 4.2 V/cell 之间，则将保持以 0.7 C 电流充电，直到达到电压上限或超时。然后，CV 模式启动，直到电流降至阈值以下或达到超时。如果初始 OCV 低于 2.9 V/cell，则将持续以低至 0.1 C 的电流充电，直至 OCV 达到 3 V/cell，此时将应用 0.7 C 的快速充电电流。如果充电时温度偏离一定范围，电池将被断开，直到温度恢复到规定范围。为了安全起见，充电将在 720 分钟后自动终止。
<img src="https://img-blog.csdnimg.cn/direct/e9248ed0944749a2b8e01cda444efb90.png" width="50%">

>锂电池充放电模型及关键参数影响研究_刘娇娇

文章给出了锂电池等效电路模型以及放电参数的计算公式

![](https://img-blog.csdnimg.cn/direct/78ae13ef29644619bd6c86229f890d2d.png ) 电路模型

<img src="https://img-blog.csdnimg.cn/direct/8702c2bd0328424eb2d28f244d4988ac.png" width="50%"> 电路参数公式

式中：E0 为锂电池内电势，V；K 为锂电池极化电压，V；Cmax 为 锂电池的最大容量，Ah；Qe 为锂电池充放电量，Ah；A 为指数 区电压振幅，V；B 为指数区时间常数的倒数；Efull 为电池满充 电压，V；Eexp 为锂电池放电曲线中指数区的截止电压，V；通常 锂电池厂家会给定电池的额定电压 Erated ，按照锂电池的特性， Erated=0.929 5Eexp ；Qexp 为指数区域的电池容量，Ah；Enom 为放电 截 止 电 压 ，V；Qnom 为锂电池放电曲线中线性区的电池容量， Ah；R 为锂电池内电阻，Ω；Inom 为锂电池额定放电电流，A；锂 电池的额定放电电流和最大容量呈线性关系， Inom=0.434 783 Cmax ；IB 是流过锂电池的电流，单位为 A；h 是锂 电池的充放电效率，根据经验可0.995~0.998。
# Battery capacity
| 地区 |  2020年居民人均年用电量（kw*h）|参考电池容量（kw*h），以年人均用电量除以180得到
|--|--|--|
| 瑞典 | 13085 |73

参考网址：https://www.indexmundi.com/map/?v=81000&r=eu&l=zh




 

<!--stackedit_data:
eyJoaXN0b3J5IjpbNDI5ODA4NzM4LDExMDg0MTcwMDksNTM2MT
AxNTk2LDcyMDI4MDEzNywtMTkzNTY0OTA4OCwtMTI0NDEyNTE5
OSw1NTY2NDc1ODhdfQ==
-->
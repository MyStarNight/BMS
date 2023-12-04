# Research
# Battery Charging  Model

## paper

> A_Review_of_Charging_Algorithms_for_Nickel_and_Lithium_Battery_Chargers

文章给出了一种锂电池的充电策略：在充电期间持续监控温度，通过测量电池的初始开路电压开始充电。如果该值介于 2.9 V/cell 和 4.2 V/cell 之间，则将保持以 0.7 C 电流充电，直到达到电压上限或超时。然后，CV 模式启动，直到电流降至阈值以下或达到超时。如果初始 OCV 低于 2.9 V/cell，则将持续以低至 0.1 C 的电流充电，直至 OCV 达到 3 V/cell，此时将应用 0.7 C 的快速充电电流。如果充电时温度偏离一定范围，电池将被断开，直到温度恢复到规定范围。为了安全起见，充电将在 720 分钟后自动终止。
<img src="https://img-blog.csdnimg.cn/direct/e9248ed0944749a2b8e01cda444efb90.png" width="50%">

>锂电池充放电模型及关键参数影响研究_刘娇娇

文章给出了锂电池等效电路模型以及放电参数的计算公式

![](https://img-blog.csdnimg.cn/direct/78ae13ef29644619bd6c86229f890d2d.png ) di


![](https://img-blog.csdnimg.cn/direct/8702c2bd0328424eb2d28f244d4988ac.png )
# Battery capacity
| 地区 |  2020年居民人均年用电量（kw*h）|参考电池容量（kw*h），以年人均用电量除以180得到
|--|--|--|
| 瑞典 | 13085 |73

参考网址：https://www.indexmundi.com/map/?v=81000&r=eu&l=zh




 

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTM4MTAxNjY1Miw1MzYxMDE1OTYsNzIwMj
gwMTM3LC0xOTM1NjQ5MDg4LC0xMjQ0MTI1MTk5LDU1NjY0NzU4
OF19
-->
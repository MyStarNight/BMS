# Research
# Battery Charging  Model

## paper

> A_Review_of_Charging_Algorithms_for_Nickel_and_Lithium_Battery_Chargers

文章给出了一种锂电池的充电策略：在充电期间持续监控温度，通过测量电池的初始开路电压开始充电。如果该值介于 2.9 V/cell 和 4.2 V/cell 之间，则将保持以 0.7 C 电流充电，直到达到电压上限或超时。然后，CV 模式启动，直到电流降至阈值以下或达到超时。如果初始 OCV 低于 2.9 V/cell，则将持续以低至 0.1 C 的电流充电，直至 OCV 达到 3 V/cell，此时将应用 0.7 C 的快速充电电流。如果充电时温度偏离一定范围，电池将被断开，直到温度恢复到规定范围。为了安全起见，充电将在 720 分钟后自动终止。
<img src="https://img-blog.csdnimg.cn/direct/e9248ed0944749a2b8e01cda444efb90.png" width="50%">

# Battery capacity
| 5 | 1 | 1
|--|--|--|
|  4|  5| D




 

<!--stackedit_data:
eyJoaXN0b3J5IjpbODcwODMxMzgsLTEyNDQxMjUxOTksNTU2Nj
Q3NTg4XX0=
-->
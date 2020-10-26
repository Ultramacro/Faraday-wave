<center><font size=6, color=blue>法拉第波实验</font></center>

**法拉第波**（英语：Faraday waves 或 Faraday ripples）是在气液分界面上，由于流体[不稳定性](https://zh.wikipedia.org/wiki/不稳定性)（法拉第不稳定性）产生的一种[非线性](https://zh.wikipedia.org/wiki/非線性)[驻波](https://zh.wikipedia.org/wiki/駐波)，当其振荡频率超过临界值时，气液分界面就会不稳定，可用于液基微小物体聚集器，法拉第波得名自[麦可·法拉第](https://zh.wikipedia.org/wiki/麥可·法拉第)（Michael Faraday）。

若将一层液体放置在垂直振荡的活塞顶部，则会出现以一半驱动频率振荡的驻波模式，可以给出某些不稳定性的标准[[3\]](https://zh.wikipedia.org/wiki/法拉第波#cite_note-3)。 这涉及[参数共振](https://zh.wikipedia.org/w/index.php?title=參數共振&action=edit&redlink=1)的问题。驻波可能以条纹、紧密堆积的六边形、甚至正方形或准周期的型式出现。在可发出铃铛声般的葡萄酒酒杯内，葡萄酒表面通常可以观察到细条纹的法拉第波。 



星形的对称性（即分支的数量）与容器的形状和大小无关，并且可以根据振动的==幅度和频率==进行更改。 我们表明，可以设想三个重力波之间的非线性共振耦合来触发观察到的对称性破坏，尽管在最终的周期性状态中肯定会发生更复杂的相互作用。

固定频率8Hz，增大振幅，圆形波，离心centrifugal和向心centripetal。进一步增大振幅，出现五边形图案



1.熟悉试验设备

2.学习faraday波原理，线性水动力方程推导，Floquet理论求解

亚谐振：振动圆频率=2*波圆频率，图案会旋转$\pi/N$

两个振动加速度幅值的阈值：a1:Faraday threshold   a2:disorder threshold

![image-20201025171721684](C:\Users\DELL\AppData\Roaming\Typora\typora-user-images\image-20201025171721684.png)

![image-20201025171739192](C:\Users\DELL\AppData\Roaming\Typora\typora-user-images\image-20201025171739192.png)

3.尝试拍出论文中很漂亮的faraday波形图，实际经过多种调整，图片差强人意。

* 纯硅油，到五阶模态前的波形都很清楚，与论文给出的模态图片很接近，但是第六阶（也就是六边形）的波形混乱
* 液体内部的流体运动对拍摄有干扰（李靖老师也有提到），我们想要得到的仅仅是表面波形

为此我们做了一些尝试

* 在器皿底部垫的滤光片
* 调整拍摄角度和光照角度

* 不透明液体（牛奶），确实只能看到表面波形
* 墨水（含稀释），吸收折射光
* 器皿内部底部形成一层吸光层，我们在硅油中加入一层墨水
* 硅油

<img src="F:\faraday_video\h6s1.3f10.1.gif" alt="h6s1.3f10.1" style="zoom:70%;" />

<img src="F:\faraday_video\h6s1f12.gif" alt="h6s1f12" style="zoom:70%;" />

<img src="F:\faraday_video\h6s1f13.4.gif" alt="h6s1f13.4" style="zoom:70%;" />

<img src="F:\faraday_video\h6s1N5.gif" alt="h6s1N5" style="zoom:70%;" />

水

<img src="F:\faraday_video\purewater.gif" alt="purewater" style="zoom:70%;" />

墨水

<img src="F:\faraday_video\ink3.gif" alt="ink3" style="zoom:70%;" />

滤光纸底部

<img src="F:\faraday_video\h5s1.1N3_bottom.gif" alt="h5s1.1N3_bottom" style="zoom:70%;" />

墨水底

<img src="F:\faraday_video\inkbottom.gif" alt="inkbottom" style="zoom:200%;" />

<img src="C:\Users\DELL\AppData\Roaming\Typora\typora-user-images\image-20201025165852521.png" alt="image-20201025165852521" style="zoom:150%;" />

牛奶

<img src="F:\faraday_video\milk4.gif" alt="milk4" style="zoom:70%;" />

对比

![image-20201025164740169](C:\Users\DELL\AppData\Roaming\Typora\typora-user-images\image-20201025164740169.png)

<img src="C:\Users\DELL\AppData\Roaming\Typora\typora-user-images\image-20201025165545182.png" alt="image-20201025165545182" style="zoom:50%;" />

<img src="C:\Users\DELL\AppData\Roaming\Typora\typora-user-images\image-20201025165311447.png" alt="image-20201025165311447" style="zoom:50%;" />



问题

* 六阶模态后，比较混乱
* 水平问题
* 表面波形问题（液体内部流动的干扰）
* 黑白高速摄像机CCD？，需要灯光很亮
* 灯光的布置

尝试

* 加色素
* 彩色摄像机和灯光
* 其它液体材料

| 液高h(mm) | 位移峰峰值s(mm) | 频率f(Hz) | 模态N | 备注         | 圆频率   | 加速度   | 波频率 | 波圆频率 | 波长 | 波数 |
| --------- | --------------- | --------- | ----- | ------------ | -------- | -------- | ------ | -------- | ---- | ---- |
| 5         | 1.2             | 11.3-12.0 | 3     |              | 70.99993 | 6.049189 | 5.65   | 35.49997 |      |      |
| 5         | 1.2             | 13.2      | 4     |              | 82.93798 | 8.254449 | 6.6    | 41.46899 |      |      |
|           |                 |           |       |              |          |          |        |          |      |      |
| 6         | 1               | 11.8      | 3     |              | 74.14152 | 5.496966 | 5.9    | 37.07076 |      |      |
| 6         | 1               | 13.2      | 4     |              | 82.93798 | 6.878708 | 6.6    | 41.46899 |      |      |
| 6         | 1               | 14.8      | 5     |              | 92.99106 | 8.647338 | 7.4    | 46.49553 |      |      |
| 6         | 1               | 16.3      | 6     |              | 102.4158 | 10.489   | 8.15   | 51.20792 |      |      |
| 6         | 1               | 17.8      | 7     |              | 111.8406 | 12.50832 | 8.9    | 55.9203  |      |      |
|           |                 |           |       |              | 0        | 0        | 0      | 0        |      |      |
| 6         | 1.2             | 10.3      | 2     | 不可高于17Hz | 64.71675 | 5.02591  | 5.15   | 32.35838 |      |      |
| 6         | 1.2             | 11.8      | 3     |              | 74.14152 | 6.596359 | 5.9    | 37.07076 |      |      |
| 6         | 1.2             | 13.3      | 4     |              | 83.56629 | 8.379991 | 6.65   | 41.78315 |      |      |
| 6         | 1.2             | 14.7      | 5     |              | 92.36275 | 10.23705 | 7.35   | 46.18137 |      |      |
| 6         | 1.2             | 16.3      | 6     |              | 102.4158 | 12.5868  | 8.15   | 51.20792 |      |      |
|           |                 |           |       |              | 0        | 0        | 0      | 0        |      |      |
| 6         | 1.3             | 10.1      | 2     | 不可高于16Hz | 63.46012 | 5.235343 | 5.05   | 31.73006 |      |      |
| 6         | 1.3             | 11.6      | 3     |              | 72.88489 | 6.905869 | 5.8    | 36.44244 |      |      |
| 6         | 1.3             | 13.2      | 4     |              | 82.93798 | 8.94232  | 6.6    | 41.46899 |      |      |
| 6         | 1.3             | 14.6      | 5     |              | 91.73443 | 10.93977 | 7.3    | 45.86721 |      |      |

![image-20201025171148907](C:\Users\DELL\AppData\Roaming\Typora\typora-user-images\image-20201025171148907.png)

![image-20201025171243082](C:\Users\DELL\AppData\Roaming\Typora\typora-user-images\image-20201025171243082.png)

波形跟倾斜方向有关

波形重构同样是只要表面波形进行重构，滤去折射透射光很重要吧
# Netshoot
 
游戏实录视频：
链接：https://pan.baidu.com/s/13FzwpZZoeZ0CX-jUDLuc-Q 
提取码：59on 

在提供案例的基础上：
    
* 增加会飞的物件
  * 服务器端右侧的木桶可以被击飞。
* 打击物件支持网络同步移动
  * 这个实现的不是很好，一端击中木桶时另一端也会有反应，但是位置不一定同步。
* 固定位置物件，打击此物件额外加分
  * 服务器端右侧的箱子被击中时会为射击玩家加一分。
![](https://p.sda1.dev/6/369be6b478bca670af6b3d99367e9a55/3.png)
* 限制时间一分钟
  * 在右上角可以看到倒计时60秒，只在两个玩家都就位的情况下在计时，单人模式下不计时。
  ![](https://p.sda1.dev/6/d024576b6294a8429938d676b5cb206b/1.png)
* 结算ui
  * 在计时结束后会弹出。
  * 有得分情况，获胜，失败，平局。
  ![](https://p.sda1.dev/6/c1f6d0d4e7f1629feb07d610628e19d6/2.png)
  ![](https://p.sda1.dev/6/14c5e6eac3458a07ef783b115248caf7/4.png)
  ![](https://p.sda1.dev/6/a5e8708bbcb86b1b8afc1ed4a9185ce3/5.png)
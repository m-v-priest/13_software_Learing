- https://www.bilibili.com/video/BV17y4y1J71q?spm_id_from=333.999.0.0
- 创建fusion片段
  collapsed:: true
	- ![image.png](../assets/image_1660469791599_0.png)
	- ![image.png](../assets/image_1660469852285_0.png)
	- ![image.png](../assets/image_1660469929232_0.png)
	- 但注意: 你媒体池中的fusion片段, 和你拖到时间线上的fusion片段, 会被分成两个独立的片段, 彼此的编辑, 互不影响对方.
- 节点
	- 节点类型
	  collapsed:: true
		- ![image.png](../assets/image_1660470659327_0.png)
		- ![image.png](../assets/image_1660470674816_0.png)
		- ![image.png](../assets/image_1660470692158_0.png)
		- ![image.png](../assets/image_1660470700383_0.png)
		- ![image.png](../assets/image_1660470707130_0.png)
		- 每个节点的输入端, 只能连接一个输入
		- ![image.png](../assets/image_1660470752400_0.png)
		- ![image.png](../assets/image_1660470771158_0.png)
	- 重命名节点 F2
	  collapsed:: true
		- ![image.png](../assets/image_1660470843591_0.png)
		- 节点命名, 不能以数字为开头
	- 在监视器中显示
	  collapsed:: true
		- ![image.png](../assets/image_1660471010186_0.png)
		- 选中节点, 按数字键1或2, 来将它显示到对应的监视器上.
- 节点的逻辑
  collapsed:: true
	- ![image.png](../assets/image_1660471134939_0.png)
	- 原素材, 通过输入端, 进入到节点中, 来进行加工.
	- 加工好的内容, 通过输出端, 传给下一个加工厂, 进行下一步加工.
	- 最后的成品, 交给meidaout
	- 而mask遮罩, 就是告诉这个加工厂, 你只需要加工哪个部分(区域)
	-
	-
	-
- 案例1:
  collapsed:: true
	- ![image.png](../assets/image_1660471644648_0.png)
	- ![image.png](../assets/image_1660471940298_0.png)
	- ![image.png](../assets/image_1660472087440_0.png)
	- 我们还要看这个水墨片段, 是否包含alpha通道, 如下
	- ![image.png](../assets/image_1660472166141_0.png)
	- ![image.png](../assets/image_1660472241195_0.png)
	- ![image.png](../assets/image_1660472336989_0.png)
	- ![image.png](../assets/image_1660472464717_0.png)
	- luma keyer, 就是一个"亮度抠像节点"
	- ![image.png](../assets/image_1660473113237_0.png)
- 案例2
  collapsed:: true
	- ![image.png](../assets/image_1660474323661_0.png)
	- ![image.png](../assets/image_1660474360500_0.png)
	- ![image.png](../assets/image_1660474484420_0.png)
	- ![image.png](../assets/image_1660475364466_0.png)
	-
	-
	-
-
-
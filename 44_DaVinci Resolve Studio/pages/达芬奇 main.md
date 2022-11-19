-
- [[fusion]]
-
- 项目初始设置
	- 自动备份
	  collapsed:: true
		- 在"偏好设置-> 用户-> 项目保存和加载" 中, 可以打开自动备份, 以免软件崩溃文件丢失
			- ![image.png](../assets/image_1668773239260_0.png)
	- 缓存文件的位置
	  background-color:: pink
	  collapsed:: true
		- ![也 打 开 顶 目 设 ](file:///C:\Users\priest\AppData\Local\Temp\msohtmlclip1\01\clip_image001.png)
		- "代理媒体"的分辨率, 位置设置, 和"缓存"位置设置
		- ![image.png](../assets/image_1668772877990_0.png)
		-
	- 解码质量设置
	  collapsed:: true
		- ![image.png](../assets/image_1668773120788_0.png)
	- RAW
	  collapsed:: true
		- RAW只是保存传感器接收到的最原始的光的数据,  需要经过转化, 才能变成 log 画面. 所以RAW会比Log具有更大的可调性.
			- ![image.png](../assets/image_1668846401434_0.png)
			-
		-
	- 重新恢复默认界面
	  background-color:: pink
	  collapsed:: true
		- ![image.png](../assets/image_1668773299146_0.png)
	- 达芬奇一旦导入素材, 就无法修改项目的帧率, 所以, 在导入前,  就需要在 文件 -> 项目设置 -> 主设置 中, 设置好项目帧率.  之后再导入素材!
	- 历史记录
	  collapsed:: true
		- ![未命名图片.png](../assets/未命名图片_1668775122071_0.png)
		-
- ---
- 最常用功能
	- iphone 4k 视频导入问题
	  collapsed:: true
		- 遇到iphone 4k 载入视频是离线媒体的问题, 要安装HEVC解码器
		- 可以从第三方安装HEVC解码器。例如从“free-codecs”网站。
		- HEVC解码器：[https://www.free-codecs.com/download/hevc_video_extension.htm](https://link.zhihu.com/?target=https%3A//www.free-codecs.com/download/hevc_video_extension.htm)
		- 这是一个专门提供各种多媒体工具的网站，我们可以从中免费下载到HEVC解码器。选择对应的版本，安装即可，效果和从Win10商店下载的HEVC解码器是一致的。
	- 场景剪切探测
	  collapsed:: true
		- ![image.png](../assets/image_1668845061009_0.png)
		- ![image.png](../assets/image_1668845077327_0.png)
		- 在左下方, 点击 "自动探测", 之后可以点中间的"添加"(即手动添加)
		- ![image.png](../assets/image_1668845092728_0.png)
		-
	- 视频尺寸, 由横幅转成竖幅
	  background-color:: pink
	  collapsed:: true
		- 文件 -> 项目设置 -> 主设置 -> 选中 use vertical resolution
		  collapsed:: true
			- ![image.png](../assets/image_1668770080777_0.png)
		- 默认会变成这种样子:
		  collapsed:: true
			- ![image.png](../assets/image_1668770253894_0.png){:height 171, :width 169}
		- 所以还需要做这个设置:
		  collapsed:: true
			- ![image.png](../assets/image_1668770376436_0.png)
			- 或第二个也行, 它会自动缩放画面顶天立地, 左右则扩到画幅外面出去
				- ![image.png](../assets/image_1668770633869_0.png)
				- 效果:
				- ![image.png](../assets/image_1668770654662_0.png)
				-
			-
		-
	- 将尺寸不一素材的画面, 自动充满屏幕
	  collapsed:: true
		- 选中视频, 然后
		- ![image.png](../assets/image_1668774989980_0.png)
	- 上下加黑边
	  background-color:: blue
	  collapsed:: true
		- ![未命名图片.png](../assets/未命名图片_1668775517956_0.png){:height 326, :width 716}
	- 自动插帧, 让视频更平滑
	  background-color:: pink
	  collapsed:: true
		- 对单个片段独立进行插帧
		  collapsed:: true
			- ![image.png](../assets/image_1667370377289_0.png)
			- ![image.png](../assets/image_1668856656424_0.png)
		- 自动对所有素材, 进行插帧
		  collapsed:: true
			- ![image.png](../assets/image_1668856529169_0.png)
			- 三个参数,就是在改变素材速率时, 帧不够时, 如何"插帧"的算法:
			  collapsed:: true
				- 最近: 容易产生跳帧, 卡顿(一帧放了两遍)的情况
				- 帧混合  :
				  就是借助前后的帧, 来自动生成一个模糊的中间的帧
				- 光流算法: 也是自动算出中间的帧, 其缺点是容易算不出来.
	- 稳定器
	  collapsed:: true
		- ![image.png](../assets/image_1668845841437_0.png)
		- ![image.png](../assets/image_1668845848660_0.png)
		- ![image.png](../assets/image_1668845860744_0.png)
	- 静帧
	  collapsed:: true
		- 截图, 抓取静帧
		  collapsed:: true
			- ![未命名图片.png](../assets/未命名图片_1668844583132_0.png)
			- ![image.png](../assets/image_1668844595039_0.png)
			- ![image.png](../assets/image_1668844612918_0.png)
		- 将视频中的某段变成静帧
		  collapsed:: true
			- ![image.png](../assets/image_1668844650264_0.png)
		- 静帧调色
		  collapsed:: true
			- ![image.png](../assets/image_1668857922567_0.png)
			- ![image.png](../assets/image_1668858082220_0.png)
			- ![image.png](../assets/image_1668858121592_0.png)
			- ![image.png](../assets/image_1668858136660_0.png)
			-
	-
	- 时间线
	  collapsed:: true
		- 备份你的某个版本的时间线
		  background-color:: blue
		  collapsed:: true
			- ![image.png](../assets/image_1668858289706_0.png)
			- ![image.png](../assets/image_1668858298795_0.png)
			- ![image.png](../assets/image_1668858313141_0.png)
			- ![image.png](../assets/image_1668858323669_0.png)
			- ![image.png](../assets/image_1668858336734_0.png)
	- 入点i,出点o
	  collapsed:: true
		- 删除入点出点, 按  alt + i, alt + o
		- 将入点出点间的片段, 另存为素材
		  background-color:: blue
		  collapsed:: true
			- ![image.png](../assets/image_1668845154380_0.png)
-
- ---
- 选区 & 蒙版
	- 选区
	  collapsed:: true
		- ![image.png](../assets/image_1668862286212_0.png)
		-
	- 矩形蒙版剪裁
	  collapsed:: true
		- ![image.png](../assets/image_1668773655452_0.png)
	-
- 效果
	- 关键帧
	  collapsed:: true
		- ![image.png](../assets/image_1668845518636_0.png)
		- ![image.png](../assets/image_1668845552416_0.png)
		- ![image.png](../assets/image_1668845559887_0.png)
		- ![image.png](../assets/image_1668845571869_0.png)
		- ![image.png](../assets/image_1668845579821_0.png)
		-
	- 把一个片段的效果, 应用到另一个片段上
	  background-color:: blue
	  collapsed:: true
		- ![image.png](../assets/image_1668845642876_0.png)
	- 视频变速, 调速
	  background-color:: blue
	  collapsed:: true
		- 方法 1
		  collapsed:: true
			- ![image.png](../assets/image_1668775446485_0.png)
			- 对片段点右键 -> 更改片段速度
			- ![image.png](../assets/image_1668855955270_0.png)
			-
		- 方法2 : 变速控制
		  collapsed:: true
			- ![image.png](../assets/image_1668856301875_0.png)
			- ![image.png](../assets/image_1668856314240_0.png)
			- ![image.png](../assets/image_1668856326364_0.png)
			- ![image.png](../assets/image_1668856336365_0.png)
			- ![image.png](../assets/image_1668856344398_0.png)
			- ![image.png](../assets/image_1668856352923_0.png)
			- ![image.png](../assets/image_1668856371721_0.png)
			- ![image.png](../assets/image_1668856384427_0.png)
			-
		- 修改帧率
		  collapsed:: true
			- ![image.png](../assets/image_1668856425050_0.png)
			- ![image.png](../assets/image_1668856442563_0.png)
			- ![image.png](../assets/image_1668856463407_0.png)
			-
	- 模糊
	  background-color:: blue
	  collapsed:: true
		- 在调色界面
		- ![image.png](../assets/image_1668775337821_0.png)
		- ![image.png](../assets/image_1668775360480_0.png)
		-
	- 文字蒙版遮罩
	  collapsed:: true
		- 使用 text +
		- ![image.png](../assets/image_1668776287923_0.png)
		- ![image.png](../assets/image_1668776299718_0.png)
		- ![image.png](../assets/image_1668776318432_0.png)
		- ![image.png](../assets/image_1668776334620_0.png)
		-
	- 动态缩放静图
	  collapsed:: true
		- ![image.png](../assets/image_1668845691651_0.png)
		- ![image.png](../assets/image_1668845721958_0.png)
		-
		-
	-
	- 交叉叠化
	  collapsed:: true
		- ![image.png](../assets/image_1668845764943_0.png)
		-
	-
- ---
- 调色
	- 一级调色, 二级调色
	  collapsed:: true
		- 一级调色: 是对画面整体, 进行颜色调整
		- 二级调色: 是对画面的局部, 或特定颜色, 进行调整. 因此, 会经常用到 抠像, 蒙版, 跟踪. 来调画面单独的一块区域
		- ![image.png](../assets/image_1668857173926_0.png)
	- 调色显示开关 -> shift+h
	  collapsed:: true
		- ![image.png](../assets/image_1668856986745_0.png)
		- ![image.png](../assets/image_1668861858552_0.png)
		- ![image.png](../assets/image_1668857118453_0.png)
		- ![image.png](../assets/image_1668857005390_0.png)
		- ![image.png](../assets/image_1668857048144_0.png)
		-
	- 示波器
	  collapsed:: true
		- 示波器 - 波形图
		  collapsed:: true
			- ![image.png](../assets/image_1668857238136_0.png)
			- ![image.png](../assets/image_1668857248960_0.png)
			- ![image.png](../assets/image_1668857274810_0.png)
			- ![image.png](../assets/image_1668857301367_0.png)
			- ![image.png](../assets/image_1668857311580_0.png)
			- ![image.png](../assets/image_1668857331655_0.png)
			- ![image.png](../assets/image_1668857350624_0.png)
			-
		- 示波器 - 矢量图
		  collapsed:: true
			- ![image.png](../assets/image_1668857452734_0.png)
			- ![image.png](../assets/image_1668857470251_0.png)
			- ![image.png](../assets/image_1668857485776_0.png)
			-
			-
	- 白平衡
	  collapsed:: true
		- ![image.png](../assets/image_1668857087325_0.png)
		-
	- 单独调片段的颜色
	  collapsed:: true
		- ![image.png](../assets/image_1668857533264_0.png)
		-
	- 单独调某色
	  collapsed:: true
		- ![image.png](../assets/image_1668855858482_0.png)
		- ![image.png](../assets/image_1668855877437_0.png)
	- 批量对片段进行调色
	-
	- lut颜色查找表
	  collapsed:: true
		- 注意: 套 lut  是调色的起点, 而不是终点. 你需要在 lut 的基础上, 进行进一步的调色.
		  collapsed:: true
			- lut 分两种: 1.矫正lut(能把你的画面, 放到一个合理的调色起始点), 2.风格lut
			- 相机的 log格式, 会保留大量光影信息. 但不同的厂家会, 开发不同的Log曲线. 所以, 你应该在你相机的官网, 下载对应这个log的矫正lut, 在达芬奇中给你的素材套上去. 你的画面, 应该就能被转换成一个正常的画面.
			-
		- lut 的载入, 在 "色彩管理" 中
		  collapsed:: true
		  background-color:: blue
			- ![image.png](../assets/image_1668773045565_0.png)
			- ![image.png](../assets/image_1668845928756_0.png)
			- ![image.png](../assets/image_1668845949173_0.png)
			- ![image.png](../assets/image_1668845958343_0.png)
			- ![image.png](../assets/image_1668846005770_0.png)
			- ![image.png](../assets/image_1668846027780_0.png)
			-
		- 对lut颜色的预览, 换封面
		  collapsed:: true
			- ![image.png](../assets/image_1668846073420_0.png)
		- 降低 lut的颜色浓度
		  background-color:: blue
		  collapsed:: true
			- 选中节点后,
			- ![image.png](../assets/image_1668846477323_0.png)
			-
		- 用了lut后, 发现颜色出现断层
		  collapsed:: true
			- 有时, 套用 lut后, 会发现有的色彩出现断层,  只要在"项目设置 -> 色彩管理"中, 把 3d lut 改成"四面体" ,就能缓解这一问题
			- ![image.png](../assets/image_1668846529300_0.png)
			-
	- 将你不同版本的调色设置, 存储下来
	  background-color:: blue
	  collapsed:: true
		- ![image.png](../assets/image_1668857651549_0.png)
		- ![image.png](../assets/image_1668846992127_0.png)
		- ![image.png](../assets/image_1668847116400_0.png)
		- ![image.png](../assets/image_1668847130138_0.png)
		- ![image.png](../assets/image_1668847003884_0.png)
		- ![image.png](../assets/image_1668857701517_0.png)
		- ![image.png](../assets/image_1668847014440_0.png)
		- ![image.png](../assets/image_1668847038792_0.png)
		- ![image.png](../assets/image_1668847061952_0.png)
		- ![image.png](../assets/image_1668847078151_0.png)
		-
	-
	- 复制一个画面的调色, 到另一个画面
	  background-color:: blue
	  collapsed:: true
		- 方法1:
		  collapsed:: true
			- ![image.png](../assets/image_1668846652749_0.png)
		- 方法2
		  collapsed:: true
			- ![image.png](../assets/image_1668846685487_0.png)
			-
		- 方法3
		  collapsed:: true
			- ![image.png](../assets/image_1668857850276_0.png)
		- 方法4
		  collapsed:: true
			- ![image.png](../assets/image_1668846709964_0.png)
		-
- ---
- 节点
	- 节点简介
	  collapsed:: true
		- 串行节点, 是后面的节点是站在前面节点的效果的基础上, 来做进一步调整的. 只要前面的节点一动, 后面的节点就会全部受影响.
		- 所以当你有大量"串型节点"的时候, 你就很容易引发多米诺骨牌效应. 前面的东西一动, 后面的所有调整都会翻车. 因此, 对于 "二级调色" ,我们需要使用 "并行节点" !
		- ![image.png](../assets/image_1668861890981_0.png)
		- ![image.png](../assets/image_1668861753044_0.png)
		- ![image.png](../assets/image_1668861760935_0.png)
		-
	- 节点快捷键
	  collapsed:: true
		- Alt + p , 添加并行节点
		- Alt + s 添加串行节点
		- ![image.png](../assets/image_1668859235879_0.png)
		-
	- 图层节点 -> alt+L
	  collapsed:: true
		- 还有一个类型叫 "图层节点",  是起什么作用? 它就类似于 ps 里的 图层混合, 可以营造图层叠加效果.
		- ![image.png](../assets/image_1668862096087_0.png)
		- 从媒体池中, 拖入一张炫光图片, 直接到"节点编辑器"中来, 链接到"图层节点"上, 只有就像 ps 中的图层模式叠加一样操作了
		- ![image.png](../assets/image_1668862125753_0.png)
		- ![image.png](../assets/image_1668862159617_0.png)
	- 并行节点, 和"图层混合节点", 可以互相转换 (注意: 图标会变)
	  collapsed:: true
		- ![image.png](../assets/image_1668862482083_0.png)
		- ![image.png](../assets/image_1668862499484_0.png)
		- ![image.png](../assets/image_1668862509104_0.png)
		- ![image.png](../assets/image_1668862557578_0.png)
		- ![image.png](../assets/image_1668862567415_0.png)
		- ![image.png](../assets/image_1668862580457_0.png)
		-
	- 缩放显示节点框架
	  collapsed:: true
		- ![image.png](../assets/image_1668861600428_0.png)
	- 自动理顺多个节点的布局
	  collapsed:: true
		- ![image.png](../assets/image_1668862318269_0.png)
	-
	- 节点间的连线
	  collapsed:: true
		- ![image.png](../assets/image_1668861805949_0.png)
		-
	- 让节点暂时失效 -> ctrl+d
	  background-color:: blue
	  collapsed:: true
		- ![image.png](../assets/image_1668859519873_0.png)
		- 其实就是这个菜单:
		- ![image.png](../assets/image_1668859555917_0.png)
	- 让所有节点, 暂时失效 -> alt+d
	  collapsed:: true
		- ![image.png](../assets/image_1668862193819_0.png)
	- 复合节点
	  collapsed:: true
		- ![image.png](../assets/image_1668859262291_0.png)
		- ![image.png](../assets/image_1668859281505_0.png)
		- ![image.png](../assets/image_1668859299006_0.png)
		- ![image.png](../assets/image_1668859309322_0.png)
	- 重命名节点
	  collapsed:: true
		- ![image.png](../assets/image_1668859408462_0.png)
	-
	- 将一个节点的调色, 复制给另一个节点
	  collapsed:: true
		- ![image.png](../assets/image_1668859447698_0.png)
		- ![image.png](../assets/image_1668859436611_0.png)
	- 将静帧的调色, 复制给某个节点上
	  collapsed:: true
		- ![image.png](../assets/image_1668859499417_0.png)
	- 交换两个节点的调色状态
	  collapsed:: true
		- ![image.png](../assets/image_1668860410425_0.png)
		-
	- 把并行节点的效果, 综合起来
	  collapsed:: true
		- ![image.png](../assets/image_1668861486063_0.png)
		- ![image.png](../assets/image_1668861504154_0.png)
		- ![image.png](../assets/image_1668861510336_0.png)
		- ![image.png](../assets/image_1668861519058_0.png)
		-
	- 重置节点到初始状态
	  collapsed:: true
		- ![image.png](../assets/image_1668859320568_0.png)
		-
- ---
- 片段
	- 片段间不吸附了, 怎么办?
	  collapsed:: true
		- ![image.png](../assets/image_1668773755392_0.png)
		-
	- 复合片段
	  collapsed:: true
		- 对片段右键 -> 新建复合片段
		- ![image.png](../assets/image_1668856228852_0.png)
		- ![image.png](../assets/image_1668856239398_0.png)
	-
-
- ---
- 注释功能
	- 标记
	  collapsed:: true
		- ![image.png](../assets/image_1668845310061_0.png)
		- ![image.png](../assets/image_1668845320138_0.png)
		-
-
- 素材
	- 素材管理
	-
	-
- 配音
	- 音效素材库
	  collapsed:: true
		- ![image.png](../assets/image_1668844789156_0.png)
		-
		-
		-
		-
-
- 输出成品
	- 将每个片段输出成独立的文件
	  collapsed:: true
		- ![image.png](../assets/image_1668846784316_0.png)
	- 无损渲染
	  collapsed:: true
		- 如果你想无损渲染, 可以选下图中的编码
		- ![image.png](../assets/image_1668846819795_0.png)
		-
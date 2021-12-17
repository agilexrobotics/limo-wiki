## 一、LIMO产品简介

### 1.1 产品简介

松灵机器人LIMO是全球首款集四种运动模态于一体的ROS开发平台，提供了适应场景更广泛、更符合行业应用要求的学习平台，适用于机器人教育、功能研发、产品开发。通过创新性的机械设计，能实现四轮差速、阿克曼、履带型、麦克纳姆轮运动模式的快速切换，可在配套的专业沙盘中快速建立多场景实拟教学和测试，LIMO搭载NVIDIA Jeston Nano、EAI XL2激光雷达、深度相机等高性能传感器配置，可实现精确的自主定位、SLAM建图、路线规划和自主避障、自主倒车入库、红绿灯识别等丰富功能。

同时，松灵机器人联合国内ROS社区教学开创者古月居，致力于结合企业用人和行业应用需求，打造基于LIMO开发小车的全新ROS精品课程，助力院校科研教学，让学生达到更高的行业应用技术要求。

### 1.2 产品列表

| 名称                            | 数量                  |
| ------------------------------- | --------------------- |
| LIMO高配版主体（安装越野轮 X4） | X1                    |
| 电池                            | X1                    |
| 充电器                          | X1                    |
| 麦克纳姆轮                      | X4                    |
| 履带                            | x2                    |
| 内六角螺丝刀                    | X1                    |
| 螺丝                            | M3 12mmx20、M3 5mmx20 |

[img](/LIMO_image/product_overview1.png)

[img](/LIMO_image/product_overview_2.png)

### 1.3 性能参数

<table>
	<tr>
		<td>参数类型</td>
		<td>项目</td>
        <td>指标</td>
	</tr>
	<tr>
		<td rowspan="8">机械参数</td>
		<td>外形尺寸</td>
        <td>322*220*251mm</td>
	</tr>
	<tr>
		<td>轴距</td>
        <td>200mm</td>
	</tr>
    	<tr>
		<td>轮距</td>
        <td>175mm</td>
	</tr>
    	<tr>
		<td>自重</td>
        <td>4.8kg</td>
	</tr>
    	<tr>
		<td rowspan="2">负载</td>
            <td>四轮差速（1kg）</td>
            <tr>
				<td>阿克曼模式（4kg）</td>
			</tr>
	</tr>
    	<tr>
		<td>最小离地间隙</td>
            <td>24mm</td>
	</tr>
    	<tr>
		<td>驱动方式</td>
            <td>轮毂电机(4x14.4W)</td>
	</tr>
<tr>
		<td rowspan="4">性能参数</td>
		<td>空载最高车速</td>
        <td>1m/s</td>
	</tr>
<tr>
		<td>阿克曼最小转弯半径</td>
        <td>0.4m</td>
	</tr>
<tr>
		<td>工作环境</td>
        <td>-10~+40℃</td>
	</tr>
<tr>
		<td>最大爬坡角度</td>
        <td>40°（履带模式下）</td>
	</tr>
	<td rowspan="10">系统参数</td>
		<td>电源接口</td>
        <td>DC（5.5x2.1mm)</td>
	</tr>
	<tr>
		<td>系统</td>
        <td>Ubuntu18.0</td>
	</tr>
    	<tr>
		<td>IMU</td>
        <td>MPU6050</td>
	</tr>
    	<tr>
		<td>CPU</td>
        <td>ARM 64位四核@1.43GHz （Cortex-A57）</td>
	</tr>
    	<tr>
	</tr>
    	<tr>
		<td>GPU</td>
        <td>128核 NVIDIA Maxwell @921MHz</td>
	</tr>
    	<tr>
		<td>电池</td>
            <td>5200mAh 12V</td>
	</tr>
    	<tr>
		<td>工作时间</td>
            <td>40min</td>
	</tr>
    	<tr>
		<td>待机时间</td>
            <td>2h</td>
	</tr>
    	<tr>
		<td>通讯接口</td>
            <td>WIFI、蓝牙</td>
	</tr>
	<td rowspan="8">传感器</td>
		<td>激光雷达</td>
        <td>EAI X2L</td>
	</tr>
	<tr>
		<td>深度相机</td>
        <td>奥比中光 DaBai/RealSense D435</td>
	</tr>
    	<tr>
		<td>工控机</td>
        <td>NVIDIA Jetson Nano（4G）</td>
	</tr>
    	<tr>
		<td>语音模块</td>
        <td>讯飞语音助手/谷歌助手</td>
	</tr>
    	<tr>
		<td>扬声器</td>
        <td>左右双声道（2x2W)</td>
	</tr>
    	<tr>
		<td>USB-HUB </td>
            <td>TYPE-C x1、USB2.0 x2</td>
	</tr>
    	<tr>
		<td>前显示器</td>
            <td>1.54寸128x64白色OLED显示屏</td>
	</tr>
    	<tr>
		<td>后显示器</td>
            <td>7寸1024x600 IPS触控屏</td>
	</tr>
	<td rowspan="2">控制参数</td>
		<td>控制模式</td>
        <td>手机APP、指令控制</td>
	</tr>
	<tr>
		<td>手机APP</td>
        <td>蓝牙/极限距离10m</td>
	</tr>
</table>






### 1.4 Nvidia Jetson Nano介绍

Nvidia Jetson Nano 是一款功能强大的小型计算机，专为支持入门级边缘 AI 应用程序和设备而设计。依托完善的 NVIDIA JetPack™ SDK 包含用于深度学习、计算机视觉、图形、多媒体等方面的加速库。搭载在limo高配版本，可以用于拓展机器人导航定位、图像处理、语音识别等技术的拓展。

| GPU      | 128-Core Maxwell                                             |
| -------- | ------------------------------------------------------------ |
| CPU      | Quad-core ARM57 @1.43Ghz                                     |
| 内存     | 4GB 64Bit LPDDR4 25.6GB/s                                    |
| 存储     | Micro SD卡（默认）                                           |
| 视频编码 | 4K@30\| 4 X 1080p@30 \| 9 X 720p@30(H.264/H.265)             |
| 视频解码 | 4K@60\| 2X 4K@30 \| 8X 1080p@30 \| 18 X 720p@30(H.264/H.265) |
| 摄像头   | 2 X MIPI CSI-2 DPHY lanes                                    |
| 联网     | 千兆以太网，M.2 Key E 接口外扩                               |
| 显示     | HDMI X 1, DP X 1                                             |
| USB      | 4 X USB 3.0, USB 2.0 Micro-B                                 |
| 扩展接口 | GPIO，I2C，I2S，SPI，UART                                    |

### 1.5 部件名称

[img](/LIMO_image/车体1-带编号.png)

①　WIFI/蓝牙天线；

②　深度相机；

③　前显示器；

④　EAI X2L激光雷达;

⑤　轮毂电机；

⑥　RGB车灯；

⑦　四轮差速/阿克曼模式切换插销；

⑧　电量显示；

⑨　左扬声器；

⑩　左海鸥门；

[img](/LIMO_image/车体2-带编号.png)

⑪　后显示器；

⑫　电池门；

⑬　开关；

⑭　右海鸥门；

⑮　右扬声器；

[img](LIMO_image/展开1-编号.png)

⑯　USB-HUB模块；

[img](LIMO_image/展开2-编号.png)

⑰　语音模块；

⑱　工控机NVIDIA Jetson Nano（4G）；

⑲　电池；

### 1.6 功能亮点

（1）使用四个轮毂电机，节省车体内部空间，可在一个车体上实现阿克曼、四轮差速、履带和麦轮这四种模态的快速切换；

[img](LIMO_image/四轮毂电机.png)

①阿克曼模式：

一种为了解决交通工具转弯时，内外转向轮路径指向的圆心不同的几何学，依据阿克曼转向几何设计的车辆，沿着弯道转弯时，利用四连杆的相等曲柄使内侧轮的转向角比外侧轮大大约2~4度，使四个轮子路径的圆心大致上交会于后轴的延长线上瞬时转向中心，让车辆可以顺畅的转弯。

[img](LIMO_image/阿克曼模式.png)

②四轮差速模式：

四轮驱动，可实现原地自转，但对轮胎磨损严重，请勿长时间原地自转；

[img](LIMO_image/四轮差速模式.png)

③履带模式：

具有良好的越野性能，可上40°坡和小台阶；

[img](LIMO_image/履带模式.png)

④麦克纳姆轮模式：

基于麦克纳姆轮技术的全方位运动设备可以实现前行、横移、斜行、旋转及其组合等运动方式。

[img](LIMO_image/麦轮模式.png)

（2）车灯状态指示：

两车灯为RGB LED，选用5种对比度高的颜色作为指示灯，其余颜色可供开发者自定义；

| 颜色     | 状态              |
| -------- | ----------------- |
| 红色闪烁 | 低电量/主控报警   |
| 红色常亮 | 程序暂停          |
| 绿色     | 阿克曼模式        |
| 黄色     | 四轮差速/履带模式 |
| 蓝色     | 麦克纳姆轮模式    |

 

（3）两侧车门可展开，预留一个TYPE-C口和两个USB2.0口，方便调试；



[img](LIMO_image/USB-HUB.png)

（4）电池可拆换；

[img](LIMO_image/换电池.png)

（5）预留丰富的拓展孔位：

车顶预留8个M3螺丝孔位，以及两条3.2mm宽的槽口；

[img](LIMO_image/安装孔尺寸-顶视1.png)

两车门预留4个M3螺丝孔位，水平展开获得更大安装平台；

[img](LIMO_image/安装孔尺寸-顶视2.png.png)

车底前后各预留四个M3螺丝孔位；

[img](LIMO_image/安装孔尺寸-底视.png)

（6）丰富的交互体验：

摄像头、激光雷达、语音模块、双扬声器配合前显示器可提供丰富的交互体验。

[img](LIMO_image/车体-前显示器.png)

### 1.7 模态切换方法

（1）切换阿克曼模式：

先将两侧插销拔起，顺时针转30度，使两插销上较长的线指向车体正前方 [](LIMO_image/插销1.png)，即可卡住，车灯变为绿色且常亮时，则切换成功；

[img](LIMO_image/阿克曼-切换1.png)

[img](LIMO_image/阿克曼-切换2.png)

（2）切换四轮差速模式：

  拔起来顺时针转30度，使两插销上较短的线指向车体正前方[](LIMO_image/插销2.png)，此时为插入状态，微调轮胎角度对准孔位让插销插入，车灯变为黄色且常亮时，则切换成功；

[img](LIMO_image/安装孔尺寸-顶视2.png.png)

[img](LIMO_image/安装孔尺寸-顶视2.png.png)

（3）切换履带模式：

在四轮差速模式下将履带直接套上，建议先套空间较小的后轮，并且履带模式下请将两侧车门抬起防止剐蹭；

[img](LIMO_image/履带-切换.png)

（4）切换麦轮模式：

先将轮毂盖和轮胎拆下，只保留轮毂电机，然后保证每个麦轮的小滚子朝向车体中心，用包装里的M3*5螺丝将麦轮安装上，最后需要用遥控/APP调整至麦轮模式。

[img](LIMO_image/麦轮-切换1.png)

[img](LIMO_image/麦轮-切换2.png)

[img](LIMO_image/麦轮角度示意图.png)

**注：切换至麦轮模式的时候，请确保每个麦轮安装的角度如上图所示**

### 1.8 操作说明

（1）长按开关键开机（短按暂停程序），观察电量表，最后一颗红灯量时请及时充电或更换电池；

[img](LIMO_image/开机准备.png)

（2）观察前面插销状态以及车灯颜色判断当前模式：

[img](LIMO_image/模态判断.png)

| 颜色     | 状态              |
| -------- | ----------------- |
| 红色闪烁 | 低电量/主控报警   |
| 红色常亮 | 程序暂停          |
| 绿色     | 阿克曼模式        |
| 黄色     | 四轮差速/履带模式 |
| 蓝色     | 麦克纳姆轮模式    |

（3）遥控器说明

遥控准备：右滑开机键开机，将SWB通道拨到中间即可遥控控制，下方为指令控制，上方关闭控制；

[img](LIMO_image/遥控器-01.png)

差速模式：将SWD通道拨到中下档位为四轮差速模式，左摇杆控制前进后退，右摇杆控制原地左右转；

[img](LIMO_image/遥控器-02.png)

履带模式：与四轮差速模式的运动模型一样；

[img](LIMO_image/遥控器-03.png)

麦轮模式：SWD通道在上档位时为麦克纳姆轮模式，左摇杆控制运动方向，右摇杆控制左右原地转；

[img](LIMO_image遥控器-04.png)

阿克曼模式：在车体上切换为阿克曼模式，开启遥控器控制即可，左摇杆控制前进后退，右摇杆控制左右方向；

[img](LIMO_image/遥控器-05.png)

（4）APP遥控说明

1、 首先在手机上下载我司提供的APP--Nexus，下载方式如下：

IOS端下载：在AppStore搜索Nexus并下载

Android端扫描下面二维码：

[img](/LIMO_image/APP_1.png) 

下载链接：https://www.pgyer.com/lbDi

2、下载App成功后，打开App,如图1-1所示，连接LIMO_xxxxxx的蓝牙；安卓手机点击左上的的蓝牙图标进入蓝牙扫描界面  

[img](/LIMO_image/APP_2.png) 

3、遥控limo

左边控制杆：控制limo前进后退

右边控制杆：控制limo左转右转

中间进度条：速度值显示

模式切换：总共有三种模式，阿克曼运动模式：ackermann，四轮差速运动模式：4wd，麦克纳姆运动模式：mailun

 ackerMann：需要手动将LIMO小车切换阿克曼模式，主要用于校准零点、控制前进后退以及转动角度；

4wd：需要手动将LIMO小车切换四轮差速模式，主要控制前进后退、转换方向以及原地旋转；

Mailun：需要手动将LIMO小车切换麦轮模式，主要控制前进后退、转换方向以及原地旋转

4、APP设置说明

Language switch：通过点击右边的按钮 English/简体，来切换英语和中文

Left-romte min speed：设置LIMO小车的最小速度

Left-romte max speed：设置LIMO小车的最大速度

right-romte min speed：设置LIMO小车的最小旋转速度

right-romte max speed：设置LIMO小车的最大旋转速度

veer calibration：设置零点矫正，先点击+号，然后点击确定Verify，当校准成功会弹出提醒框Successful calibration

BlueTooth：点击弹出蓝牙扫描界面

Bluetooth management：点击random 生成任意以LIMO_xxxx的命名的名字，确认OK并同步修改小车蓝牙的名字，注意此时蓝牙会断开，并会提醒重新连接蓝牙，重新连接蓝牙后可以继续控制小车；当app再次启动，小车的蓝牙名字已经显示修改成功的状态

[img](/LIMO_image/APP_3.png)

[img](/LIMO_image/APP_4.png)



### 1.9 远程桌面连接

#### 1.9.1 下载安装NoMachine

首先在个人电脑下载相应的软件，下载链接：https://www.nomachine.com/download，根据自己电脑的操作系统和架构下载相应的版本。让limo和电脑连接到同一个WIFI下。                         

#### 1.9.2 连接wifi

打开limo右侧的海鸥门，找到USB-HUB模块，给limo连接上键盘鼠标，USB-HUB模块的位置如下图：

<img src="/LIMO_image/USB-HUB.png" style="zoom:70%;" />

键盘鼠标成功连接之后通过以下操作连接wifi，选择需要连接的wifi。

[](/LIMO_image/wifi_1.png)

输入wifi的密码

[](/LIMO_image/wifi_2.png)s



#### 1.9.2 远程连接limo

选择连接对象

[](/LIMO_image/Nomachine.png)

点击Yes

[](/LIMO_image/Nomachine_2.png)

Username：agilex   Password：agx 勾选保存密码

[](/LIMO_image/Nomachine_3.png)

一路选择默认OK

[](./LIMO_image/Nomachine_4.png)
**将归档，已知但不计划解决的问题：**
1. hdmi输出
2. 睡眠唤醒

~*(也不会还有人在用这么老的型号了吧……)*~

---

***序列号那一页清空了，记得用工具生成好再去用***

---

###### 系统信息：

| **硬件** | 	**型号**              |
|--------|----------------------|
| 处理器    | i5-6500              |
| 显卡     | HD530                |
| 硬盘     | WD5000AZLX（西数蓝盘）     |
| 声卡     | Realteck ALC662      |
| 网卡     | RealTeck RTL8168/8111 |
| 主板     | 希腊奶，反正是原装            |
|        | **2024-4-16 迁移系统**   |
| 硬盘     | 致钛PC005              |
|        | **2024-5-5 添加网卡**    |
| 网卡₂    | AX210                |

###### BIOS改动：
更新BIOS（不知道有没有影响）

| 项目 | 位置和改动                                                                           |
|---|---------------------------------------------------------------------------------|
| 更新BIOS | [官网](https://newsupport.lenovo.com.cn/driveList.html?fromsource=driveList&selname=%E5%90%AF%E5%A4%A9M410)|
| | |
| Hyper-Threading | 	超线程，需要关闭。不知道是不是因为换6500不支持超线程的缘故找不到了。                                           |	
| SATA MODE: AHCI| 	Devices > ATA Drive Setup > Configure SATA as: AHCI                            |
| Serial/COM PORT| 	Devices > Serial Port Setup: Disabled                                          |
| VT-x        | dvanced > CPU Setup > Interl(R) Visualization Technology: Enabled               |
| VT-d        | Advanced > CPU Setup > VT-d: Disableld                                          |
| Intel SGX   | Advanced > Interl(R) Software Guard Extensions > Intel(R) SGX Control: Disabled |
| Secure Boot | Security > Secure Boot >Secure Boot: Disabled                                   |
| CSM | Startup > CSM: Disabled                                                         |
| CFG Lock | 使用工具 CFGLock 解锁                                                                 |

###### USB端口号 ( USB2 / USB3 )
> <small>
> 不清楚同型号主板端口号是否一致 </br>
> 因为仅支持15个端口所以F-USB2没测 </br>
> F-USB1的USB3和USB2也没条件测
> </small>
| 位置 | 序号   | 位置 | 序号   |
|----|------|----|------| 
| 前↖ | 4/20 | 前↗ | 3/19 |
| 前↙ | 6/22 | 前↘ | 5/21 |
|    |      | |      |
| 后↖ | 1/17 | 后↗ | 2/18 |
| 后↙ | 8/-  | 后↙ | 9/-  | 
|    |      | |      |
| F-USB1 | -10- | F-USB2 | ?    |



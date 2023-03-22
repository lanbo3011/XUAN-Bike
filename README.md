# XUAN-Bike

![](2.Structure/xuan.jpg)

> 项目视频：[【自制】我把自行车做成了 自 动 驾 驶 ！！【硬核】](https://www.bilibili.com/video/BV1fV411x72a)

## 文件说明

`Hardware`里面是控制器的PCB文件，包括**昇腾A200模组**载板的参考方案。MCU基于ESP32，搭载MPU6050，通过CAN总线连接驱动器。

`Structure`里面是车身结构设计文件，step是Fusion导出的可能有些BUG，建议直接下载这个Fusion360的工程在软件里打开：https://a360.co/2TOtZRd

软件部分由于涉及到FOC驱动器的耦合并不是通用的所以暂时未放出，不过我后面会开源一个包括源码的迷你简化版的自行车完整方案（使用小型直流电机），大家可以等待一阵子。

另外，我正在整理一个机器人嵌入式开发框架（REF），会统一抽象出机器人开发中常用的一些工具和开发模式，到时候也会单独更新一个仓库。

版权来源自gitee：https://gitee.com/CuZn-come-on/XUAN-Bike.git

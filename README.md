# Lenovo_P340_Tiny

本人配置：

OpenCore：0.7.0

macOS Big Sur 11.4 (20F71)

SystemProductName：iMac20,2

使用时需手动加入三码

CPU:i9-10900

内存：32GB 2666

SSD:760p 256GB970&EVO Plus 2TB

核显：UHD630

无线网卡：intel AX201

内置了启动音频及图形界面。

可能感觉使用P340 Tiny跑黑苹果的人不多吧，加上用了另一位网友的EFI在我的机器上无法安装完成。
自己之前从未了解过OpenCore，于是从零开始找教程摸索配置EFI，收获还是有的，目前还在不断完善中
供网友参考，如果问题还希望一起研究。

目前能实现了核显板载的HDMI及DP（DP原生就支持）的音视频输出。
未完成问题：AX201蓝牙设备在P340tiny上不识别，无法正常使用，看了下好像是USB控制器的ID不在作者支持范围内

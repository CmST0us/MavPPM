# MavPPM
MavPPM 主工程。MavPPM 是一个使用移动设备作为航模遥控器的系统。

请使用

```
git submodule init
git submodule update --init --recursive
```

初始化

冒烟测试通过，此节点后，master分支每次commit必须为release版本

# 系统组件

* MavPPM-EMB-PPM 嵌入式系统 PPM信号生成层
* MavPPM-EMB-CommLayer 嵌入式系统 通信层
* MavPPM-EMB-APP 嵌入式系统 APP
* MavPPM-iOS-CommLayer iOS APP 通信层
* MavPPM-iOS-APP iOS APP
* MavPPM-iOS-GravityControlLogic iOS APP 重力感应控制逻辑层
* MavPPM-mavlink MavPPM 工程使用的mavlink协议 包含C库和Objective-C framework
* Vendor 使用到的第三方库

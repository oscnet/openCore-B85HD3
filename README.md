
## B85-HD3 主板的  openCore 配置

## 配置情况：

* LGA 1150
* 采用Intel B85芯片组
* 集成Realtek ALC892 8声道音效芯片纠错
* 4×SATA III接口，2×SATA II接口
* 4×USB3.0接口（2内置+2背板），8×USB2.0接口（4内置+4背板）纠错
* 显卡 AMD Radeon RX 580


## 2019.11.26  完成硬解  

关闭了核显，机型设为 iMacPro1,1  加入 [AGPMInjector.kext](https://github.com/Pavo-IM/AGPMInjector)
这两个缺一不可，否则都不可能实现硬解

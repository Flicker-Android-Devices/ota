日志/Changelog: [https://github.com/Flicker-Android-Devices/ota/blob/fifteen/updater/changelogs/thyme.md](https://github.com/Flicker-Android-Devices/ota/blob/fifteen/updater/changelogs/thyme.md)  

固件要求：HyperOS V1.0.4.0  

ROM：  
同步源码(20250203)  
新增背部轻敲手势  
新增应用音量调节  
新增侧边栏/小窗模式  
其他细节：[https://github.com/PixelOS-AOSP](https://github.com/PixelOS-AOSP)  
设备：  
dts：从Thyme HyperOS V1.0.4.0版本更新保留内存节点的地址和大小  
内核：合并上游los qcom sm8250内核的更新，Linux 4.19.325  
修复使用MIPPS充电器时无法显示快充的问题（目前逻辑：使用原装充电器显示快充，其他显示慢充）  
使用符合中国运营商标准的NR 5G信号显示阈值  
增加自动高亮度模式  
重做防闪烁模式UI  
调整状态栏布局，修复AOD动画位置不正确的问题 @KaguraRinko  
添加杜比音效  
调度优化  
调整杜比音效配置  
优化低亮度时自动亮度的抖动  
调整wifi band优先级和阈值  
新增颜色高级设置（参考官方色彩管理高级模式自定义）  
重做色彩管理，加载正确的颜色配置（与官方一致）  
重新设计屏幕挖孔overlay  
移除不存在的启动项  
修复toucheventcheck服务未正常启动的问题  
调整音量步骤到30  
重做小米支付环境hal sepolicy  
导入Qti网络定位提供商  
开启ZRAM dedup  
使用Full Lto编译内核  
修复pcc变化时屏幕亮度变化：  
- 修复开启dc/hbm时无法使用livedisplay、护眼模式的问题  
- 修复开启dc时旋转屏幕亮度变化的问题  
- 修复小窗模式全屏亮度变化的问题  

移除webcam  
添加小米app  
其他调整..  

日志/Changelog: [https://github.com/Flicker-Android-Devices/ota/blob/fifteen/updater/changelogs/psyche.md](https://github.com/Flicker-Android-Devices/ota/blob/fifteen/updater/changelogs/psyche.md)

20250218 Mi12X PixelOS 15 QPR1 February

日志(Changelog):
ROM：
- 同步最新源码(20250218)  
  Sync latest source code(20250218)
- 更新二月安全补丁  
  Update the February security patch
- 更多汉化  
  More language translations
- 移除侧边栏/小窗模式(PixelOS官方未加入该功能，我不再单独维护)  
  Remove sidebar/window mode (Officially not included in PixelOS, I will no longer maintain this feature separately).
- 更新中国电信澳门(CTMO)的APN  
  Update the APN for China Telecom Macau (CTMO)  
- 其他细节：  
  Other details:   
  https://github.com/PixelOS-AOSP / https://blog.pixelos.net/blog/

设备(Device):
- 移除酷控APP  
  Remove the Kukoo app
- 切换至AIDL Boot Control HAL  
  Switch to AIDL Boot Control HAL
- 从K40S OS1.0.8.0.ULMMIXM升级通用Blobs  
  Upgrade to Common Blobs from K40S OS1.0.8.0.ULMMIXM
- 使用最新的cgroups.json  
  Use the latest cgroups.json
- 正确配置Zram dedup  
  Configure Zram dedup correctly
- 调整模糊半径  
  Adjust blur radius
- 调整task_profiles  
  Adjust task_profiles
- 新增手电筒亮度调节  
  Add flashlight brightness adjustment
- 开启DC调光时将屏幕切换到60Hz  
  Switch the screen to 60Hz when DC dimming is enabled
- 其他调整  
  Other optimizations

内核(Kernel)：
- 新增MGLRU (Multi-Gen LRU)，改善内存管理性能  
  Added MGLRU (Multi-Gen LRU) to improve memory management performance
- 删除不需要的内核模块  
  Remove unnecessary kernel modules

注意(Notice):
小米12X(Xiaomi 12X):
- 小米12X固件要求：中国大陆版本：HyperOS CN V1.0.10.0 | 国际版本 HyperOS GL V1.0.8.0  
  Xiaomi 12X Firmware Requirements: Mainland China: HyperOS CN V1.0.10.0 | Global: HyperOS GL V1.0.8.0

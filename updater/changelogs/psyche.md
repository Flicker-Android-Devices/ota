20250614 Mi12X PixelOS 15 QPR2 June  

日志(Changelog):
ROM：
- 同步最新源码(20250612)  
  Sync latest source code(20250612)
- 其他细节 / Other details:   
  https://github.com/PixelOS-AOSP / https://blog.pixelos.net/blog/

设备(Device):
- BL锁状态隐藏 / Play integrity strong认证  
  BL lock status hidden / Play integrity strong certification
- 修复MIUI相机EIS  
  Fix MiuiCamera EIS
- 内存管理调整  
  Memory management adjustments
- 切换至AIDL红外遥控HAl  
  switch to common AIDL IR service
- 系统调度调整  
  System scheduling adjustment
- 优化屏上指纹解锁性能  
  udfps: Use unique_fd and atomic<bool> for thread safety
- 使用实现完整的ART优化  
  Enable full ART optimizations with VDEX/ODEX
- 添加google play认证overlay在线更新功能  
  Add an ability to update certified props from server
- 将默认zram压缩算法调整为lzo-rle  
  Set zram default compression algorithm to lzo-rle
- 调整LMK阈值  Add commentMore actions
  Increase LMK threshold
- zram wb大小调整到1G  
  change backing device size to 1G
- 其他调整...  
  Other optimizations...

内核(Kernel)：
- 合并上游更新  
  Merge upstream updates
- 修复电量0%时无法关机的问题  
  Fixed the issue that the battery could not be turned off when the battery was 0%.
- 从Linux 5.10反向移植MG-LRU补丁  
  Backport MG-LRU patches from Linux 5.10
- 从Linux 5.10反向移植lzo-rle并设置为默认zram后端  
  Backport lzo-rle from Linux 5.10 and set as the default zram backend
- 移除zram dedup  
  Drop zram dedup

注意(Notice):
小米12X(Xiaomi 12X):
- 小米12X固件要求：中国大陆版本：HyperOS CN V1.0.10.0 | 国际版本 HyperOS GL V1.0.8.0  
  Xiaomi 12X Firmware Requirements: Mainland China: HyperOS CN V1.0.10.0 | Global: HyperOS GL V1.0.8.0

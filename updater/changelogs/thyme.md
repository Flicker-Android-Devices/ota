20250517 Mi10S PixelOS 15 QPR2 April  

日志(Changelog):
ROM：
- 同步最新源码(20250510)  
  Sync latest source code(20250510)
- 其他细节 / Other details:   
  https://github.com/PixelOS-AOSP / https://blog.pixelos.net/blog/

设备(Device):
- 添加google play认证overlay在线更新功能  
  Add an ability to update certified props from server
- 将默认zram压缩算法调整为lzo-rle  
  Set zram default compression algorithm to lzo-rle
- 调整LMK阈值  
  Increase LMK threshold
- zram wb大小调整到1G  
  change backing device size to 1G
- 修复Miui相机ai功能  
  fix ai camera
- 调度调整  
  Decrease powerhint launch boost to 3sec
- 其他调整...  
  Other optimizations...

内核(Kernel)：
- 合并上游更新  
  Merge upstream updates
- 从Linux 5.10反向移植MG-LRU补丁  
  Backport MG-LRU patches from Linux 5.10
- 从Linux 5.10反向移植lzo-rle并设置为默认zram后端  
  Backport lzo-rle from Linux 5.10 and set as the default zram backend
- 移除zram dedup  
  Drop zram dedup

注意(Notice):  
- 如果你需要小米相册，可自行下载安装  
  https://www.pling.com/p/2208495/  
  If you need Xiaomi Gallery, you can download and install it yourself.  
  https://www.pling.com/p/2208495/

小米10S(Xiaomi 10S):
- 小米10S固件要求：HyperOS V1.0.4.0  
  Xiaomi 10S Firmware Requirements: HyperOS V1.0.4.0
- 1.从20250118版本更新时需要更新底包至HyperOS V1.0.4.0  
    When updating from 20250118, it is necessary to update fw to HyperOS V1.0.4.0
- 2.从首个稳定版本（20241229）更新时需要使用自带rec双清  
    When updating from the first stable version (20241229), 
    it is necessary to wipe data using the built-in recovery.

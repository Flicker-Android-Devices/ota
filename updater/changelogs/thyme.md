日志 / Changelog: [https://github.com/Flicker-Android-Devices/ota/blob/fifteen/updater/changelogs/thyme.md](https://github.com/Flicker-Android-Devices/ota/blob/fifteen/updater/changelogs/thyme.md)  

20250430 Mi10S PixelOS 15 QPR2 April  

- 警告！从老版本更新后需要在设置中清除 ‘高级设置（org.lineageos.settings）’的数据，并立即重启一次  
  Warning! After updating from an old version, you need to clear the data of 'Advanced Settings (org.lineageos.settings)' in the settings and restart immediately.  
- 警告！从老版本更新后需要在设置中清除 ‘高级设置（org.lineageos.settings）’的数据，并立即重启一次  
  Warning! After updating from an old version, you need to clear the data of 'Advanced Settings (org.lineageos.settings)' in the settings and restart immediately.  
- 警告！从老版本更新后需要在设置中清除 ‘高级设置（org.lineageos.settings）’的数据，并立即重启一次  
  Warning! After updating from an old version, you need to clear the data of 'Advanced Settings (org.lineageos.settings)' in the settings and restart immediately.  

日志(Changelog):
ROM：
- 同步最新源码(20250429)  
  Sync latest source code(20250429)
- 更新4月安全补丁  
  Update the April security patch
- 其他细节 / Other details:   
  https://github.com/PixelOS-AOSP / https://blog.pixelos.net/blog/

设备(Device):
- 允许前台应用在CPU 0-6上运行  
  Allow foreground tasks to run on CPU 0-6
- 关闭应用子进程数量限制（修复termux 使用proot时闪退）  
  Properly disable phantom process killing
- 添加'性能'温控配置  
  Add performance thermal config
- 为常用应用/游戏配置默认的温控模式  
  Configure default thermal config for frequently apps/games
- 使用小米官方HBM方法  
  Switch to disp_param
- 允许后台应用在CPU 0-4上运行  
  Allow background tasks to run on CPU 0-3
- 使用3/4/5G选项调整移动网络模式  
  Disable CDMA and world phone bools
- 压缩多任务预览图以节省内存  
  Set reduced config_highResTaskSnapshotScale
- 更新小米应用  
  Update MiApps from houji OS2.0.6.0.VNCMIXM
- 为中文用户添加百度网络定位  
  Add Baidu network location support for China region
- 修复蓝牙硬件卸载  
  Support BT A2DP hardware offload for legacy bt decoders
- 添加Miui相机  
  Add MiuiCamera
- 添加隐藏屏幕挖孔功能（位于开发者选项）  
  Add hide cutout emulations
- 将GPU驱动升级至530.55版本  
  Update Adreno Driver to 530.55
- 从K40S OS1.0.9.0.ULMMIXM更新通用blobs  
  Update blobs to munch OS1.0.9.0.ULMMIXM
- 修复充电控制  
  Fix charge control
- 修复关机闹钟  
  Fix poweroff alarm
- 其他调整...  
  Other optimizations...

内核(Kernel)：
- 合并上游更新  
  Merge upstream updates

注意 / Notice:  
- 如果你需要小米相册，可自行下载安装  
  https://www.pling.com/p/2208495/  
  If you need Xiaomi Gallery, you can download and install it yourself.  
  https://www.pling.com/p/2208495/

小米10S / Xiaomi 10S:
- 小米10S固件要求：HyperOS V1.0.4.0  
  Xiaomi 10S Firmware Requirements: HyperOS V1.0.4.0
- 1.从20250118版本更新时需要更新底包至HyperOS V1.0.4.0  
    When updating from 20250118, it is necessary to update fw to HyperOS V1.0.4.0
- 2.从首个稳定版本（20241229）更新时需要使用自带rec双清  
    When updating from the first stable version (20241229), 
    it is necessary to wipe data using the built-in recovery.

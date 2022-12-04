# DELL-7050-MFF-Hackintosh(黑苹果)


### OC 0.8.6

配置:i5-6400,网卡ax200  
HDMI,Wi-Fi,声音正常  
睡眠后虽然可以唤醒，但是显示器无反应

其他不清楚

bios设置:https://github.com/linkev/Dell-Optiplex-7050-Micro-Hackintosh/blob/master/BIOS.md

2021.08.15         

0.7.0>>>0.7.2（Catalina）

Misc--security--SecureBootModel--j137

UEFI--APFS--MinVersion--无限制 or Catalina

(  MinDate   -1                  MinVersion    -1               

   or

   MinDate    20200306     MinVersion    1412101001000000   )

2021.08.16 更新：

升级Big Sur（11.5.2），Wi-Fi的kexts文件更换为Big Sur专用版本

2022.03.13 更新:

修改layout-id为12(可使用麦克风）

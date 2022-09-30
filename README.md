 # J9110 的TWRP设备树（本项目仅供参考）
 
# 说明

**本项目暂缓更新，如需使用，请前往xda获取另一个twrp的更新，直达链接 ==>>**
**<a href="https://forum.xda-developers.com/t/twrp-r-unofficial-xperia-1-based-on-android-11.4495643/">https://forum.xda-developers.com/t/twrp-r-unofficial-xperia-1-based-on-android-11.4495643/</a>**


已在twrp12.1分支上编译,并经过真机运行。

但是功能并不完全，因此**该仓库的内容仅供参考**

**已修复：**

- 触摸

**尚存在的问题：**

- 因为内核过大，因此加入解密功能后，编译出来的boot文件可能会过大( > 64 MB )，因此也移除了对中文的支持
- 文件解密
- 分区（想先看一下怎么修复解密，就暂时没完善分区表）
- 槽位切换（bootctrl模块引入有点问题）

其他未知...

# 解密问题
 
在一番尝试后，暂时不知道如何修复twrp的解密问题，项目采用的是twrp12.1分支进行编译
1,使用的是Evo X ，解密userdata时查看logcat日志会抛出异常
2.使用PixelExperience的GSI时，提示用户使用默认解密，但是解密失败。

因为不太理解FBE的解密流程，因此暂时没办法修复。（看XDA那个新出twrp的能不能修好了）


如果感兴趣可以一起讨论。
QQ：1712865977 @eswd

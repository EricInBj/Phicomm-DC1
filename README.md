# Phicomm-DC1
Phicomm DC1 plugin for Domoticz

将Phicomm-DC1 目录放置在 Domoticz 的 Plugins目录下，在 Domoticz 中添加硬件

可以配置状态更新间隔，以及插座的名字，格式为 {'45':'fish','46':'cat'}， 45，46 为DC1的IP地址最后一段，fish cat则为显示名字。

可以不配置显示名，这样会直接用 IP 地址最后一段作为名字。

每一个 DC1 会创建出5个设备：一个总开关、三个孔位对应的开关、一个电压设备。



#感谢

参考了 Zack 大神的 M1 插件, 以及 MP1 插件
https://github.com/promisezackr/Phicomm-M1-Domoticz-Plugin

参考了 Hass 社区里的大神们的插件
https://bbs.hassbian.com/thread-4773-1-1.html


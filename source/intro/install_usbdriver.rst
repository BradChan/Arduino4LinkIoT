.. _install_usbdriver:

=====================
安装USB驱动
=====================

当我们安装和配置Arduino IDE之后，还有一项非常重要的工作：安装USB2Serial桥接芯片——CP2014的驱动程序。如果我们的电脑OS比较新，譬如你使用Windows10、Mac OS X 10.8之后的版本，自然支持LinkIoT的USB桥接芯片，就可以跳过这一步。

LinkIoT板上使用SilCon Labs公司的USB2Serial桥接芯片(CP2104)实现用户程序下载、串口监视器等功能，如果我们的电脑OS比较陈旧，必须安装这个USB接口的Driver。

下载CP2104的Driver
=====================

打开Silcon labs公司官网下载或直接点击下面的下载链接页面，在页面中选择与自己电脑OS匹配的Driver程序

https://cn.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers

Windows系统中安装LinkIoT的USB驱动
=====================

<> 请参考Silcon labs的安装向导文档
大多数Win7、Win10电脑系统都支持LinkIoT。

macOS系统中安装LinkIoT的USB驱动
=====================

<> 请参考Silcon labs的安装向导文档。
大多数Mac OS X电脑系统都支持LinkIoT。

Linux系统中安装LinkIoT的USB驱动
=====================

<> 请参考Silcon labs的安装向导文档

验证安装是否成功
=====================

当你使用USB数据线(不要被USB电源线误导，不是所有USB线都是数据线)将LinkIoT与电脑链接时，你的电脑都会多出一个Com端口，说明Driver安装成功，否则请根据Silcon labs官方向导排查安装问题。



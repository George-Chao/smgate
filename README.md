使用方法，路由器局域网ip设置为192.168.99.1，关闭路由器LAN口的dhcp功能。将设置好的树莓派用网线连接路由器上去。即可。

特别注意：连接到此路由器的设备网络连接属性设置必须为自动获取DNS，网关，和IP地址

使用效果，树莓派与路由器组成透明翻墙网关，只要是连接到这个路由中的设备，自动翻墙，无需再安装设置翻墙软件。本例所配置的json为白名单。
使用v2ray自带的国内IP列表与国内常用网站domain列表。列表中的网站与IP直连。不在列表中的走代理网络。DNS使用v2ray内置查询，国内外网站自动分流。

---------------------安装步骤--------------------------------

https://github.com/MassSmith/smgate/wiki

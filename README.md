
文件打开器
此插件将使用其默认应用程序在设备文件系统上打开文件。

官方地址：https://github.com/pwlin/cordova-plugin-file-opener2
版本：2.0.19
官方地址上的插件在跑Android的项目会报错，主要原因是插件支持最新版本，解决办法把plugin.xml中对插件的支持配置修改：<framework src="com.android.support:support-v4:27.1.0" />
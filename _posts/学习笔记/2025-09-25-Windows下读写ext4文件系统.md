---
layout: post
comments: true
categories: 学习笔记
---

Ext2Fsd 是由国人发起的开源项目。

其官方主页为http://www.ext2fsd.com/。

项目下载地址为http://sourceforge.net/projects/ext2fsd/。

该工具的基础使用方法如下：

* 完成安装后启动 Ext2Mgr，右键选中需要进行读写操作的分区，选择【加载装配点盘符】，操作完成后，即可通过系统自带的资源管理器对该分区的文件进行访问和修改，文件的读写速度基本与 NTFS 分区持平。

* 文件修改操作完成后，为避免误操作，可右键该分区选择 “更改装配点盘符”，删除已分配的盘符，此时资源管理器将不再显示该分区；若未执行卸载操作，重启系统可能出现异常问题。

* 若需对驱动进行相关设置，可在软件菜单中选择 “工具与设置”>“配置文件系统驱动”，进入对应界面进行调整。

* 其官方主页最新版本为 0.69，开源代码可在 Github 地址https://github.com/matt-wu/Ext3Fsd 查看；

* 针对 Windows 11 系统的后续适配与功能更新工作，由开发者 Bo Branten（bobranten）负责维护，相关代码托管在 GitHub 仓库https://github.com/bobranten/Ext4Fsd，该项目当前最新版本为 0.71。


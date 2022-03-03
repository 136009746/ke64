# ke64 0.2.0.0



### 免责声明:
这只是一个免费的辅助软件, 如果您使用本软件, 给您直接或者间接造成损失、损害, 本人概不负责. 从您使用本软件的一刻起, 将视为您已经接受了本免责声明.

本软件仅限于学习交流，如侵权请在24小时进行删除.

### 简介

ke64是一个免费但功能强大的内核研究工具。它支持从Windows 7(7601)到Windows 11(22000)，仅支持x64位系统，请在虚拟机运行。

### 问题反馈&帮助
* qq群：822257392
* 163：alinml@163.com
* google：ke64ml@gmail.com
* gitee：[gitee](https://gitee.com/alinml/ke64)

#### 签名
由于我没有数字证书，使用泄漏的数字证书来签署ke64的驱动程序。使用泄漏数字证书防病毒软件都认为文件是恶意软件,请大家放心使用


# 功能列表
1. 进程,线程,模块,窗口,内存,定时器,热键,(等显示 隐藏，欺骗，杀进程,杀线程，卸载，移除)
2. 用户钩子(消息钩子,事件钩子，inline,iat,eat,hook检测,(程序入口反汇编和汇编(双击汇编)))
3. 驱动模块(卸载等操作)
4. FilterDriver(File,Disk,RAW,Volume,Keyboard,Mouse,I8042prt，Tdx,NDIS,PnpManager)(移除等操作)
5. CreateProcess,LoadImage,CreateThread,CmpCallback,Shutdown(移除等操作)
6. Callbak,ObjectType,ObjectTypeHook,DPC,WFPCallout,minifilter,WorkerThread(堆栈回溯)(移除等操作)
7. IRP(Keyboard,Mouse,I8042prt,ndis,nsiproxy,tcpip,partmgr,disk,ntfs,scsi,npfs,fltmgr)
8. GDI,IDT
9. 端口查看
10. 启动项(删除等操作)
11. 服务
12. 文件管理(删除等操作)
13. 应用层和驱动层(支持反汇编和汇编内存)
14. 功能(...)

# Screenshots
仅在该页面上放置了一张图片。
![image](https://github.com/alinml/ke64/blob/main/screenshots/process(hook).jpg)

# 待加入功能
1. 行为监控功能(行为大类:文件，注册表，进程线程，模块，网络)等行为监控。
2. 注册表管理
3. 驱动页面菜单导入导出功能。
4. 文件页面菜单几个功能。
5. ~~支持英语(English)语言。~~
## 特别感谢
*弃

## 感谢名单
bbjj999,Hmily


## 更新日志 0.2.0.0

1. 修复消息和事件钩子某些情况下会有失败情况
2. 界面调整支持DPI
3. 修复文件页卡住
4. 支持English语言(自动适配在不是中文语言系统程序设置English语言)
5. 修复多个问题

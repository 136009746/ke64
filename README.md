# ke64 0.1.0.0

免责声明:
这只是一个免费的辅助软件, 如果您使用本软件, 给您直接或者间接造成损失、损害, 本人概不负责. 从您使用本软件的一刻起, 将视为您已经接受了本免责声明.

本软件仅限于学习交流，如侵权请在24小时进行删除.

###  实现一个端口隐藏DEMO（文件port.sys）支持win7-win11,可过ark工具检查，本DEMO没有严禁测试可能不稳定仅测试，是否触发pg短时间我也没测出来，单独一个驱动使用工具加载即可使用工具查看端口,默认只隐藏pid为4的tcp&udp端口,请在虚拟机运行测试，此驱动没有添加卸载，我随时可能就删除测试程序，不要问报毒问题不解释，一切责任概不负责。

### 驱动页面菜单导入导出功能暂未添加，文件页面菜单几个功能暂未添加，下个版本在加，偷个懒

#### 后面会加入行为监控功能(测试中)(行为大类:文件，注册表，进程线程，模块，网络)等行为监控。

ke64是一个免费但功能强大的内核研究工具。它支持从Windows 7(7601)到Windows 11(22000)，仅支持x64位系统，请在虚拟机运行。

签名：
我没有数字证书，使用泄漏的数字证书来签署ke64的驱动程序。使用泄漏数字证书防病毒软件都认为文件是恶意软件,请大家放心使用

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
![image](https://github.com/alinml/ke64/blob/main/screenshots/2.jpg)

## 感谢名单
bbjj999,Hmily

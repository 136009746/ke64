# ke64 0.2.0.0

[简体中文](https://github.com/alinml/ke64/blob/main/README_Chinese.md)


### Question feedback & help
* qq group：822257392
* 163：alinml@163.com
* google：ke64ml@gmail.com
* gitee：[gitee](https://gitee.com/alinml/ke64)

Disclaimer:
This is just a free auxiliary software. If you use this software, you are not responsible for any loss or damage caused directly or indirectly. From the moment you use this software, you will be deemed to have accepted this disclaimer.

This software is only for learning and communication, if infringement, please delete it within 24 hours.

ke64 is a free but powerful kernel research tool. It supports from Windows 7 (7601) to Windows 11 (22000), only supports x64-bit systems, please run in a virtual machine。

#### sign
Since I don't have a digital certificate, I use a leaked digital certificate to sign the ke64 driver. Antivirus software that uses leaked digital certificates thinks that the file is malicious software, please rest assured to use


# function list
1. Process, thread, module, window, memory, timer, hot key, (show, hide, cheat, kill process, kill thread, uninstall, remove)
2. User hooks (message hooks, event hooks, inline, iat, eat, hook detection, (program entry disassembly and assembly (double-click assembly)))
3. Drive module (unloading and other operations)
4. FilterDriver(File,Disk,RAW,Volume,Keyboard,Mouse,I8042prt，Tdx,NDIS,PnpManager)(Remove and other operations)
5. CreateProcess,LoadImage,CreateThread,CmpCallback,Shutdown(Remove and other operations)
6. Callbak,ObjectType,ObjectTypeHook,DPC,WFPCallout,minifilter,WorkerThread(Stack traceback)(Remove and other operations)
7. IRP(Keyboard,Mouse,I8042prt,ndis,nsiproxy,tcpip,partmgr,disk,ntfs,scsi,npfs,fltmgr)
8. GDI,IDT
9. Network
10. Startup item (delete, etc.)
11. Serve
12. File management (delete and other operations)
13. Application layer and driver layer (support disassembly and assembly memory)
14. Features(...)

# Screenshots
Only one image is placed on this page。
![image](https://github.com/alinml/ke64/blob/main/screenshots/process(hook)_en.jpg)

# Features to be added
1. Behavior monitoring function (file, registry, process thread, module, network) and other behavior monitoring。
2. Registry management
3. Drive page menu import and export function。
4. Several functions of the file page menu。
5. ~~Support(English)language。~~
## Special thanks to
*弃

## Thanks list
bbjj999,Hmily


## Update log 0.2.0.0
1. Fixed message and event hooks failing in some cases
2. Interface adjustment support DPI
3. Fix file page stuck
4. Support English language (automatic adaptation is not Chinese language system program to set English language)
5. Fix multiple issues

# ke64 2.0.0.0

[简体中文](https://github.com/alinml/ke64/blob/main/README_Chinese.md)

### Disclaimer:
This is just a free auxiliary software. If you use this software, you are not responsible for any loss or damage caused directly or indirectly. From the moment you use this software, you will be deemed to have accepted this disclaimer.

This software is not allowed to be used for commercial purposes without the written authorization of the author; It is prohibited to use this software to break the computer system or software environment, etc.

This software is only for learning and communication, if infringement, please delete it within 24 hours.

### Introduction

ke64 is a free but powerful kernel research tool. It supports from Windows 7 (7601) to Windows 11 (22000), only supports x64-bit systems, please run in a virtual machine。

### Question feedback & help
* qq group：822257392
* 163：alinml@163.com
* google：ke64ml@gmail.com
* gitee：[gitee](https://gitee.com/alinml/ke64)

### Sign
Since I don't have a digital certificate, I use a leaked digital certificate to sign the ke64 driver. Antivirus software that uses leaked digital certificates thinks that the file is malicious software, please rest assured to use


### Characteristics
1. Process, thread, module, window, memory, timer, hotkey, (etc. show hide, cheat, kill process, kill thread, unload, remove)
2. User hook (message hook, event hook, inline, iat, eat, hook detection)
3. Drive module (unloading and other operations)
4. FilterDriver (File, Disk, RAW, Volume, Keyboard, Mouse, I8042prt, Tdx, NDIS, PnpManager) (removal and other operations)
5. CreateProcess, LoadImage, CreateThread, CmpCallback, Shutdown
6. Callback, ObjectType, ObjectTypeHook, DPC, WFP Callout, minifilter, WorkerThread (stack backtracking) (remove and other operations)
7. IRP(Keyboard,Mouse,I8042prt,ndis,nsiproxy,tcpip,partmgr,disk,ntfs,scsi,npfs,fltmgr)
8. GDI,IDT
9. Port View
10. Startup item (delete and other operations)
11. Service (start, stop, temporary, restore, restart, delete, start type, locate registry, attribute)
12. Registry management (delete, rename, export, create (key, binary, DWORD, QWORD, multiple strings, extensible strings), modify (DWORD, QWORD, multiple strings))
13. File management (delete, quickly locate files, lock, rename, copy files, remove read-only hidden attributes, set read-only hidden attributes, attributes)
14. Add behavior monitoring (behavior includes:
File (create, read, write, delete, rename, set attributes, set permissions),
Registry (open, create, delete key, delete value, read value, rename key, set security, query value, set value),
Processes (create, start, destroy),
Thread (create, destroy),
Module (loaded),
Network (connect, listen, receive, send)
）Etc.
15. Application layer and driver layer (support disassembly and assembly memory)
16. Function (...)

### Screenshots
Only one image is placed on this page。
![image](https://github.com/alinml/ke64/blob/main/screenshots/mon.png)

### Features to be added
1. ~~Behavior monitoring function (file, registry, process thread, module, network) and other behavior monitoring。~~
2. ~~Registry management~~
3. ~~Drive page menu import and export function。~~
4. ~~Several functions of the file page menu。~~
5. ~~Support(English)language。~~
### Special thanks to
*弃

### Thanks list
bbjj999,Hmily

### Update log 

2.0.0.0
1. Add behavior monitoring (behavior includes:
File (create, read, write, delete, rename, set attributes, set permissions),
Registry (open, create, delete key, delete value, read value, rename key, set security, query value, set value),
Processes (create, start, destroy),
Thread (create, destroy),
Module (loaded),
Network (connect, listen, receive, send)
）Etc.
2. Add End Delete Process
3. Enhanced file deletion (blue screen for slow response)
4. Add deletion of files occupied by hidden processes
5. Add process protection
6. New process hidden (later versions are enabled)
7. Add process camouflage (later versions are enabled)
8. Add PlugPlay callback enumeration
9. Add memory scanning Ldr driver module
10. Enter the new file location input field
11. Violent deletion of new files (handle occupation, irp occupation, hard links, etc. can be ignored...)
12. Rewrite the file handle view, including hiding the lower layer (solving the slow response blue screen)
13. Right click the modified file tree list and select
14. Deleting files in the repair list will not clean up the display
15. Repair file transferred to
16. Modify the list color a little darker
17. Fix known bugs
18. Optimize some functions

1.0.3.0
1. New support for (win11 22H2) 22621 and (win2022) 20348
2. Add registry management (delete, rename, export, create (key, binary, DWORD, QWORD, multi string, extensible string), modify (DWORD, QWORD, multi string))
3. Improve file functions (fast file positioning, file locking, renaming, copying files, removing read-only hidden attributes, setting read-only hidden attributes, attributes),
4. Improve service functions (start, stop, temporary, restore, restart, delete, start type, locate registry, attribute)
5. Add some menus and go to the ke64 registry and file
6. Repairing multiple bugs will not be described here
7. Enhanced startup item deletion
8. Strengthen stability

0.2.1.0
1. Fix the scanning process hook segment is too large to cause too slow (like a stuck phenomenon)
2. Remove process menu entry disassembly function
3. Fix multiple bugs and blue screen of some functions
4. enhance stability

0.2.0.0
1. Fixed message and event hooks failing in some cases
2. Interface adjustment support DPI
3. Fix file page stuck
4. Support English language (automatic adaptation is not Chinese language system program to set English language)
5. Fix multiple issues

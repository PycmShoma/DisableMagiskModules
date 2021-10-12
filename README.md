# RemoveLastMagiskModule
TWRP script for uninstalling the last installed Magisk module

## Description
This is a script for installation via TWRP Recovery. If you have Orange Fox Recovery, use the built-in Magisk Manager.

If after installing the next Magisk module the device does not boot into the system, install this script. It will find the newest directory in /data/adb/modules/ and remove it.

You can do this manually. This script simplifies and automates this process. It will not restore your system if the previous module permanently deleted system files. Please read the description and do Nandroid Backup before installing new unfamiliar modules.

Each subsequent installation of the script will remove new modules one by one in descending order of installation time. Until the modules run out.

Best regards! 

### Link
- https://github.com/PycmShoma/RemoveLastMagiskModule/releases 

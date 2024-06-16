# Windows PE Basic Enhanced
Windows PE Basic Enhanced is a portable Windows recovery, deployment, troubleshooting and diagnostic tool that is based from Windows 11 PE version 24H2 (Windows ADK May 2024). <br>
It is inspired by my other project which is Windows PE Basic that is located on https://github.com/thedoggybrad/WindowsPEBasic/.

## Download Link (391Mb ISO File)
[https://github.com/thedoggybrad/WindowsPEBasicEnhanced/releases/download/1.0/WinPEBasicEnhanced.iso](https://github.com/thedoggybrad/WindowsPEBasicEnhanced/releases/download/1.0/WinPEBasicEnhanced.iso)

## Minimum System Requirements
•Storage: 400MB of FAT/FAT32/NTFS Bootable Storage<br>
•Memory: 512MB<br>
•CPU: Any 64-bit capable processor<br>
•GPU: None (Just a video output is needed)<br>
•BIOS: Legacy BIOS or UEFI BIOS

## Preferred System Configuration (For Optimal Performance)
•Storage: 512MB of NTFS Bootable Storage or higher capacity<br>
•Memory: 1GB or higher<br>
•CPU: A dual-core 64-bit capable processor or better<br>
•GPU: On-board Integrated Graphics or better<br>
•BIOS: Legacy BIOS or UEFI BIOS

## Additional Custom Tools
It contains the following set of custom tools, I personally added that are useful for troubleshooting, diagnostic and recovery:
<br>
•cpuz.exe - CPUID CPU-Z<br>
•DiskInfo.exe - Crystal Disk Info<br>
•DiskView.exe - SysInternals DiskView<br>
•explorer.exe - Explorer++ (Not Windows Explorer)<br>
•HWMonitor.exe - CPUID Hardware Monitor<br>
•procexp.exe - SysInternals Process Explorer<br>
•procmon.exe - SysInternals Process Monitor<br>
•RAMMap.exe - SysInternals RAM Map <br>

## Tools and Commands from Windows PE
Plus all of the built-in tools and commands from Windows PE that compose of selected Windows NT tools such as Notepad, Registry Editor, Task Manager, SFC, DISM, BCDBOOT,  DIR, DISKPART, CHKDSK, MD, CD and more.<br>
Some familar commands from Windows NT such as SHUTDOWN and more are not available (Research about commands and tools available on Windows PE).

## Basic Operation
1.) To Restart your PC, type "exit" on the Command Prompt window and hit ENTER. Shutdown is not supported.
<br>
2.) The UI is commandline, so to access GUI/Non-GUI apps you need to type the exact application name in the Command Prompt window. For my custom tools, just refer to the ".exe" titles and for built-in Windows PE tools and commands be sure to research or memorize it.
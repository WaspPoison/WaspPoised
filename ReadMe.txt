WINDOWS 2000 PROFESSIONAL CONTROL PANEL PORT, BOOT, & BANNERS README:
------------------------------------------------------------------------------------

In Windows XP, Setup.exe installs the Windows 2000 .cpl files,  updates your NTOSKRNL for an integrated Windows 2000 Professional bootscreen (v1.0), replaces your start menu banner with Windows 2000 Professional, Overwrites your Winver NT version as 5.0 (Build 2195) 
including OEM Windows 2000 banners for logon\winver. 
System Properties will display Microsoft Windows 2000 5.00.2195 <servicepack#> 
DO NOT USE ON ANY OTHER WINDOWS VERSION EXCEPT XP

Using Setup.exe:
-Run Setup.exe, select your Windows XP c:/windows/, open newfound windows folder in c:\windows\windows\ 
-keep one explorer window at c:\windows\windows open, and another window at c:\windows\
-move c:\windows\explorer.exe to desktop, move c:\windows\windows\explorer.exe to c:\windows\
-Navigate to c:\windows\system32\ in one window, and to c:\windows\windows\system32 in another
-One at a time & in short time frame between moving file to desktop, then moving the replacement file is the most effective way  
-follow the procedure you did with explorer.exe, except with the files found in c:\windows\windows\system32
   ex: move access.cpl from c:\windows\system32 to desktop, in small time frame move c:\windows\windows\system32\access.cpl to c:\windows\system32\
       continue this pattern with the rest of the files in c:\windows\windows\system32 ONE AT A TIME, with proper care for bypassing windows file protection taken

Using .zip Install:
-all files included in the installer are in the provided WINDOWS.zip folder. Copy what's in the root directory of 
 said WINDOWS folder to your WinXP C:\Windows\ and what is in the System32 folder to your 
 C:\Windows\System32\ 

[if when running the installer you select c:\, this should move the file write process to overwrite the system files, but 
the installer v1.0 fails to do so, working on a v2.0, but in the meantime you can still use it, just a lot more hands on of a process (see line 9 'Using Setup.exe:')] 

 -Juicifer/WaspPoison

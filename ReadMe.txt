WINDOWS 2000 PROFESSIONAL CONTROL PANEL PORT, BOOT, & BANNERS README:
------------------------------------------------------------------------------------

including OEM Windows 2000 banners for logon\winver\start, edited winver display of Version 5.0 (Build 2195). 
System Properties will display Microsoft Windows 2000 5.00.2195 <servicepack#> 
DO NOT USE ON ANY OTHER WINDOWS VERSION EXCEPT XP

-If using bootskin or are prone to ntoskrnl bsod errors and don't want to deal with that again, don't copy ntoskrnl.exe and ntoskrnlpa.exe. They do work for 
 me, but I understand the fear because of how easily to ntoskrnl.exe files in Windows trip a BSOD for seemingly no reason. Just my warning that these two files are the only 
 files included that COULD brick your system, but if you skip them I'd say you should have a 100% success rate with installing the .cpls and everything else, you can save 
 patching ntoskrnl for later. Optimally you should open your native ntoskrnl in resource hacker and replace the bitmaps, you can simply follow my ntoskrnl bitmap layout. Just 
 extract a .res file from the included ntoskrnl and replace the ones in yours (in safe mode) 

Using Win2K CPL Port WinXP v1.exe install:
-Run Win2K CPL Port WinXP v1.exe, select your Windows XP c:/windows/, open newfound windows folder in c:\windows\windows\ 
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
the installer v1.0 fails to do so, working on a v2.0, but in the meantime you can still use it, just a lot more hands on of a process (see line 9 'Using Win2K CPL Port WinXP v1.exe: install')] 

 One more thing: 
 -Juicifer/WaspPoison

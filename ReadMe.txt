WINDOWS 2000 PROFESSIONAL CONTROL PANEL PORT README:
------------------------------------------------------------------------------------
INSTALLER V2 INSTALLATION INSTRUCTIONS:
 -Run WaspPoisedNT5CPL_v2.exe
 -Select path of your HDD if not C:\ (Should be by default c:\)
 -click 'install'
 -If wuaucpl.cpl gives any problems, hit ignore
 -install complete if Windows File Protection was disabled

wuaucpl.cpl fix:
  -Navigate to c:\windows\system32\
  -move native wuaucpl.cpl to your desktop
  -Run WaspPoisedNT5CPL_v2.exe and complete installation

disabling Windows File Protection:
  -press win key + R
  -run 'regedit'
  -navigate to HKEY_LOCAL_MACHINE/SOFTWARE/Microsoft/Windows NT/Current Version/Winlogon
  -In the right hand pane find 'SFCDisable' (REG_DWORD Value)
  -open/double-click SFCDisable
  -Change the value data to '1'
  -reboot
  -open services.msc in run (Win Key + R)
  -disable Cryptographic Services and stop the service
  -disable Protected Storage and stop the service
    [watch the services.msc page routinely for a minute or two, the 
    Cryptographic Services service might start up again very quickly despite 
    being disabled, just stop the service again and eventually it won't 
    start again]
  -go to c:\windows\system32
  -move dllcache folder to your desktop, this is a hidden folder
  -hit serch files, search 'SFC'
  -delete SFC.exe sfcfiles.dll and sfc.dll
  -if windows file protection rewrites these files, check services.msc to 
   see if Cryptographic Services has started again, as this is the main 
   cause 

 -WaspPoison

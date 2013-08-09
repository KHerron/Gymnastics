Gymnastics for 64 Bit ahscript
==========

Performs the Gymnastics required to register the X10 ahscript.dll as a COM+ service.

This is required for the CM15A plugin for OSA (Open Source Automation) to operate on a 64 Bit computer.

The X10 ahscript.dll that is distributed with the X10 SDK or other x10 software is written in 32 bit ONLY.
In order for a 64 bit Application or Service to register or perform calls to this file, you must build a "Wrapper".

This is done using Component Services, but can be a little confusing.

However, to solve the confusion, sinmply run this setup.exe file.

Files extracted
---------------
Gymnastics for 64 Bit ahscript.exe
ahscript.dll
CM15A_ComServ.MSI
CM15A_ComSer.MSI.cab
uninstall.exe
uninstall.ini

Gymnasticts for 64 Bit ahscript will launch automatically.

Simply follow the 3 easy screens, and POOF your done.

You can also use the uninstall to remove these files.
The unistall does NOT remove the component service.

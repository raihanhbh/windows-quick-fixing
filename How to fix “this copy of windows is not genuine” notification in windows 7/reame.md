Procedure to fix "this copy of windows is not genuine" notification:

The whole process can be divided into two parts:
PART A - Uninstalling Windows Update: KB971033
PART B - Rearm Windows

The so notification is because of Windows Update: KB971033. You need to uninstall it. It will not affect anything else in your system. Follow these simple steps to uninstall it-


PART - A: Uninstalling Windows Update: KB971033
---------------------------------------------------
Go to Windows Update
Hit Installed Updates (link at the bottom left corner). If that link isn’t there, hit “view update history” and hit the “installed updates” link at the top.
Scroll down to the section titled “Microsoft Windows” and look for update KB971033.
Right click it and hit “uninstall”. Hit okay.

PART - B: Rearm Windows:
---------------------------------------------------

Click start and simply type CMD in the start menu’s search box. Right click COMMAND PROMPT and select RUN AS ADMINISTRATOR.
 

 2. In the command prompt window type: 

  slmgr.vbs -rearm and press enter. (Note that there is a space between slmgr.vbs and -rearm.)
 
 3.Now reboot and you're good to go.

Be sure to turn off windows update or else you will face the same problem again. Alternatively, you can hide Windows Update: KB971033 in your windows update history.
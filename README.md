Step1: Open x64 native tools command prompt for vs
Step2: goto project directory
step3: comiple program: cl.exe /c /EHsc Window.c
step4: if compile successfull then Run Program : Link.exe Window.obj User32.lib gdi32.lib /SUBSYSTEM:WINDOWS
step5: if Link is successfully then exucate this :E:\My Project\WinDev-2024\01-Win32\01-Windowing\01-FirstWindows>Window.exe

#1/3/2021 Release
##Python v3.7

###This is only a joke excuted-file.
It will only unmount drive(C:\\) on the computer.  

----

>In usually,we are not allowed to unmount C: although in disk manager.  

But we can do it with a command.
```  
mountvol C:\ /d  

moountvol [drivepath:] /d  
```
In fact,replace \[drivepath:] to drivepath(Such as `C:\`,`D:\`,`E:\`),  
you can unmount every drive.
Execute them in `cmd.exe` or save as a .bat file.  
#####Tips:__These commands need Administrator privilege.__
---
I just code them into python code and compiled to EXE with pyinstaller,so they
will not doubt the executed file or edit the file code.
I also changed the manifest so the file will ask you Administrator privileges and it will not be this:
```
Access Denied.
```
---
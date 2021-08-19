## Restoring  console colors in windows 10

I noticed colors look wrong with Far Manager - my favorite file manager app. ;)

Why: Microsoft folks decided to “update” the colors by “brightening” the palette in Windows 10 1709.   [info](https://devblogs.microsoft.com/commandline/updating-the-windows-console-colors/) 

So how to revert to old colors:
Microsoft released  [Color Tool](https://github.com/microsoft/terminal/releases/tag/1708.14008) . Download it, extract it, copy files colortool.exe and campbell-legacy.ini somewhere and then run this command:

```
colortool.exe -b campbell-legacy.ini
``` 


This will affect the colors for both the current console and for the default console.


src: 

 [link](https://www.oboroc.com/posts/2020/06/09/restoring-classic-colors-in-windows-10-console/) 


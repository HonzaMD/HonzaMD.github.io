---
layout: mainen
title: KRKAL 1 DosBox Settings
lang: en
submenu: krkal1
---
# K1 DosBox Settings

Here you can find recommended changes to [DosBox](http://www.dosbox.com/) settings (version 0.74).

output=ddraw  
aspect=TRUE  
scaler=normal2x  
cycles=fixed 10000  

Settings *output*, *aspect* and *scaler* allow to properly scale up the original low resolution 320x200. You can also choose between window and fullscreen mode or adjust the screen resolution.  
The most important is the setting *cycles*. In order for Krkal to move smoothly, it is necessary to set fixed cycles in the range 10000 to 15000.  
Finally, edit the section *\[autoexec\]* and add there the *mount* command. For example:

mount c d:\dosgames  
c:
